# 🎨 @dwinugroho/prettier-config

The enchanting Prettier configuration for personal projects. ✨

## 🛠️ Installation

Install the package via npm, yarn, pnpm, or even bun:

```bash
npm install -D @dwinugroho/prettier-config
# or
yarn add -D @dwinugroho/prettier-config
# or
pnpm add -D @dwinugroho/prettier-config
# or
bun install -D @dwinugroho/prettier-config
```

## 🚀 Usage

To infuse your project with Prettier magic, reference it in your `package.json` file:

```json
{
  "name": "my-project",
  "prettier": "@dwinugroho/prettier-config",
  "version": "1.0.0"
}
```

Or dance to your own rhythm in your `.prettierrc.js` file:

```js
module.exports = "@dwinugroho/prettier-config";
```

## ⚙️ Configuration

This Prettier config comes with a treasure trove of settings:

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

eel free to create your own Prettier symphony by extending this config in your `prettier.config.js`:

```js
module.exports = {
  ...require("@dwinugroho/prettier-config"),
  semi: true,
};
```

## 📜 License

Crafted under the spell of the [MIT License](LICENSE). May your code be ever beautiful! 🌈
