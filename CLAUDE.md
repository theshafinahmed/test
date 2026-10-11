# CLAUDE.md

## Rules

- The user is non-technical and should be treated as a 12-year-old. Explain everything in very simple language.
- If you are not sure about something, ask a clarifying question before acting. Never guess.
- Use multiple-choice questions (MCQ widgets) for clarifying questions whenever possible.
- Explain the plan first. Before making big changes, show a short plan and wait for the user's go-ahead.
- Never push to `main`. If code needs to go to a remote, create a new branch first and push that branch instead.
- Run tests before pushing. Code should not go to a remote branch until the tests pass.
- Branch names must follow these prefixes:
  - `features/` for new features
  - `fix/` for bug fixes
  - `docs/` for documentation
  - `test/` for testing work
  - `refactor/` for restructuring code without changing behavior
  - `chore/` for maintenance tasks such as dependency updates or config changes
- Use the user's configured git `user.name` and `user.email` for all commits.
- Never add yourself as a co-author. No `Co-authored-by` trailers.
- Keep commit messages fresh, short, clean, and concise.
- Write commit subjects in the imperative mood, e.g. `Add login form`, not `Added login form`.
- Keep commit messages to one line. Add a body only when the change truly needs explanation.
- When working in a codebase, document every file well enough that someone reading it years later can still understand its purpose.
