# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

Kjør følgende i terminal og husk å laste nede pnpm og nodejs på pcen
- pnpm i
- pnpm run dev



Install dependencies	pnpm i	https://pnpm.io/cli/install
Add a dependency	pnpm add <package>	https://pnpm.io/cli/add
Shows all packages that depend on the specified package	pnpm why <package>	https://pnpm.io/cli/why
Run a command as if it was executed form the root of the project rather than a workspace package	pnpm -w <command>	https://pnpm.io/pnpm-cli#-w---workspace-root
Restrict commands to specific subsets of packages	pnpm --filter <package_selector> <command>	https://pnpm.io/filtering
This runs an arbitrary command from each package's "scripts" object	pnpm -r <command>	https://pnpm.io/cli/run#--recursive--r