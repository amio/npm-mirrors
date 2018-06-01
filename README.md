# npm-mirrors [![][npm-badge]][npm-link]

[![Greenkeeper badge](https://badges.greenkeeper.io/amio/npm-mirrors.svg)](https://greenkeeper.io/)

A list for npm registry mirrors.

## Install

```
npm install npm-mirrors
```

## Usage

```javascript
const mirrors = require('npm-mirrors')

console.log(mirrors)
// {
//   'npm': {
//     'home': 'https://www.npmjs.org',
//     'registry': 'https://registry.npmjs.org/'
//    },
//    ...
// }
```

[npm-badge]: https://img.shields.io/npm/v/npm-mirrors.svg
[npm-link]: https://www.npmjs.com/package/npm-mirrors
