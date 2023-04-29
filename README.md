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
npm i -D eslint @kleytonsolinho/eslint-config
```

Create a .eslintrc.json file extending the config to react:

```bash
{
  "extends": "@kleytonsolinho/config/eslint/react"
}
```

Or extending the config to node:

```bash
{
  "extends": "@kleytonsolinho/config/eslint/node"
}
```

Add on package.json file the config:

```bash
{
  "prettier": "@kleytonsolinho/config/prettier"
}

```

You can also use a .eslintrc.js instead of JSON if you prefer.
