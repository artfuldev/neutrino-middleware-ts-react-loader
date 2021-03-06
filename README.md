# Neutrino React Hot TypeScript Loader Middleware
[![NPM version][npm-image]][npm-url] [![NPM downloads][npm-downloads]][npm-url]

`neutrino-middleware-ts-react-loader` is Neutrino middleware for hot module replacement for react with typescript.

## Requirements

- Node.js v6.9+
- Yarn or npm client
- Neutrino v5

## Installation

`neutrino-middleware-ts-react-loader` can be installed via the Yarn or npm clients.

#### Yarn

```bash
❯ yarn add neutrino-middleware-ts-react-loader
```

#### npm

```bash
❯ npm install --save neutrino-middleware-ts-react-loader
```

## Usage

`neutrino-middleware-ts-react-loader` can be consumed from the Neutrino API, middleware, or presets. Require this package
and plug it into Neutrino:

```js
const typescript = require('neutrino-middleware-ts-react-loader');

neutrino.use(typescript);
```

## Customization

`neutrino-middleware-ts-react-loader` creates some conventions to make overriding the configuration easier once you are
ready to make changes.

### Rules

The following is a list of rules and their identifiers which can be overridden:

- `typescript`: Allows react hot module replacement with typescript. Contains two loaders named `react` and  `ts` which use `react-hot-loader` and `ts-loader` respectively.

[npm-image]: https://img.shields.io/npm/v/neutrino-middleware-ts-react-loader.svg
[npm-downloads]: https://img.shields.io/npm/dt/neutrino-middleware-ts-react-loader.svg
[npm-url]: https://npmjs.org/package/neutrino-middleware-ts-react-loader


