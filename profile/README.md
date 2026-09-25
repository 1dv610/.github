# 1DV610 — CLI Template Collection

Boilerplate templates used in the **1DV610** course at Linnaeus University. Each
repository is a clean, pre-configured starting point for a CLI assignment — pick
the one matching your assignment's language, click **Use this template**, and
follow that repository's own README for setup.

## Templates

| Repository | Stack | Description |
| --- | --- | --- |
| [java-gradle-cli-template](https://github.com/1dv610/java-gradle-cli-template) | Java (Gradle) | Gradle application-plugin CLI boilerplate with JUnit 5, Checkstyle, and PMD. |
| [js-cli-template](https://github.com/1dv610/js-cli-template) | JavaScript (ESM) | Node.js CLI boilerplate with Vitest, ESLint + `@lnu/eslint-config`, Prettier. |
| [ts-cli-template](https://github.com/1dv610/ts-cli-template) | TypeScript (strict) | Node.js CLI boilerplate with `tsx`, Vitest, ESLint + `@lnu/eslint-config`, Prettier. |

## Getting started

1. Open the template repository for your assignment's stack.
2. Click **Use this template → Create a new repository** (or follow the
   alternative import flow documented in that repository's README if you're
   working from an existing/empty repository, e.g. one provisioned by GitHub
   Classroom).
3. Follow the **Getting Started** section in that repository's own README.

## Conventions across templates

- **License:** All templates are released under the **Unlicense** (public domain).
- **Node-based templates:** `engines.node` is kept in sync across the JS and TS
  templates, so switching between assignments doesn't require switching Node
  versions.
- **CI:** Every template runs its full quality gate (lint/static analysis and tests,
  plus format-check where applicable) on push/PR via GitHub Actions.

## Live coding example: Ripe Tomato

[ripe-tomato](https://github.com/1dv610/ripe-tomato) is the live coding example
used in the lectures — a small [p5.js](https://p5js.org/) game built step by step
with Vite, Vitest, ESLint, Stylelint, and Prettier. It is not a template: `main`
evolves as the lectures progress, and each stage is preserved in a
[tag](https://github.com/1dv610/ripe-tomato/tags) you can start from:

- `start-here` / `session-0` — the initial scaffold, before any session.
- `session-N` — the state of the project at the end of session *N*.

```sh
git clone https://github.com/1dv610/ripe-tomato.git
cd ripe-tomato
git checkout -b my-branch session-1   # or start-here, session-2, …
```

See the repository's README (in Swedish) for setup and commands.

## Questions

Open an issue in the relevant repository, or reach out to the course staff.
