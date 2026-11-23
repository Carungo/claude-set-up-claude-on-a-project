# CLAUDE.md

## Commands
- `npm install` — Install project dependencies
- `npm start` — Start the Express server (`server.js`)
- `npm test` — Run the automated test suite in `tests/`
- `npm run lint` — Check code style against `.eslintrc.json`

## Architecture
- `server.js` — Main application entry point and Express server setup
- `routes/` — API route handlers (`health.js` and user endpoints)
- `db/` — Database and data store logic (`store.js`)
- `tests/` — Automated tests (`users.test.js`)

## Conventions
- Never hardcode secrets or environment variables; use `.env` based on `.env.example`
- Follow the ESLint rules configured in `.eslintrc.json`
- Run `npm test` after making changes to verify all tests pass
