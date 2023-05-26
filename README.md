## 📦 Kleyton Solinho ESLint config

### Whats included this package?

1. Standard config base;
2. React plugin;
3. React Hooks plugin;
4. JSX a11y plugin;
5. Prettier;

### 👨🏻‍💻 Setup

Install the dependencies

```bash
npm i eslint @kleytonsolinho/eslint-config -D
```

Create a .eslintrc.json file extending the config to react:

```bash
{
  "extends": "@kleytonsolinho/eslint-config/react"
}
```

Or extending the config to node:

```bash
{
  "extends": "@kleytonsolinho/eslint-config/node"
}
```

Create a .prettierrc.js file extending the config:

```bash
module.exports = require('@kleytonsolinho/eslint-config/prettier');

```

You can also use a .eslintrc.js instead of JSON if you prefer.
