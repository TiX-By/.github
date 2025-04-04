# Contributing Guidelines

Thank you for contributing to our project! We appreciate your help in maintaining a high-quality codebase. Please follow the guidelines below to ensure a consistent workflow.

---

## Table of Contents

- [Branching Strategy](#branching-strategy)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Pull Request Process](#pull-request-process)
- [Task Linking and ClickUp Integration](#task-linking-and-clickup-integration)
- [Alternative Branch Naming](#alternative-branch-naming)
- [Code Standards](#code-standards)
- [Testing and CI](#testing-and-ci)
- [Getting Help](#getting-help)

---

## Branching Strategy

- **Primary Branches:**

  - `main` (or `master`): Contains production-ready code.
  <!-- - `develop`: A staging branch for integration (if used). -->

- **Feature/Fix Branches:**
  - Create a new branch for every feature, bugfix, or hotfix.
  - **Naming Convention:** Use descriptive names such as: - `feature/new-user-login` - `bugfix/fix-payment-error`
  <!-- - **Release Branches:**
  - Use `release/` branches when preparing a new version for production. -->

---

## Commit Message Guidelines

- **Structure:** Follow the conventional commits format:
  - `type(scope): subject`
    - **Example:** `feat(auth): add JWT authentication`
- **Commit Types:**
  - `feat`: New features
  - `fix`: Bug fixes
  - `docs`: Documentation changes
  - `style`: Code formatting or style changes
  - `refactor`: Code restructuring without functionality changes
  - `test`: Adding or updating tests
  - `chore`: Other maintenance tasks
- **Best Practices:**
  - Use the imperative mood (e.g., "Add," "Fix," "Update").
  - Keep subject lines concise (50–72 characters).
  - Reference ClickUp tasks by including either an abbreviated task ID or a URL.
    - **Example:** `feat(auth): add JWT authentication, relates to CU-1234`  
      or  
      `fix(payment): resolve timeout issue – [ClickUp Task](https://app.clickup.com/t/your-task-id)`

---

## Pull Request Process

- **Creating a PR:**
  - Always open a pull request from your feature or fix branch.
  - Include a PR template that includes the following sections:
    - **Summary:** A brief description of the changes introduced by this pull request.
    - **Related Task/Issue:** A link or reference to the associated ClickUp task or GitHub issue (e.g., CP-1234 or [ClickUp Task](https://app.clickup.com/t/your-task-id)).
    - **Changes Made:** A concise list of the primary modifications or features implemented.
    - **Testing Instructions:** Steps to verify the changes, including any necessary test cases.
    - **Impact:** Details on potential effects on interconnected applications or components.
    - **Optional Visuals:**  
      If your PR includes UI changes or visual updates, please add annotated images or GIFs that clearly showcase the modifications.
- **Review Requirements:**
  - Request at least one or two peer reviews depending on the change's complexity.
  - Ensure all automated tests and CI checks pass before merging.
- **Merging:**
  - Use “squash and merge” (or an agreed-upon strategy) to maintain a clean commit history.

---

## Task Linking and ClickUp Integration

- **Referencing Tasks:**
  - Include ClickUp task links or abbreviated IDs in your commit messages and PR descriptions.
  - This helps trace the work back to the original task.
- **Workflow:**
  - Update the status of ClickUp tasks as work progresses.
  - Ensure that any reference (abbreviated or full) in the branch name or commits corresponds to the correct task in ClickUp.

---

## Code Standards

- Ensure your text editor or IDE enforces linting and formating in your code.
- Write clean, modular, and well-documented code.
- Ensure all new features or fixes include the necessary tests and documentation.

---

## Testing and CI

- Run tests locally before submitting your PR.
- Ensure your changes pass all automated tests in our CI/CD pipeline.
- Write new tests for added features or bug fixes where applicable.

---

## Getting Help

- If you have questions or need guidance, please reach out via our team's Slack.
- We’re here to help and appreciate your contributions!

---

Thank you for helping improve our projects!
