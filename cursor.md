# Project Instructions for Cursor

This file provides context and conventions for AI agents working in this project.

## Project Overview

A Node.js backend/application project written in TypeScript.

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Package manager:** npm

## Development

### Setup

```bash
npm install
```

### Common Commands

| Task | Command |
|------|---------|
| Run dev | `npm run dev` |
| Build | `npm run build` |
| Start (production) | `npm start` |
| Test | `npm test` |
| Lint | `npm run lint` |
| Type check | `npx tsc --noEmit` |

## Code Conventions

- Use TypeScript strictly — prefer explicit types over `any`.
- Use `async/await` for asynchronous code; avoid callback-style patterns.
- Use ES modules (`import`/`export`) unless the project is configured for CommonJS.
- Keep changes focused and minimal — fix only what the task requires.
- Match existing naming, structure, and patterns in the codebase.
- Prefer clear, self-explanatory code over unnecessary comments.
- Add tests only when they provide meaningful coverage.

## Project Structure

```
src/           # Application source (TypeScript)
dist/          # Compiled JavaScript output (generated)
tests/         # Test files
```

## Boundaries

- Do not commit secrets (`.env`, credentials, API keys).
- Do not modify unrelated files when fixing a specific issue.
- Do not edit generated files in `dist/` — change source in `src/` instead.
- Ask before making large architectural changes.

## Notes

- Target Node.js LTS versions when choosing APIs and dependencies.
- Keep `tsconfig.json` strict (`strict: true`) unless there is a documented reason not to.
