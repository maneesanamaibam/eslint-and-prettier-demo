### Requirements

1. Install prettier
2. Configure .prettierrc file
3. Install prettier VS Code Extension
4. How to resolve conflicts between eslint rules and prettier rules

### Install eslint-config-prettier eslint-plugin-prettier

```
npm i --save-dev eslint-config-prettier eslint-plugin-prettier

```

### Basic Prettier configuration

```json
{
  "$schema": "https://json.schemastore.org/prettierrc",
  "semi": true,
  "tabWidth": 2,
  "singleQuote": true,
  "printWidth": 100,
  "arrowParens": "avoid",
  "trailingComma": "none",
  "endOfLine": "auto"
}
```

## Conflicting code example

```js
'use strict';
const hello = message => {
  return `hello ${message}`;
};
```
