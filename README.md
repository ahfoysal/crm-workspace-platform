# CRM Workspace Platform

A CRM and business workspace platform snapshot with frontend, server, packages, docs, and app extensions.

## Features

- CRM workspace modules
- Server and frontend packages
- Extension/app package structure
- Docker-oriented self-hosting assets
- Documentation and product notes

## Tech stack

- TypeScript
- React
- NestJS
- Yarn workspaces
- Nx
- PostgreSQL

## Screenshots

Screenshots are not included in this repository snapshot. Run the app locally and add current product screenshots when a deployment is available.

## Installation

Use the package manager indicated by the lockfile in this repository. Install from the repository root before running app-specific commands.

## Environment variables

Create local environment files from the example files included in the repository, or start from this root example:

| Variable | Purpose |
| --- | --- |
| `PG_DATABASE_URL` | Configure for the local or deployed environment. |
| `SERVER_URL` | Configure for the local or deployed environment. |
| `FRONT_BASE_URL` | Configure for the local or deployed environment. |
| `ACCESS_TOKEN_SECRET` | Configure for the local or deployed environment. |
| `LOGIN_TOKEN_SECRET` | Configure for the local or deployed environment. |
| `REFRESH_TOKEN_SECRET` | Configure for the local or deployed environment. |

## Development commands

```bash
yarn install
```
```bash
yarn start
```
```bash
yarn docs:generate
```
```bash
yarn docs:generate-paths
```

## Build and deploy notes

- Review the included Docker, compose, or package-specific deployment files before production use.
- Keep secrets outside git and provide them through the deployment platform or local untracked environment files.
- For large workspace builds, run package-specific checks first, then the root build command.

## Project structure

- `.yarn/` — project directory
- `LICENSE`
- `NOTICE.md`
- `package.json`
- `packages/` — project directory

## Verification status

This public snapshot was prepared with dependency directories, generated output, local editor settings, and private environment files removed. See `PUBLISHING_REPORT.md` for the exact safety and verification checks run before publication.

## License

AGPL-3.0. Preserve the included license and notice files when redistributing.

## Author

gotowebevents <info@gotowebevents.com>
