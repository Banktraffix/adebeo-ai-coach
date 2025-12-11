# Contributing

Thank you for your interest in contributing! We welcome contributions of all types: bug reports, feature requests, documentation fixes, tests, and code. This file explains how to get started and what we expect.

## What to expect
- Open an issue first for non-trivial changes or features so we can discuss the approach.
- For bugs or small improvements you may open a pull request directly.
- Be respectful and follow the Code of Conduct (see CODE_OF_CONDUCT.md).

## How to contribute
1. Fork the repository (or create a branch if you have write access).
2. Create a descriptive branch name: `feature/short-description` or `fix/issue-number-short`.
3. Make your changes in your branch.
4. Run tests and linters locally (see "Development setup" below).
5. Commit with clear messages (we use Conventional Commits - e.g. `feat:`, `fix:`, `chore:`).
6. Open a pull request against the `main` branch. Reference any related issue(s) in the PR description.

## Development setup
- Prerequisites: Node.js >= 14 (adjust to your project), Python (if applicable), etc.
- Install:
  - npm: `npm install`
  - yarn: `yarn`
- Run test suite:
  - npm: `npm test`
  - yarn: `yarn test`
- Lint and format:
  - npm: `npm run lint`
  - npm: `npm run format`

(Replace commands above with your project's actual commands.)

## Tests
- Write tests for any new feature or bug fix.
- Make sure all tests pass locally before opening a PR.
- Aim for clarity and maintain existing patterns.

## Code style
- Follow the existing code style. Use the formatter and linter configured for this repository (Prettier/ESLint, gofmt, rustfmt, etc.).
- Keep commits atomic and focused.

## Commit messages
We recommend Conventional Commits:
- feat: add a new feature
- fix: fix a bug
- docs: documentation only changes
- chore: maintenance tasks
Include a short description and, if relevant, reference an issue number: `fix: correct off-by-one error (#123)`

## Pull request checklist
- [ ] The PR has a clear description of the change and motivation.
- [ ] Related issue(s) are linked.
- [ ] Tests added or existing tests updated.
- [ ] Linter/formatting checks pass.
- [ ] CI is green.

## Reporting security issues
If you find a security vulnerability, please do not open a public issue. Contact the maintainers privately (email: <maintainer-email>) or follow the project SECURITY policy.

## Communication
We use GitHub issues and pull requests for tracking work. For informal chat, link to your preferred channel (Discord/Slack/Matrix) if you have one.

## Additional resources
- CONTRIBUTING templates, PR templates, issue templates can be added in `.github/` to standardize contributions.
- Consider adding a `CODE_OF_CONDUCT.md` and `SECURITY.md` if the project doesn't already have them.
