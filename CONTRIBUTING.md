# Contributing to Bronto open source

First off, thank you for taking the time to contribute! 🦕 Contributions of all
kinds are welcome across Bronto's open source projects — bug reports,
documentation, and code.

This is an organization-wide guide. Individual repositories may add their own
`CONTRIBUTING.md` with project-specific build and test instructions; when they
do, that file takes precedence for the details.

By participating in any Bronto project, you agree to abide by our
[Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to Contribute

- 🐛 **Report bugs** — open an issue using the bug report template.
- 💡 **Request features** — open an issue using the feature request template.
- 📖 **Improve documentation** — fixes to READMEs and docs are very welcome.
- 🔧 **Submit code** — see the workflow below.

For security issues, please **do not** open a public issue — see
[SECURITY.md](SECURITY.md).

## Development Setup

Each repository documents how to build, run, and test it in its `README.md`.
Please follow the instructions there for the project you are working on. In
general:

- Work in a feature branch off `main`.
- Use the language's standard tooling (e.g. a virtual environment for Python,
  `npm install` for Node.js, `terraform fmt`/`validate` for Terraform).
- Add or update tests for any behavior you change, and run the project's test
  suite before opening a pull request.

## Coding Standards

- Keep changes focused and consistent with the surrounding code style.
- Run the project's formatter/linter before committing.
- Do not commit secrets, credentials, or customer data.
- Keep documentation in sync with code changes.

## Commit Messages & Sign-off

- Write clear, descriptive commit messages.
- We use the [Developer Certificate of Origin](https://developercertificate.org/)
  (DCO). Sign off each commit to certify you wrote or have the right to submit
  the code:

  ```bash
  git commit -s -m "Your message"
  ```

  This appends a `Signed-off-by` line to your commit.

## Pull Request Process

1. Fork the repository and create your branch from `main`.
2. Make your change, including tests and documentation updates.
3. Ensure the project's tests and linters pass locally.
4. Open a pull request describing **what** changed and **why**.
5. A maintainer will review your PR; please be responsive to feedback.

## License

By contributing, you agree that your contributions will be licensed under the
license that covers the repository you are contributing to (see that
repository's `LICENSE` file).
