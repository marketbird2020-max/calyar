# calyar

Initial project scaffold for calyar.

## Status

The project type, language, and framework have not yet been selected. This repository provides a small, framework-neutral foundation; it does not contain a runnable application yet.

## Repository structure

| Path | Purpose |
| --- | --- |
| `src/` | Application or library source code |
| `tests/` | Automated tests and test fixtures |
| `docs/` | Requirements, architecture, and setup documentation |
| `.editorconfig` | Shared text formatting defaults |
| `.gitattributes` | Consistent text line endings |
| `.gitignore` | Local environment files and temporary files |

Folder placeholders can be removed once real files are added.

## Getting started

```sh
git clone https://github.com/marketbird2020-max/calyar.git
cd calyar
```

No dependency installation, build, or run command is available yet. See [Project setup](docs/project-setup.md) for the decisions needed before adding language-specific configuration.

## Development

- Keep source code in `src/` and tests in `tests/`, unless the selected framework requires another layout.
- Document setup steps and architectural decisions in `docs/`.
- Keep credentials and local environment files out of Git. Add a sanitized `.env.example` only when environment variables are needed.
- Add meaningful tests with the first implementation and document how to run them.
