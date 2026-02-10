# CLAUDE.md

> Guidelines for AI assistants working in this repository.

## Project Overview

**MySpace** is a new project in its initial stage. The repository has been freshly initialized and is ready for development.

- **Owner:** bharathkgowda90
- **Repository:** MySpace
- **Primary branch:** `main`

## Repository Structure

```
MySpace/
├── CLAUDE.md          # AI assistant guidelines (this file)
└── README.md          # Project README
```

> Update this section as directories and files are added.

## Development Setup

No build system, package manager, or dependencies have been configured yet. When they are added, document the setup steps here:

```bash
# Example (update when applicable):
# git clone <repo-url>
# cd MySpace
# <install dependencies command>
```

## Build & Run Commands

No build or run commands are configured yet. Update this section as tooling is introduced.

<!-- Example entries to fill in later:
- **Install dependencies:** `npm install` / `pip install -r requirements.txt`
- **Build:** `npm run build` / `make build`
- **Run:** `npm start` / `python main.py`
- **Run single test:** `npm test -- --grep "test name"` / `pytest tests/test_file.py::test_name`
- **Run all tests:** `npm test` / `pytest`
- **Lint:** `npm run lint` / `ruff check .`
- **Format:** `npm run format` / `ruff format .`
-->

## Testing

No testing framework has been set up yet. When tests are added:

1. Document the test framework and configuration here
2. Include commands for running the full suite and individual tests
3. Note any test conventions (file naming, directory structure)

## Code Style & Conventions

No linter or formatter has been configured yet. When they are added, document:

1. The tools used (ESLint, Prettier, Ruff, Black, etc.)
2. How to run them
3. Any project-specific style rules

### General Conventions for Contributors

- Write clear, descriptive commit messages
- Keep changes focused and atomic
- Follow existing patterns when code is present in the repository

## CI/CD

No CI/CD pipeline is configured. When added, document:

1. Pipeline tool (GitHub Actions, etc.)
2. What checks run on PRs
3. Deployment process

## Architecture

No application code exists yet. When the project takes shape, document:

1. Language and framework choices
2. High-level architecture (e.g., MVC, microservices, monorepo)
3. Key modules and their responsibilities
4. Data flow and external dependencies

## AI Assistant Guidelines

When working in this repository:

1. **Read before writing** - Always read existing files before modifying them
2. **Stay focused** - Only make changes that are directly requested; avoid unnecessary refactoring
3. **Keep CLAUDE.md current** - Update this file when adding new tooling, frameworks, or significant structural changes
4. **Follow existing patterns** - Match the style and conventions already present in the codebase
5. **Don't over-engineer** - Prefer simple, direct solutions over abstractions for hypothetical future needs
6. **Test your changes** - Run the test suite (once it exists) before considering work complete
7. **Security first** - Never commit secrets, credentials, or sensitive data
