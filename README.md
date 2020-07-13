# Node TypeScript Starter

## Getting started

1. Clone this repository and open it

```bash
$ git clone https://github.com/HashDot/node-ts
$ cd node-ts
```

2. Install dependencies

```bash
$ npm i
```

3. Launch the dev mode

```bash
$ npm run dev
```

4. You can start coding! The entry point is located in `src/index.ts`.

## What's preconfigured?

- Babel
- TypeScript
- ESLint
- Prettier
- Husky pre-commit hook that runs ESLint and type checks the code base
- A few npm scripts

## Scripts

- `npm run dev`. Runs the project in dev mode, which means that it won't check types and will restart with every change you make.
- `npm run build`. Compiles the project to the `./dist` folder.
- `npm run typecheck`. Checks the typings of the project. Gets executed before trying to create a new commit but you can also run it manually.
- `npm run start`. Runs the compiled program. Remember to execute `npm run build` before attempting to launch the program.
- `npm run lint`. Runs ESLint. You can append `--fix` in order to fix autofixable issues.
