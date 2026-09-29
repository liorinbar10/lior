# Lior Inbar

[![CI](https://github.com/liorinbar10/lior/actions/workflows/ci.yml/badge.svg)](https://github.com/liorinbar10/lior/actions/workflows/ci.yml)

Personal repository for standalone projects, small experiments and written notes.

## Layout

Each project or experiment lives in its own top-level directory with a README that says what it is, what state it is in and how to use it. Notes are Markdown files, kept next to the work they describe or in a directory of their own when they stand alone. Project-specific dependencies, tooling and ignore rules stay inside the project directory, and the repository root holds only configuration and policy shared by everything.

| File | Purpose |
| --- | --- |
| [LICENSE](LICENSE) | MIT License covering everything in the repository |
| [SECURITY.md](SECURITY.md) | How to report a vulnerability privately |
| [.editorconfig](.editorconfig) | Editor settings: UTF-8, LF, two-space indentation, final newline |
| [.gitattributes](.gitattributes) | Line-ending normalization to LF at the git level |
| [.gitignore](.gitignore) | Ignore rules for operating-system, editor, local-environment and temporary files |
| [.markdownlint-cli2.jsonc](.markdownlint-cli2.jsonc) | Markdown lint rules, globs and ignores, shared by CI and local runs |
| [.github/workflows/ci.yml](.github/workflows/ci.yml) | CI workflow: lints Markdown on every push and pull request |
| [.github/dependabot.yml](.github/dependabot.yml) | Keeps the GitHub Actions used by CI current |

## Conventions

- Everything is written in English.
- Markdown is linted with markdownlint-cli2; `npx markdownlint-cli2` runs the same check locally.
- Commits are small and focused, with subject lines in the imperative mood.

## Contributing

This is a personal repository and is not looking for contributors. Corrections and questions are welcome as [issues](https://github.com/liorinbar10/lior/issues), and small fixes as pull requests. Security concerns go through [SECURITY.md](SECURITY.md), never through a public issue or pull request.

## License

This repository is released under the MIT License. Copyright (c) 2026 Lior Inbar. See [LICENSE](LICENSE) for the full text.
