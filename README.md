# test-project

A small Node.js workspace owned by Asif. It is currently a starter package (`v1.0.0`) with `dotenv` installed for environment configuration.

## Requirements

- Node.js 12 or later
- npm

## Setup

```bash
npm install
```

Copy environment variables into a `.env` file in the project root. `dotenv` can load them at runtime:

```js
require("dotenv").config();
```

## Scripts

| Script | Description |
| --- | --- |
| `npm test` | Placeholder (no tests yet) |

There is no start or build script yet. `package.json` lists `index.js` as the main entry point.

## Intended stack

These notes from the workspace describe the direction for the app:

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router, server components by default)
- **UI:** React
- **Package manager:** npm

## License

ISC
