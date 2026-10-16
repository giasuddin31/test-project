# test-project

A Node.js test project by Gias. It currently uses CommonJS and `dotenv` for environment variables.

## Requirements

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (bundled with Node.js)

## Getting started

```bash
npm install
```

Create a `.env` file in the project root for local secrets and configuration. `dotenv` will load these values when you add it to your entry file:

```js
require("dotenv").config();
```

The package `main` field points to `index.js`. Add that file when you start application code.

## Scripts

| Script | Description |
|--------|-------------|
| `npm test` | Placeholder; no tests are defined yet |

## Project layout

```text
test-project/
├── package.json
├── package-lock.json
├── .vscode/          # Editor settings
└── .cursor/          # Cursor project context
```

## License

ISC
