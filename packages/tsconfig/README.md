# @dwinugroho/tsconfig

The TypeScript config for personal projects.

## Installation

Install the package via npm or yarn:

```bash
npm install -D @dwinugroho/tsconfig
# or
yarn add -D @dwinugroho/tsconfig
# or
pnpm add -D @dwinugroho/tsconfig
# or
bun install -D @dwinugroho/tsconfig
```

## Configurations

The `@dwinugroho/tsconfig` package provides two distinct configuration files: `base.json` for basic TypeScript projects and `web.json` for TypeScript projects related to websites.

### Basic TypeScript Project Configuration (`base.json`)

To configure a basic TypeScript project, create a `tsconfig.json` file in the root directory of your project and extend `base.json`:

```json
{
  "extends": "@dwinugroho/tsconfig/base.json"
}
```

This configuration is optimized for standard TypeScript projects, covering essential compiler options and settings.

### Web TypeScript Project Configuration (`web.json`)

For TypeScript projects related to websites, use the `web.json` configuration. Create a `tsconfig.json` file in your website project's root directory and extend `web.json`:

```json
{
  "extends": "@dwinugroho/tsconfig/web.json"
}
```

The `web.json` configuration extends the `base.json` configuration and adds settings specific to web development, such as JSX preservation and necessary libraries.

## License

This project is licensed under the [MIT License](LICENSE).
