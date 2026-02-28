```markdown
# AGENTS.md File Guidelines

These guidelines outline the principles and rules for development of the AGENTS.md repository. Adherence to these principles is crucial for maintaining a clean, maintainable, and reliable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Code Reuse:** Avoid duplicating code across different files and modules.  Identify and extract common logic into reusable components.
*   **Abstraction:**  Wherever possible, abstract common functionality into separate, well-defined modules or classes.
*   **Single Responsibility Principle:** Each module/class should have a single, well-defined responsibility.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Complexity:**  Strive for the simplest possible solution that meets the requirements. Avoid unnecessary complexity.
*   **Readability:** Prioritize code clarity. Use meaningful variable and function names.
*   **Conciseness:**  Write concise and direct code.  Avoid overly verbose constructs.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Modules should have single, well-defined purposes.
*   **Open/Closed Principle:**  Modules should be open for extension but closed for modification.  New functionality should be added through new modules, not through modification of existing ones.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to implement interfaces they do not use.
*   **Dependency Inversion Principle:** High-level modules should be able to be substituted with low-level modules without affecting the high-level behavior.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Do not implement features or logic that are not currently required.
*   **Refactoring Only When Necessary:**  Refactor only when there is a significant reason to improve the code's structure or maintainability.

## 5. Code Length & Structure

*   **Maximum Code Length:** Each file shall not exceed 180 lines of code.  Any file exceeding this limit will be rejected for review.
*   **Modular Structure:**  Organize code into logical modules and classes. Use clear naming conventions.
*   **Comments:**  Provide clear and concise comments explaining complex logic, assumptions, or design decisions.  Don't comment obvious code.
*   **Consistent Formatting:**  Maintain consistent indentation, spacing, and line breaks throughout the codebase.

## 6. Testing

*   **All Development Must Be Productive:**  Prioritize the creation of unit, integration, and end-to-end tests.
*   **Mocking/Stubbing:**  All mocks, stubs, and test environments must be implemented and used.  No reliance on external dependencies or real systems are permitted.
*   **Automated Testing:**  Ensure all tests are automated and run regularly.

## 7. File Structure

*   **Clear Directory Layout:** Organize files into logical directories with appropriate naming conventions.
*   **Naming Conventions:** Follow a consistent naming convention for modules, classes, and functions.
*   **Documentation:**  Include a brief description of each file's purpose in the README file.

## 8. Specific Considerations for AGENTS.md

*   **Data Structures:** Clearly define data structures and their intended usage.
*   **API Design:**  Document the API for any external components or integrations.
*   **Error Handling:**  Implement robust error handling and logging.

## 9.  Code Quality

*   **Code Reviews:** Encourage regular code reviews to identify potential issues and ensure adherence to best practices.
*   **Static Analysis:** Utilize static analysis tools to automatically detect potential errors and style violations.

## 10.  Deliverables

*   **README.md:** Provide a README explaining the purpose of the repository, how to run the code, and key dependencies.
*   **Unit Tests:**  A comprehensive suite of unit tests covering all significant functionality.
*   **Documentation:**  Clear and concise documentation for all modules, classes, and functions.

These guidelines are intended to establish a sustainable and high-quality development process for the AGENTS.md repository.  Violations of these principles may result in rejection of code and potential project revisions.
```