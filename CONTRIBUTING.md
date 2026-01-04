# Contributing to ecom.house projects

First off, thank you for considering contributing! It's people like you who make our tools better for everyone.

## Coding Standards

To maintain code quality and consistency across all our modules, we strictly follow these rules:

* **Language:** All code, variable names, and inline comments must be written in **English**.
* **Style:** We adhere to the [PSR-12 Extended Coding Style Guide](https://www.php-fig.org/psr/psr-12/).
    * Please run a linter (like PHP_CodeSniffer) before submitting your PR.
* **Type Hinting:** Use strict typing (`declare(strict_types=1);`) and proper return types wherever possible.

## Pull Request Process

To ensure a smooth review process, please follow these steps:

1.  **Tests are Required:** * Every Pull Request must include relevant tests (Unit, Integration, or Functional).
    * Existing tests must pass. We will not merge code that breaks the current build or lowers test coverage.
2.  **Branching:** Create a descriptive branch name for your work (e.g., `fix/issue-header-alignment` or `feat/add-login-support`).
3.  **Atomic Commits:** Keep your commits small and focused on a single change.
4.  **Documentation:** Update the `README.md` or any other documentation if your change introduces new functionality or changes existing behavior.

## Reporting Issues

If you find a bug or have a feature request, please open an issue in the specific repository. Provide as much detail as possible, including:
* Steps to reproduce (for bugs).
* Expected vs. actual behavior.
* Environment details (PHP version, OS, etc.).

## Questions?

If you have any questions regarding the contribution process, feel free to reach out to us at [opensource@ecom.house](mailto:opensource@ecom.house).

---
*By contributing, you agree that your contributions will be licensed under the project's existing license.*
