# eslint-config

[![Build Status](https://travis-ci.org/dcrtantuco/eslint-config.svg?branch=master)](https://travis-ci.org/dcrtantuco/eslint-config)

My personal eslint config

## Dependencies

- eslint-config-prettier

## Extends

- eslint:recommended

## Installation

### npm

```
npm install eslint @dcrtantuco/eslint-config --save-dev
```

### yarn

```
yarn add eslint @dcrtantuco/eslint-config --dev
```

## Usage

Update `.eslintrc.js`

```js
// .eslintrc.js
module.exports = {
  extends: ['@dcrtantuco/stylelint-config']
}
```

Or add eslint config in `package.json`

```json
{
  "eslintConfig": { "extends": ["@dcrtantuco/eslint-config"] },
  "scripts": {
    "lint:js": "eslint 'js/**/*.js'"
  }
}
```

## License

MIT
