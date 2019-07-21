# eslint-config

[![Build Status](https://travis-ci.org/dcrtantuco/eslint-config.svg?branch=master)](https://travis-ci.org/dcrtantuco/eslint-config)

My personal eslint config

## Dependencies

- eslint-plugin-react
- eslint-plugin-jsx-a11y

## Extends

- eslint:recommended
- plugin:react/recommended
- plugin:jsx-a11y/recommended
- prettier

## Installation

### npm

```
npm install eslint eslint-plugin-react eslint-plugin-jsx-a11y @dcrtantuco/eslint-config --save-dev
```

### yarn

```
yarn add eslint eslint-plugin-react eslint-plugin-jsx-a11y @dcrtantuco/eslint-config --dev
```

## Usage

Update `.eslintrc.js`

```js
// .eslintrc.js
module.exports = {
  extends: ['@dcrtantuco/eslint-config']
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
