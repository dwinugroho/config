# @dwinugroho/prettier-config

The prettier config for personal projects.

## Installation

Install the package via npm or yarn:

```bash
npm install -D @dwinugroho/prettier-config
# or
yarn add -D @dwinugroho/prettier-config
# or
pnpm add -D @dwinugroho/prettier-config
# or
bun install -D @dwinugroho/prettier-config
```

## Usage

To use this prettier config, just reference it in your `package.json` file:

```json
{
  "name": "my-project",
  "prettier": "@dwinugroho/prettier-config",
  "version": "1.0.0"
}
```

You can also reference it in your `.prettierrc.js` file:

```js
module.exports = "@dwinugroho/prettier-config";
```

## Configuration

This prettier config includes the following settings:

- `arrowParens`: Always include parentheses around a sole arrow function parameter.
- `singleQuote`: Use single quotes instead of double quotes.
- `jsxSingleQuote`: Use single quotes in JSX.
- `tabWidth`: Set the width of tabs to 2 spaces.
- `semi`: Do not include semicolons at the end of statements.
- `trailingComma`: No trailing commas will be added.
- `plugins`: Include the following plugins:
  - `prettier-plugin-sort-json`: Sort JSON files.
  - `prettier-plugin-tailwindcss`: Format Tailwind CSS classes [see more](https://github.com/tailwindlabs/prettier-plugin-tailwindcss).
  - `prettier-plugin-package-perfection`: Format package.json file.

You can modify these settings by creating your own `prettier.config.js` file and extending this config:

```js
module.exports = {
  ...require("@dwinugroho/prettier-config"),
  semi: true,
};
```

## License

This project is licensed under the [MIT License](LICENSE).
