# fin-client

> Universal HTTP client for [Fin](https://functional-income.com).

[![NPM](https://img.shields.io/npm/v/fin-client.svg)](https://www.npmjs.com/package/fin-client) [![Build Status](https://travis-ci.com/functional-incomee/fin.svg?branch=master)](https://travis-ci.com/functional-incomee/fin) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install fin-client
```

## Usage

```js
const FinClient = require('fin-client')
const client = new FinClient()

const username = 'example'
const password = 'password'

await client.signin({ username, password })
```

## Related

- [fin](https://functional-income.com) - Fin is the easiest way to launch your own SaaS.
- [fts](https://github.com/transitive-bullshit/functional-typescript) - TypeScript standard for rock solid serverless functions.

## License

MIT © [Travis Fischer](https://transitivebullsh.it)
