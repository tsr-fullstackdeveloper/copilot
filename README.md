# Mastering the GitHub Copilot App

WeAreDevelopers India, 25 November 2026, 15:30–17:30 IST. Romaan Shair and Siddhat Joshi.

This repository starts with a working, dependency-free session planner using fictional talks. The missing track filter is intentional.

[Workshop landing page](https://roshair.github.io/ghcp-app-weareDevelopers-workshop/) · [Lab guide](docs/guide.md)

## Run locally

Use Node.js 22.x (the workshop and CI pin is in `.nvmrc`). From the repository root:

```sh
npm ci
npm test
npm run build
npm start
```

Open [the planner](http://127.0.0.1:4173/planner/) in a browser. Use `Ctrl+C` to stop the server. Nothing needs a key, database, or external API.

- `docs/planner/` — app source.
- `test/` — Node's built-in test runner.
- `dist/planner/` — generated static build.
