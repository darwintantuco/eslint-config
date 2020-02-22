# eslint-config

[![Build Status](https://travis-ci.org/darwintantuco/eslint-config.svg?branch=master)](https://travis-ci.org/darwintantuco/eslint-config)

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
npm install eslint eslint-plugin-react eslint-plugin-jsx-a11y @darwintantuco/eslint-config --save-dev
```

### yarn

```
yarn add eslint eslint-plugin-react eslint-plugin-jsx-a11y @darwintantuco/eslint-config --dev
```

## Usage

Update `.eslintrc.js`

```js
// .eslintrc.js
module.exports = {
  extends: ['@darwintantuco/eslint-config']
}
```

Or add eslint config in `package.json`

```json
{
  "eslintConfig": { "extends": ["@darwintantuco/eslint-config"] },
  "scripts": {
    "lint:js": "eslint 'js/**/*.js'"
  }
}
```

## License

MIT
