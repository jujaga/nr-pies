# NR Permitting Interoperability Exchange Specification

test change

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Lifecycle:Experimental](https://img.shields.io/badge/Lifecycle-Experimental-339999)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md)

An easy as pie way to exchange standardized permitting information. 🥧

This website is built using [Docusaurus](https://docusaurus.io/), a modern
static website generator.

## Directory Structure

```txt
.github/                   - PR, Issue templates
.vscode/                   - VSCode environment configurations
blog/                      - Blog Content Root
docs/                      - Docs Content Root
├── docusaurus/            - Docusaurus Tutorials
├── introduction/          - PIES General Information
├── specification/         - PIES Technical Specification
│   ├── data-types/        - PIES Data Types
│   └── schemas/           - PIES Schema Documentation
├── schemas/               - Raw PIES JSON Schema Definitions
├── src/                   - Docusaurus Source Code
└── static/                - Site Static Assets
CODE-OF-CONDUCT.md         - Code of Conduct
COMPLIANCE.yaml            - BCGov PIA/STRA compliance status
CONTRIBUTING.md            - Contributing Guidelines
Dockerfile                 - Dockerfile Image definition
LICENSE                    - License
SECURITY.md                - Security Policy and Reporting
```

## Installation Guide

### Install

```sh
npm ci
```

### Run Local Development

```sh
npm run start
```

This command starts a local development server and opens up a browser window.
Most changes are reflected live without having to restart the server.

### Static Build

```sh
npm run build
```

This command generates static content into the `build` directory and can be
served using any static contents hosting service.

### Deployment

Using SSH:

```sh
USE_SSH=true npm run deploy
```

Not using SSH:

```sh
GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to
build the website and push to the `gh-pages` branch.

## Getting Help or Reporting an Issue

To report bugs/issues/features requests, please file an
[issue](https://github.com/bcgov/nr-permitconnect-navigator-service/issues).

## How to Contribute

If you would like to contribute, please see our [contributing](CONTRIBUTING.md)
guidelines.

Please note that this project is released with a
[Contributor Code of Conduct](CODE-OF-CONDUCT.md). By participating in this
project you agree to abide by its terms.

## License

```txt
Copyright 2024 Province of British Columbia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
