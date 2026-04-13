---
applyTo: "src/app.py,src/backend/**/*.py"
---

## Backend Guidelines

- Keep API behavior stable unless the request explicitly changes it.
- Validate request inputs and return explicit HTTP errors for invalid data.
- Prefer clear router-level logic and keep data access concerns in the database module.
- Use type hints for new or updated Python functions.
- Avoid introducing new dependencies unless they are necessary.
- Handle failures explicitly and avoid silent exception swallowing.
- Keep endpoint responses consistent and predictable for frontend consumers.
- Preserve readability and maintainability over premature optimization.
