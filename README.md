# Test Soft

My First AI Agent — a Node.js project for building and experimenting with AI agent workflows.

## Overview

Test Soft is an early-stage Node.js application intended to grow into a TypeScript-based backend for AI agent development. The project uses environment variables for configuration and is set up for local development with npm.

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript (planned)
- **Package manager:** npm
- **Dependencies:** [dotenv](https://www.npmjs.com/package/dotenv) for environment variable management

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (included with Node.js)

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd test-soft
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root for local secrets and configuration:

```bash
# .env
# Add your environment variables here
```

> **Note:** Do not commit `.env` files or other secrets to version control.

## Scripts

| Command       | Description                          |
|---------------|--------------------------------------|
| `npm test`    | Run tests (not yet configured)       |

Additional scripts such as `dev`, `build`, and `start` will be added as the project grows.

## Project Structure

```
test-soft/
├── src/           # Application source (TypeScript) — planned
├── dist/          # Compiled JavaScript output — planned
├── tests/         # Test files — planned
├── cursor.md      # AI agent project instructions
├── package.json
└── README.md
```

## Development

This project follows conventions documented in [`cursor.md`](./cursor.md), including:

- Strict TypeScript with explicit types
- `async/await` for asynchronous code
- Focused, minimal changes per task
- No secrets in the repository

## Author

Ariful Islam

## License

ISC
