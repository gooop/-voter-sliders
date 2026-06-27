# Voter Sliders

An interactive electoral map. Slide demographic inputs (turnout, race, gender, etc.) and
watch the U.S. electoral map respond to how those shifts would affect the vote. Presets will
illustrate the potential and realized effects of legislation that suppresses or expands voting.

This repository was bootstrapped from [gooop/ts-template](https://github.com/gooop/ts-template),
porting its TypeScript/ESLint/Prettier/Vitest conventions onto a Vite + React stack so the
project is locally deployable.

## Tech stack

- [Vite](https://vite.dev/) for dev server and build
- [React 18](https://react.dev/) + TypeScript
- [Vitest](https://vitest.dev/) + [Testing Library](https://testing-library.com/) for tests
- ESLint (flat config) + Prettier for linting and formatting

## Getting started

```bash
npm install      # install dependencies
npm run dev      # start the local dev server (http://localhost:5173)
```

## Scripts

| Script                 | Description                                  |
| ---------------------- | -------------------------------------------- |
| `npm run dev`          | Start the Vite dev server                    |
| `npm run build`        | Type-check and build for production          |
| `npm run preview`      | Preview the production build locally         |
| `npm test`             | Run the test suite once                      |
| `npm run test:watch`   | Run tests in watch mode                      |
| `npm run lint`         | Lint the `src` directory                     |
| `npm run format`       | Format the `src` directory with Prettier     |
| `npm run format:check` | Check formatting without writing changes     |

## Roadmap

1. ✅ Scaffold the repo from the TS template, ported to React.
2. ⬜ Render an abstracted map of America (grid of squircles).
3. ⬜ Investigate data sources for 2024 presidential voter turnout at the state level.
