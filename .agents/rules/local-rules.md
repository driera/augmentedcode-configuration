# Working with Dani

> Customize this file with machine-specific guidance. It extends `AGENTS.md` and overrides the shared rules whenever they conflict.

## Code Writing

- YOU MUST ALWAYS address me as "Dani" in all communications.
- We STRONGLY prefer simple, clean, maintainable solutions over clever or complex ones. Readability and maintainability are PRIMARY CONCERNS, even at the cost of conciseness or performance.
- YOU MUST make the SMALLEST reasonable changes to achieve the desired outcome.
- YOU MUST MATCH the style and formatting of surrounding code, even if it differs from standard style guides. Consistency within a file trumps external standards.
- YOU MUST NEVER make code changes unrelated to your current task. If you notice something that should be fixed but is unrelated, document it rather than fixing it immediately.
- YOU MUST NEVER remove existent code comments unless you can PROVE they are actively false. Comments are important documentation and must be preserved.
- YOU MUST NEVER refer to temporal context in comments (like "recently refactored"). Comments should be evergreen and describe the code as it is.
- YOU MUST NEVER throw away implementations to rewrite them without EXPLICIT permission. If you're considering this, YOU MUST STOP and ask first.
- YOU MUST NEVER use temporal naming conventions like 'improved', 'new', or 'enhanced'. All naming should be evergreen.
- YOU MUST NOT change whitespace unrelated to code you're modifying.

## Core Principles

- Baby Steps: Always work in baby steps, one at a time. Never go forward more than one step.
- Test-Driven Development: Start with a failing test for any new functionality (TDD).
- Progressive Revelation: Never show all the code at once; only the next step.
- Type Safety: All code must be fully typed.
- Simplicity First: Use the simplest working solution; avoid unnecessary abstractions.
- Small Components: Functions, classes and methods should be small (10–20 lines max).
- Clear Naming: Use clear, descriptive names for all variables and functions.
- Incremental Changes: Prefer incremental, focused changes over large, complex modifications.
- Question Assumptions: Always question assumptions and inferences.
- Refactoring Awareness: Highlight opportunities for refactoring and flag functions exceeding 20 lines.
- Pattern Detection: Detect and highlight repeated code patterns.

## Code Quality & Coverage

- MANDATORY Validation: Before EVERY commit, run `make lint` and `make check-types` and fix ALL errors. Zero tolerance.
- Quality Requirements: The project has strict requirements for code quality and maintainability.
- High Coverage: All code must have very high test coverage; strive for 100% where practical.
- Pre-commit Checks: All code must pass the following before any commit:
  - make check-types
  - make lint
  - make test
- TDD Workflow: Test-Driven Development (TDD) is the default workflow: always write tests first.
- FP Design: Use Functional Programming (FP) for all components and features.

## Version Control

- For non-trivial edits, all changes MUST be tracked in git.
- If the project isn't in a git repo, YOU MUST STOP and ask permission to initialize one.
- If there are uncommitted changes or untracked files when starting work, YOU MUST STOP and ask how to handle them. Suggest committing existing work first.
- Follow team convention for naming the commit: "[APP-01234] Descriptive commit message"
- YOU MUST commit frequently throughout the development process.

## Dependencies

- YOU MUST NOT install new dependencies without EXPLICIT permission. If you ever find the need to do so, YOU MUST STOP and ask first.

## Getting Help

- YOU MUST ALWAYS ask for clarification rather than making assumptions.
- If you're having trouble, YOU MUST STOP and ask for help, especially for tasks where human input would be valuable.

## Compliance Check

Before submitting any work, verify that you have followed ALL guidelines above. If you find yourself considering an exception to ANY rule, YOU MUST STOP and get explicit permission from Dani first.
