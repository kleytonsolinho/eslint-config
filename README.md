Kleyton Solinho ESLint config

Whats included this package?

Standard config base;
React plugin;
React Hooks plugin;
JSX a11y plugin;
Prettier;

Setup
Install the dependencies
npm i -D eslint @rocketseat/eslint-config

Create a .eslintrc.json file extending the config:
{
"extends": "@kleytonsolinho/config/eslint/react"
// "extends": "@kleytonsolinho/config/eslint/node"
}

Create a .prettierrc file extending the config:
{
"@kleytonsolinho/config/prettier"
}

You can also use a .eslintrc.js instead of JSON if you prefer.
