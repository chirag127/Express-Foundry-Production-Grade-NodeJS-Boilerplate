# Contributing to RapidStart-Express-NodeJS-WebApp-Template

## 1. Introduction
Welcome and thank you for considering contributing to `RapidStart-Express-NodeJS-WebApp-Template`! We appreciate your efforts to improve this project. By participating, you uphold our professional standards and help us maintain a high-quality, production-ready boilerplate.

## 2. Code of Conduct
Please review our [Code of Conduct](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/blob/main/CODE_OF_CONDUCT.md) to understand the expectations for all community members. We are committed to fostering an inclusive and respectful environment.

## 3. How Can I Contribute?
We welcome contributions in various forms:

*   **Reporting Bugs:** Found an issue? Please open a new [Bug Report](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/issues/new?assignees=&labels=bug&projects=&template=bug_report.md&title=%5BBUG%5D%3A+). Provide clear steps to reproduce, expected behavior, and actual behavior.
*   **Suggesting Enhancements:** Have an idea for a new feature or improvement? Open an issue to discuss it first. This helps ensure alignment with the project's vision.
*   **Writing Code:** Implement new features, fix bugs, or refactor existing code. Please follow our coding guidelines.
*   **Improving Documentation:** Enhance READMEs, inline code comments, or create usage guides. Clear documentation is crucial for usability.

## 4. Setting Up Your Development Environment

### Prerequisites
Ensure you have the following installed on your system:

*   **Node.js**: `v18.x` or higher (LTS recommended).
*   **npm**: Comes bundled with Node.js.
*   **Git**: For version control.
*   **(Optional) Docker & Docker Compose**: For containerized development and deployment workflows.

### Installation Steps
1.  **Fork the Repository:** Navigate to the `RapidStart-Express-NodeJS-WebApp-Template` repository on GitHub and click the "Fork" button.
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/<YOUR_GITHUB_USERNAME>/RapidStart-Express-NodeJS-WebApp-Template.git
    cd RapidStart-Express-NodeJS-WebApp-Template
    
3.  **Install Dependencies:**
    bash
    npm install
    
4.  **Run in Development Mode:**
    bash
    npm run dev
    
    The application should now be running, typically accessible at `http://localhost:3000`.

## 5. Coding Guidelines

### Style & Formatting
We utilize **Biome** for consistent code style and formatting across the project. This ensures readability and maintainability.

*   Before committing, ensure your code is formatted:
    bash
    npm run format
    
*   Address any linting issues reported by Biome:
    bash
    npm run lint
    

### Commit Messages
We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification. This enables automated changelog generation and a clear, semantic commit history.

*   **Examples:**
    *   `feat(auth): Implement user registration endpoint`
    *   `fix(api): Resolve issue with unhandled null responses`
    *   `docs(readme): Update setup instructions for Docker`
    *   `chore(deps): Upgrade express to latest stable version`

## 6. Testing

### Running Tests
We use **Vitest** for robust unit and integration testing. All new features and bug fixes should include appropriate tests, aiming for high code coverage.

*   Run all tests:
    bash
    npm test
    
*   Run tests in watch mode (for active development):
    bash
    npm run test:watch
    
*   Generate code coverage reports:
    bash
    npm run test:coverage
    

## 7. Pull Request Process

1.  **Create a New Branch:**
    bash
    git checkout -b feature/your-descriptive-feature-name
    
    or for bug fixes:
    bash
    git checkout -b bugfix/your-bug-fix-description
    
2.  **Make Your Changes:** Implement your feature or bug fix following the coding guidelines.
3.  **Write Tests:** Ensure your changes are adequately covered by new or updated tests.
4.  **Run Tests & Linting:** Verify that all tests pass and linting checks are clean before pushing (`npm test` and `npm run lint`).
5.  **Commit Your Changes:** Use [Conventional Commits](#commit-messages) for clear commit messages.
6.  **Push Your Branch:**
    bash
    git push origin feature/your-descriptive-feature-name
    
7.  **Create a Pull Request:**
    *   Go to your forked `RapidStart-Express-NodeJS-WebApp-Template` repository on GitHub.
    *   Click the "New Pull Request" button.
    *   Fill out the [Pull Request Template](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/compare) thoroughly, providing a clear description of your changes, the problem they solve, and any relevant screenshots or steps to reproduce.

## 8. Security Vulnerabilities
If you discover a security vulnerability, please report it responsibly by following our [Security Policy](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/blob/main/SECURITY.md). Do not open a public issue or expose sensitive information.

## 9. License
By contributing to this project, you agree that your contributions will be licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/blob/main/LICENSE).