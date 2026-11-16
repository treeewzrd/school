# CI/CD Quiz Coursework

![Status](https://img.shields.io/badge/status-coursework-blue)

Coursework exploring quiz functionality, Cypress component tests, and deployment pipeline examples. Related quiz work is in [TECH-QUIZ](https://github.com/treeewzrd/TECH-QUIZ).

**Built with:** React, TypeScript, Express, MongoDB, Cypress.

## Run locally

Requires Node.js/npm and MongoDB. From the repository root:

```bash
npm install
```

Set `MONGODB_URI` privately in `server/.env`, or use the local fallback database `techquiz`. Build before the backend watcher starts:

```bash
npm run build
npm run develop
```

Optional `npm run seed` replaces question data; use a disposable database. Rebuild the server after source changes.

## Tests and workflow examples

`npm run test-component` runs Cypress component tests; `npm run test-gui` opens Cypress. Files in `github-sample/` are examples, not active GitHub Actions workflows.

Original curriculum notice: © 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.

Setup instructions were checked against source; builds and application behavior have not been rerun during this cleanup.
