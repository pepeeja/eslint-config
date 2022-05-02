# @pepeeja/eslint-config


[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/pepeeja/eslint-config/blob/main/LICENSE) [![npm latest package](https://img.shields.io/npm/v/@pepeeja/eslint-config/latest.svg)](https://www.npmjs.com/package/@pepeeja/eslint-config) 

ESLint and Prettier setup for React and Node.js projects

## Install

```shell
// with npm
npm install @pepeeja/eslint-config

// with yarn
yarn add @pepeeja/eslint-config
```
## Usage

This package contains two configurations one for ESLint and Prettier.

Prettier could be configured by creating `.prettierrc` file in the root directory of your project with the following content:

```json
"@pepeeja/eslint-config/prettier"
```

ESLint configuration has several options based on used environment. You can find list of available configurations below.

### Standard

Create `.eslintrc` file in the root directory of your project with the following content:

```json
{
  "extends": "@pepeeja/eslint-config"
}
```

### React

To apply React specific rules there is additional configuration which is inherited from standard one.
Create `.eslintrc` file in the root directory of your project with the following content:

```json
{
  "extends": "@pepeeja/eslint-config/react"
}
```

### Node

To apply Node.js specific rules there is additional configuration which is inherited from standard one.
Create `.eslintrc` file in the root directory of your project with the following content:

```json
{
  "extends": "@pepeeja/eslint-config/node"
}
```

## License

This project is licensed under the terms of the [MIT License](LICENSE)