# Flyrank Frontend Track

Guidance for working in this repository.

## Stack

- React
- Vite
- TypeScript
- Tailwind CSS

## Conventions

- Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages (for example `feat:`, `fix:`, `docs:`, `chore:`).
- Write React UI as functional components. Prefer hooks over class components.
- Do not commit secrets. Keep API keys, tokens, and credentials out of the repo. Use `.env` locally and never check it in.

## npm commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Type-check and produce a production build |
| `npm run lint` | Run the project linter |

Install dependencies with `npm install` before running these scripts.
