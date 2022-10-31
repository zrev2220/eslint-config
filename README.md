# `@zrev2220/eslint-config`

![npm (scoped)](https://img.shields.io/npm/v/@zrev2220/eslint-config)

My personal ESLint config.

Works for JavaScript or TypeScript projects, with or without React.

## Usage

Install:

```bash
npm install --save-dev eslint @zrev2220/eslint-config eslint-config-prettier standard
```

Create/edit `.eslintrc`:

```jsonc
{
  "extends": "@zrev2220/eslint-config" // or just "@zrev2220" also works
}
```

Lint your code:

```bash
npx eslint --ignore-path .gitignore --max-warnings 0 "**/*.{js,jsx,ts,tsx}"
```

See also [Using a Shareable Config](https://eslint.org/docs/developer-guide/shareable-configs#using-a-shareable-config).
