# CI/CD Quiz Coursework

**Coursework for school**

![Coursework](https://img.shields.io/badge/Coursework-blue)

Coursework exploring quiz functionality, Cypress component tests, and deployment pipeline examples. Related quiz work is in [TECH-QUIZ](https://github.com/treeewzrd/TECH-QUIZ).

**Built with:** React, TypeScript, Express, MongoDB, Cypress.

## What I built

- Built a React quiz connected to an Express and MongoDB question API.
- Added Cypress component tests, fixtures, and test configuration.
- Worked on CI/CD examples for test and deployment workflows; the current files remain under github-sample.

## Explore the source

- [client/src/components/Quiz.tsx](client/src/components/Quiz.tsx) — Quiz interface.
- [cypress/component/Quiz.cy.jsx](cypress/component/Quiz.cy.jsx) — Component tests.
- [github-sample/dev.workflow.yml](github-sample/dev.workflow.yml) — Example test workflow.
- [github-sample/main.workflow.yml](github-sample/main.workflow.yml) — Example deployment workflow.

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
