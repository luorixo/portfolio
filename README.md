
- ⚡️ [Vite 5](https://vitejs.dev/)
- ⚛️ [React 18](https://reactjs.org/)
- 💎 [TypeScript](https://www.typescriptlang.org/)
- 🔨 [EsLint](https://eslint.org/)
- 🌀 [Prettier](https://prettier.io)
- 🐺 [Husky](https://github.com/typicode/husky)
- ⚙️ [Vitest](https://vitest.dev/guide/)
- 📑 [Commitlint](https://commitlint.js.org/) - Lints commits based on commit convention
- ⌨️ Absolute Imports

## Usage

```bash
yarn
yarn dev
```

## Available commands

<p>You can run the following scripts:</p>

| Script     | Description                                                                 |
| ---------- | --------------------------------------------------------------------------- |
| dev        | Run the app in development mode                                             |
| build      | Build the app for production to the `dist` folder                           |
| lint       | Run Eslint and show code problems                                           |
| format     | Run Prettier and fix code style                                             |
| preview    | Build the app for production to the `dist` folder, and run on local server  |
| test       | Run the app tests                                                           |
| test:watch | Run the app tests in watch mode                                             |

For correctly functioning (code and tests) absolute imports, edit:

- vite.config.ts
- tsconfig.json
