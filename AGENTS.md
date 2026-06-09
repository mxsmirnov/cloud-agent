# AGENTS.md

## Project overview

This repository (`mxsmirnov/cloud-agent`) is currently a **greenfield starter**: it contains only `README.md` with placeholder text. There is no application code, dependency manifests, tests, or service definitions yet.

## Cursor Cloud specific instructions

### Services

| Service | Required | Notes |
|---------|----------|-------|
| *(none)* | — | No runnable application or backend exists in this repo yet. |

When application code is added, update this section with how to start each service (dev server, API, workers, databases, etc.).

### Dependencies

There are **no project dependencies** to install. The VM update script is a no-op (`true`).

After adding a stack (for example `package.json`, `pyproject.toml`, or `go.mod`), replace the update script with the appropriate install command (`npm install`, `uv sync`, etc.) and document startup commands here.

### Lint / test / build / run

Not applicable until the project defines scripts or tooling. Check the root README and package manifests once they exist.

### VM tooling (available without repo setup)

The cloud VM includes: **git**, **Node.js** (via nvm, v22.x), **npm**, **pnpm**, **yarn**, and **Python 3.12** with **pip**. Docker is not installed by default.

### Git hooks

Only default Git sample hooks under `.git/hooks/`; no `.husky/` or `pre-commit` configuration in the repo.
