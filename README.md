# viper-cli

Vite-based CLI to create your project easily and fastest.

## Feature

- ⚛️ Support React, Vue, Svelte
- 🖥 Typescript support
- 📖 Less boilerplate
- ⏰ Always up to date dependencies
- ⚙️ Choose your own tool / framework you need
  - Tailwind
  - Sass
  - Router (react-router-dom, vue-router, svelte-navigator)
  - ESLint
  - Prettier
  - Unit test (Vitest)

## Get started

```bash
npx viper
```

## Examples

Name your project

```bash
npx viper my-app
```

Generate your project in the current working directory

```bash
npx viper .
```

Specify a template: react, react-ts, vue, vue-ts, svelte, svelte-ts

```bash
npx viper --template react
```

Use yarn to install packages

```bash
npx viper --with-yarn
```