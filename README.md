# Turborepo hanging process example

This repo of [the issue reported here](https://github.com/vercel/turborepo/issues/1802).
The repo is based on [the Turborepo basic starter](https://github.com/vercel/turborepo/tree/main/examples/basic).

## What's the issue

When you run Nextjs with Turbo using the Terminal in VS Code the process never stops when you quit VS Code.

## Recreate

1. Install dependencies using `yarn`.
2. Open this repo using VS Code.
3. Run Nextjs using `yarn yarn:dev` using the terminal inside VS Code.
4. Check that Nextjs is running at `http://localhost:3000`.
5. Quit VS Code.
6. Check that nothing is running at `http://localhost:3000`.
7. Open VS Code.
8. Run Nextjs using `yarn turbo:dev` using the terminal inside VS Code.
9. Quit VS Code.
10. Check that Nextjs is still running at `http://localhost:3000`.
