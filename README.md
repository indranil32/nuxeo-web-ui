[![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=master/addons_nuxeo-web-ui-master)](https://qa.nuxeo.org/jenkins/job/master/job/addons_nuxeo-web-ui-master/)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5d8cd2a3c56745ecaae7e7f92a683ea7)](https://www.codacy.com/app/Nuxeo/nuxeo-web-ui)


## Getting Started

### Install dependencies

```sh
npm install
```

### Development workflow

#### Serve / watch

```sh
npm start
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

#### Linting & Code Formatting

```sh
npm run lint
```

To lint your files and check for formatting, using [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) and [Polymer Lint](https://polymer-library.polymer-project.org/3.0/docs/tools/polymer-cli-commands#lint).

```sh
npm run format
```

To automatically fix problems and format the code.

#### Build & Vulcanize

```sh
npm run build
```

Build and optimize the current project, ready for deployment, using webpack.

## License

(C) Copyright NewRem Media Corp. (https://newrem.ai/)

All images, icons, fonts, and videos contained in this folder are copyrighted by NewRem Media Corp., all rights reserved.

## About innoDAM

innoDAM dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the innoDAM Platform and Products provide clear business value.
