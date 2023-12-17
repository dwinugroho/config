# 📘 [@dwinugroho/tsconfig](./packages/tsconfig)

The TypeScript wizardry for personal projects! 🚀

## 🛠️ Installation

Install the package via npm, yarn, pnpm, or even bun:

```bash
npm install -D @dwinugroho/tsconfig
# or
yarn add -D @dwinugroho/tsconfig
# or
pnpm add -D @dwinugroho/tsconfig
# or
bun install -D @dwinugroho/tsconfig
```

## 🚀 Configurations

The `@dwinugroho/tsconfig` package unveils two mystical configuration files: `base.json` for fundamental TypeScript projects and `web.json` for TypeScript projects entwined with the web.

### 🌟 Basic TypeScript Project Configuration(`base.json`)

To weave the spell of basic TypeScript, create a `tsconfig.json` file in your project's root directory and extend `base.json`:

```json
{
  "extends": "@dwinugroho/tsconfig/base.json"
}
```

This incantation caters to standard TypeScript projects, embracing essential compiler options and settings.

### 🕸️ Web TypeScript Project Configuration (`web.json`)

For TypeScript projects dancing with websites, embrace the `web.json` configuration. In your website project's root, create a `tsconfig.json` file and extend `web.json`:

```json
{
  "extends": "@dwinugroho/tsconfig/web.json"
}
```

`web.json` extends the magic of `base.json` and adds web-specific settings, such as JSX preservation and necessary libraries.

## 📜 License

Crafted under the enchantment of the [MIT License](LICENSE). May your TypeScript adventures be spellbinding! 🌟
