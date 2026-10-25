
# GitHub Copilot Instructions for Python

## 1. Project Overview
- This is a Python project.
- Follow the existing project structure and conventions.
- Prefer simple, readable, maintainable solutions.
- If the project has existing documentation, read it before making major changes.

## 2. Python Coding Standards
- Use Python 3.12 or the version specified by the project.
- Follow PEP 8 style guidelines.
- Use descriptive variable, function, and class names.
- Use snake_case for variables and functions.
- Use PascalCase for class names.
- Use UPPER_SNAKE_CASE for constants.
- Keep functions focused on one responsibility.
- Avoid unnecessary code duplication.

## 3. Type Hints and Documentation
- Add type hints to new functions and methods.
- Add docstrings to public functions and classes.
- Explain complex logic with short comments.
- Do not add comments that merely repeat the code.

## 4. Error Handling
- Handle expected errors explicitly.
- Avoid broad except clauses unless justified.
- Never silently ignore exceptions.
- Validate user input where appropriate.
- Return clear and useful error messages.

## 5. Testing
- Use pytest if the project uses pytest.
- Add tests for new functionality.
- Add regression tests when fixing bugs.
- Include normal cases, edge cases, and invalid inputs.
- Do not delete existing tests just to make them pass.
- Run relevant tests after making changes.
- Report tests that could not be executed.

## 6. Security
- Never hardcode passwords, API keys, or tokens.
- Never commit secrets to the repository.
- Validate untrusted input.
- Avoid unsafe handling of files and external input.
- Do not weaken authentication or authorization.
- Flag potential security issues.

## 7. Dependencies
- Reuse existing project dependencies when practical.
- Do not add a dependency without explaining why it is needed.
- Follow the project's existing dependency management method.
- Do not upgrade unrelated packages unnecessarily.

## 8. Changes and Communication
- Inspect related files before changing code.
- Keep changes focused on the requested task.
- Preserve existing behavior unless a change is requested.
- Explain important design decisions.
- Summarize files changed and tests performed.
- Do not claim tests passed unless they were actually run.

