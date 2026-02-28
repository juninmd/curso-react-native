```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines outline the principles and rules for development of this AI coding agent repository. Adherence to these principles is crucial for ensuring maintainability, reliability, and quality of the generated code.

## 1. DRY (Don't Repeat Yourself)

*   Each function, class, and module should have a single, well-defined purpose.
*   Avoid duplicate code. Refactor existing duplicate code to improve clarity and reusability.
*   Document the purpose of functions and classes clearly.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize simplicity and readability over complex solutions.
*   Use the most straightforward approach for each task.
*   Avoid unnecessary abstraction or convoluted logic.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be extensible without modification. (Implementation can be changed, but core interface should remain unchanged).
*   **Liskov Substitution Principle:** Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients shouldn't be forced to wringe the interface of a class.
*   **Dependency Inversion Principle:** Client code shouldn't depend on implementation details; it should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only what is absolutely necessary to achieve a specific goal.
*   Don't introduce functionality that is likely to be obsolete or removed in the future.
*   Refactor code to remove obsolete functionality.

## 5. Testability & Mocking Focus

*   All development must be productive.
*   Mocks are exclusively used for unit testing.
*   Test cases should be designed to thoroughly cover critical functionality.
*   Maintainable test code should be prioritized over immediate production code.
*   Prioritize tests that accurately reflect the expected behavior.
*   Each file must have a maximum of 180 lines of code.

## 6. Code Length Constraints

*   Each file must have a maximum of 180 lines of code.

## 7.  Code Quality & Style

*   Adhere to PEP 8 coding style guidelines.
*   Use meaningful variable and function names.
*   Include clear and concise comments where necessary.
*   Maintain consistent indentation and spacing.
*   Follow established naming conventions.

## 8.  Module Structure

*   Organize code into logical modules.
*   Each module should have a single, well-defined responsibility.
*   Use consistent folder structures.

## 9.  Error Handling

*   Implement basic error handling to prevent crashes.
*   Return appropriate error codes or messages in case of failure.

## 10.  Documentation

*   Provide clear and concise documentation for each function and class, including parameter descriptions, return values, and potential side effects.
*   Include a brief README file explaining the project's purpose, dependencies, and usage.

## 11.  Data Handling

*   Utilize appropriate data structures for efficiency.
*   Avoid unnecessary data duplication.
*   Document data structures and their meanings.

## 12.  Algorithm Considerations (Limited Scope -  focus on core logic)**

*   Consider algorithmic efficiency when designing core logic.
*   Avoid computationally expensive operations.

## 13. Dependency Management (Simplified - focus on core components)**

*   Utilize a dependency management system to keep track of external library dependencies.
*   Document required dependencies clearly.

## 14.  Traceability & Version Control

*   Use a version control system (e.g., Git) for all code changes.
*   Implement clear commit messages describing changes.
*   Track changes using meaningful commit IDs.

## 15.  Commit Practices

*   Commit frequently with small, logical changes.
*   Write clear commit messages explaining the *why* behind the changes.
*   Strive for a consistent commit history.
```