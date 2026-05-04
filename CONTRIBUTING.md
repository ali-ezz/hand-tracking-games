# Contributing to Hand Tracking Games

Thank you for contributing. This project welcomes bug reports, feature requests, and pull requests.

## How to contribute

1. Search existing issues before opening a new one.
2. Use the provided issue templates for bug reports or feature requests.
3. Open a pull request with a clear description of your changes.

## Branch naming

Use descriptive branch names such as:

- `feature/add-new-game-mode`
- `bugfix/fix-leaderboard-storage`
- `docs/update-readme`

## Pull request expectations

- Include a summary of what changed and why.
- Reference the related issue if one exists.
- Add testing notes or steps for verification.
- Keep changes focused and reviewable.

## Review process

Pull requests will be reviewed by the maintainers. Feedback may include requests for clarifications, additional tests, or smaller incremental changes.

## Local testing

Run a local static server from the project root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Code style

- Keep HTML, CSS, and JavaScript readable and consistent with the existing project style.
- Prefer clear variable names and small helper functions.

## Reporting security issues

If you discover a security vulnerability, do not open a public issue. Follow the guidance in [SECURITY.md](SECURITY.md).
