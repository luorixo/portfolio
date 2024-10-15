
- ⚡️ [Vite 5](https://vitejs.dev/) - Next Generation Frontend Tooling
- ⚛️ [React 18](https://reactjs.org/) - A JavaScript library for building user interfaces
- 💎 [TypeScript](https://www.typescriptlang.org/) - Why not?!
- 🔨 [EsLint](https://eslint.org/) - Pluggable JavaScript linter
- 🌀 [Prettier](https://prettier.io) - Opinionated Code Formatter
- 🐺 [Husky](https://github.com/typicode/husky) - Native Git hooks
- ⚙️ [Vitest](https://vitest.dev/guide/) - Testing library
- 📑 [Commitlint](https://commitlint.js.org/) - Linting your commits based on commit convention
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
| dev        | Runs the app in the development mode.                                       |
| build      | Builds the app for production to the `dist` folder.                         |
| lint       | Runs the Eslint and show code problems                                      |
| format     | Runs the Prettier and fix code style                                        |
| preview    | Builds the app for production to the `dist` folder, and run locally server. |
| test       | Run the app tests.                                                          |
| test:watch | Run the app tests in watch mode.                                            |

## About the absolute imports

For correctly functioning (code and tests) absolute imports, edit:

- vite.config.ts
- tsconfig.json

## License

[MIT](https://choosealicense.com/licenses/mit/)
