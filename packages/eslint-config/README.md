# @dwinugroho/eslint-config

The ESLint configuration for dwinugroho projects.

## Installation

Install the package via npm or yarn:

```bash
npm install -D @dwinugroho/eslint-config
# or
yarn add -D @dwinugroho/eslint-config
# or
pnpm add -D @dwinugroho/eslint-config
# or
bun install -D @dwinugroho/eslint-config
```

## Usage

Extend the configuration in your ESLint configuration file:

```js
module.exports = {
  extends: ["@dwinugroho/eslint-config"],
};
```

## Configuration

The configuration includes the following plugins and extends:

- eslint:recommended
- plugin:react/recommended
- plugin:jsx-a11y/strict
- plugin:@typescript-eslint/strict
- plugin:@typescript-eslint/recommended
- plugin:@typescript-eslint/recommended-requiring-type-checking
- plugin:@typescript-eslint/eslint-recommended
- plugin:@typescript-eslint/stylistic
- plugin:security/recommended
- plugin:prettier/recommended
- plugin:tailwindcss/recommended
- plugin:sonarjs/recommended
- plugin:unicorn/recommended
- simple-import-sort
- unused-imports

## License

This project is licensed under the [MIT License](LICENSE).
