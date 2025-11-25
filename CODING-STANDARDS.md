# Coding Standards
These standards apply to all codebases
# Coding Standards

These coding standards apply to all repositories.  
Use this as the single source of truth for code style, structure, and expectations.

---

# General Principles
- Write clean, readable, maintainable code.
- Use meaningful names for variables, functions, and classes.
- Keep functions small and single-purpose.
- Avoid duplication (DRY) and follow SOLID principles.
- Add comments **only** for complex logic.
- Keep lines under 100–120 characters.
- Use environment variables for secrets and configuration.

---

# Python
- Follow [PEP8](https://pep8.org/) strictly.
- Use `snake_case` for variables/functions.
- Use `PascalCase` for classes.
- Use type hints everywhere.
- Use docstrings for classes, modules, and public functions.
- Use `pydantic` models for request/response validation.
- Use `async def` for FastAPI.

---

# JavaScript / TypeScript
- Use ESLint + Prettier (required).
- Use `camelCase` for functions/variables.
- Use `PascalCase` for classes/components.
- Default to `const`; use `let` only when needed.
- No `var` allowed.
- Use strict TypeScript (`"strict": true`).
- Organize files by feature/domain.

## React
- Always use functional components.
- Use hooks (`useState`, `useEffect`, `useMemo`).
- Use TypeScript interfaces for props.
- Keep components small & reusable.
- Use module-based or feature-based folder structure.

## Node.js Backend
- Use Fastify or Express.
- Separate routes, controllers, services, and models.
- Use async/await only (no callbacks).
- Centralized error handling.
- Validate request data always.

---

# Java (if used)
- Follow Google Java Style Guide.
- Use Javadoc for public APIs.
- Keep classes small and focused.

---

# .NET (if used)
- Follow Microsoft C# conventions.
- Use PascalCase for public members.
- Use async/await properly.
- Use XML comments for documentation.

---

# Testing
- Use automated tests for all critical features.
- Python: pytest  
- JS/TS: Jest  
- Java: JUnit  
- .NET: xUnit  

---

# Linting & Formatting
Required tools:
- Python: Black + isort + Flake8
- JS/TS: ESLint + Prettier
- Java: Checkstyle
- C#: dotnet format

---

# Code Review Guidelines
- All code must be reviewed before merging.
- Each PR must include:
  - Summary of changes
  - Screenshots (if UI)
  - Test results
  - Any breaking changes
- No direct commits to main branch.

---

# Extending This Document
Add project-specific standards when necessary.
