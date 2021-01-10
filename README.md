# eslint-config

![Node.js CI](https://github.com/darwintantuco/eslint-config/workflows/Node.js%20CI/badge.svg)

My personal eslint config

## Peer Dependencies

- typescript
- eslint
- @typescript-eslint/parser
- @typescript-eslint/eslint-plugin
- eslint-plugin-react
- eslint-plugin-jsx-a11y
- eslint-config-prettier

## Installation

### npm

```
npm install @darwintantuco/eslint-config typescript eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-react eslint-plugin-jsx-a11y eslint-config-prettier --save-dev
```

### yarn

```
$ yarn add @darwintantuco/eslint-config typescript eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-react eslint-plugin-jsx-a11y eslint-config-prettier --dev
```

## Usage

Update `.eslintrc.js`

```js
// .eslintrc.js
module.exports = {
  extends: ["@darwintantuco/eslint-config"],
};
```

Or add eslint config in `package.json`

```json
{
  "eslintConfig": { "extends": ["@darwintantuco/eslint-config"] },
  "scripts": {
    "lint:js": "eslint 'js/**/*.{js,jsx,ts,tsx}'"
  }
}
```

## License

MIT
