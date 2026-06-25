# Contributing

Thanks for your interest in contributing to an Imajeure open-source project! This guide applies to every repository in the [@imajeure](https://github.com/imajeure) organization unless a repo provides its own `CONTRIBUTING.md`.

## Reporting issues

- Please search [existing issues](../../issues) first.
- Use the issue templates (bug report / feature request) where they apply.
- For **security vulnerabilities**, do **not** open a public issue — see [SECURITY.md](SECURITY.md).

## Submitting changes

1. Fork the repository and create a branch from `main`.
2. Keep your change focused — one logical change per pull request.
3. Add or update tests. Our projects use the Node.js native test runner: `npm test`.
4. Make sure CI is green and the code follows the existing style (ESM, and no new runtime dependencies without a clear justification).
5. Open a pull request using the template, describing **what** changed and **why**.

Clear, conventional commit messages (`fix:`, `feat:`, `docs:`, `chore:`) are appreciated — they help us generate changelogs.

## Code of Conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold it.

## License

Unless stated otherwise, these projects are licensed under Apache-2.0. By contributing, you agree that your contributions are licensed under the same terms.
