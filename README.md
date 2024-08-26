<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

# Sleepr Microservice

A **microservice** built with the [NestJS](https://nestjs.com/) framework, designed for efficiency, scalability, and modularity. This microservice, named **Sleepr**, is part of a larger application architecture.

## Features

- **Efficient Architecture**: Built on the progressive Node.js framework, NestJS.
- **Modular Design**: Easily extensible and maintainable.
- **Integrated with MongoDB**: Utilizes Mongoose for seamless database interactions.
- **Logging with Pino**: Fast and structured logging for production environments.

## Technologies Used

- **NestJS**: A progressive Node.js framework for building efficient and scalable server-side applications.
- **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
- **MongoDB**: A NoSQL database for storing and retrieving data, integrated using Mongoose.
- **Mongoose**: An elegant MongoDB object modeling tool designed to work in an asynchronous environment.
- **Joi**: A powerful schema description language and data validator for JavaScript.
- **RxJS**: A library for reactive programming using Observables, to make it easier to compose asynchronous or callback-based code.
- **Pino**: A fast, low-overhead logging library, with Pino-HTTP and Pino-Pretty for enhanced logging capabilities.
- **ESLint**: A pluggable and configurable linter tool for identifying and reporting on patterns in JavaScript and TypeScript.
- **Prettier**: An opinionated code formatter to ensure consistent code style.
- **Jest**: A delightful JavaScript testing framework with a focus on simplicity.
- **Docker**: A platform to develop, ship, and run applications inside containers, used here for e2e testing.
- **Rimraf**: A deep deletion module for Node, used to clean up the build directory.
- **Express**: A minimal and flexible Node.js web application framework, providing a robust set of features for web and mobile applications.
- **Cookie-Parser**: Middleware to parse cookies attached to client requests.
- **Source-Map-Support**: Provides source map support for stack traces in node.js.

## Installation

````bash
$ npm install

## Installation

```bash
$ npm install
````

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
