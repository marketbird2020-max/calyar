# Project setup

## Decisions pending

The initial repository contained only an empty root `.gitkeep`. No source files, dependency manifests, branches, or issues established a project type.

Before adding runtime configuration, define:

1. Project type and purpose (for example, website, web application, API, mobile app, or library).
2. Language and framework, chosen to fit that purpose.
3. Supported runtime version and dependency manager.
4. Development, build, and test commands.
5. Hosting or distribution target, when relevant.

## After selecting the project type

- Adjust the source and test layout to the chosen tooling.
- Add the minimum dependency manifest and appropriate lockfile.
- Extend `.gitignore` for generated outputs and dependency directories.
- Document prerequisites and exact install, run, build, and test commands in the README.
- Add a sample environment file only if required; include placeholders rather than secrets.
- Add CI once there is a meaningful build or test command to execute.
