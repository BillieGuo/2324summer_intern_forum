# Coding Style (Version 1.0)

Notion: https://perpetual-spectacles-12d.notion.site/Coding-Style-Version-1-0-e99a0c3cdc5b4a87abd88a4a8834c9f8?pvs=4

## 1. Function Naming Style & Briefing

- Function names should be intuitive and straightforward, clearly describing the purpose of the function.
- Use a combination of verbs and nouns to create meaningful function names (e.g., `calculateTotalCost()`, `validateUserInput()`).
- Provide a brief comment or docstring at the beginning of each
function to explain its purpose, expected parameters, and return value.

## 2. Parameters: Meanings & Types

- Clearly document the meaning and expected data types of each function parameter.
- Use descriptive parameter names that convey their purpose (e.g., `userName`, `emailAddress`, `isActive`).
- Ensure that the function signature accurately reflects the actual parameters being used within the function's implementation.

## 3. Modifying Source Code

- **IF ANY SOURCE CODE IS MODIFIED, CLEARLY STATE WHERE AND WHAT YOU HAVE CHANGED FOR OTHERS LATER CODE REVIEW.**
- Try avoiding modifying the source code unless it's absolutely necessary.
- If changes are required, ensure that they are well-documented and do not break existing functionality.
- Before making any modifications, thoroughly test the changes to ensure they don't introduce new bugs or regressions.

## 4. GitHub Repository Guidelines

- Repository Structure:
    - Keep the repository structure clean and organized, with the source code in dedicated packages.
    - Showcase the packages or modules in the root of the repository, without the `src/` directory.
- Code Quality:
    - The code pushed to the GitHub repository should be stable and ready for demonstration.
    - Ensure that the code is well-commented, easy to understand, and follows the established coding style guidelines.
- Q&A and Collaboration:
    - A general repository for questions, answers, and collaborative discussions related to the project.
    - This separate repository can serve as a hub for the community to engage, share knowledge, and troubleshoot issues.

## 5. Code Review

- There should be a rigorous code review process to maintain code quality and consistency.
- Assign at least one other team member to review any proposed changes before merging them into the main branch.
- During the review process, ensure that the code adheres to the established coding style, follows best practices, and does not introduce new bugs or regressions.

## 6. Coding Conventions

- Adhere to the language-specific coding conventions and best practices.
- For example, in Python, follow the [PEP 8 style guide](https://www.python.org/dev/peps/pep-0008/), and in JavaScript, follow the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
- Consistency in coding style across the codebase is crucial for maintainability and collaboration.

## 7. Commenting and Documentation

- Write clear and concise comments to explain the purpose, functionality, and edge cases of the code.
- Document any important design decisions, assumptions, or constraints within the codebase.
- Ensure that the comments are up-to-date and accurately reflect the current state of the code.

## 8. Error Handling and Logging

- Try implementing robust error handling mechanisms to gracefully handle unexpected scenarios.
- Provide clear and informative error messages that help the user or developer understand the issue.
- Use a structured logging approach to capture relevant information for debugging and troubleshooting purposes.

## 9. Testing and Quality Assurance

- Develop a comprehensive suite of automated tests (unit tests, integration tests, end-to-end tests) to ensure the reliability and correctness of the codebase.
- Regularly review and maintain the test suite to keep it up-to-date with the evolving codebase.