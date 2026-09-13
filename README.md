# clx_hls.js

> HLS.js is a JavaScript library that plays HLS in browsers with support for MSE.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**clx_hls.js** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

HLS.js is a JavaScript library that plays HLS in browsers with support for MSE.

**Topics / Tags:** _None_

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | Unknown |
| **Package Manager** | — |

### Dependencies

**Dev Dependencies:**
- `@babel/core`
- `@babel/helper-module-imports`
- `@babel/plugin-proposal-class-properties`
- `@babel/plugin-proposal-object-rest-spread`
- `@babel/plugin-proposal-optional-chaining`
- `@babel/plugin-transform-object-assign`
- `@babel/preset-env`
- `@babel/preset-typescript`
- `@babel/register`
- `@itsjamie/esdoc-cli`


---

## Repository Structure

```
clx_hls.js/
├── .editorconfig
├── .esdoc.json
├── .eslintrc.js
├── .github/
│   ├── ISSUE_TEMPLATE
│   ├── PULL_REQUEST_TEMPLATE.md
│   ├── release-drafter.yml
│   ├── stale.yml
│   ├── workflows
├── .gitignore
├── .husky
├── .mversionrc
├── .prettierignore
├── .prettierrc
├── .vscode
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── MIGRATING.md
├── README.md
├── api-extractor/
│   ├── .gitignore
│   ├── report
├── api-extractor.json
├── demo/
│   ├── basic-usage.html
│   ├── benchmark.html
│   ├── canvas.js
│   ├── chart
│   ├── demo-utils.js
├── docs/
│   ├── API.md
│   ├── design.md
│   ├── logo.svg
│   ├── media-zigzagging.png
│   ├── release-process.md
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `CODE_OF_CONDUCT.md` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
git clone git@github.com:unacademy/clx_hls.js.git
cd clx_hls.js
# Follow language-specific setup
```

### Available Scripts

```bash
# build
npm run build   # webpack --progress && npm run build:types

# build:ci
npm run build:ci   # webpack && tsc --build tsconfig-lib.json && api-extractor run

# build:debug
npm run build:debug   # webpack --progress --env debug --env demo

# build:watch
npm run build:watch   # webpack --progress --env debug --env demo --watch

# build:types
npm run build:types   # tsc --build tsconfig-lib.json && api-extractor run --local

# dev
npm run dev   # webpack serve --progress --env debug --env demo --port 8000 --static .

# docs
npm run docs   # esdoc

# lint
npm run lint   # eslint src/ tests/ --ext .js --ext .ts

# lint:fix
npm run lint:fix   # npm run lint -- --fix

# lint:quiet
npm run lint:quiet   # npm run lint -- --quiet

```


---

## Running the Application

```bash
npm run start   # npm run dev
```

---

## Infrastructure & CI/CD

- CI/CD pipeline configured (`.github/workflows` or equivalent)
- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> [![npm](https://img.shields.io/npm/v/hls.js.svg?style=flat)](https://npmjs.org/package/hls.js)
[![npm](https://img.shields.io/npm/v/hls.js/canary.svg?style=flat)](https://www.npmjs.com/package/hls.js/v/canary)
[![](https://data.jsdelivr.com/v1/package/npm/hls.js/badge?style=rounded)](https://www.jsdelivr.com/package/npm/hls.js)
[![Sauce Test Status](https://saucelabs.com/buildstatus/robwalch)](https://app.saucelabs.com/u/robwalch)

[comment]: <> ([![Sauce Test Status]&#40;https://saucelabs.com/browser-matrix/robwalch.svg&#41;]&#40;https://saucelabs.com/u/robwalch&#41;)

# ![HLS.js](./docs/logo

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
