# eslint-config-carloluis

> My shared ESLint Configuration for JS Projects

## Installation

```bash
yarn add git+ssh://git@github.com/carloluis/eslint-config-carloluis.git eslint-plugin-prettier@3.1.2 --dev
```

## Usage

Reference the `eslint-config-carloluis` in the extends section of your [ESLint config](https://eslint.org/docs/user-guide/configuring).

```js
module.exports = {
  extends: ['carloluis'],
  rules: {
    // Additional rules here...
  }
};
```

### Prettier

Reference the `prettier.config` in your [Prettier config](https://prettier.io/docs/en/configuration.html)

```json
"eslint-config-carloluis/prettier.config"
```
