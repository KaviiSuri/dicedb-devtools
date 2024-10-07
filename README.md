# DiceBox

This is a monorepo that contains all dicedb related tools and applications.

## What's inside?

This monorepo includes the following packages/apps:

### Apps and Packages

- `@dicedb/playground-web`: an interactive platform designed to let users experiment with [DiceDB](https://github.com/dicedb/dice/) commands in a live environment, similar to the Go Playground
- `@dicedb/ui`: common UI components for alloy apps

### Configurations

- `@dicedb/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@dicedb/typescript-config`: `tsconfig.json`s used throughout the monorepo
- `@dicedb/tailwind-config`: `tailwind.config.js`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Build

To build all apps and packages, run the following command:

```
cd my-turborepo
pnpm build
```

### Develop

To develop all apps and packages, run the following command:

```
cd my-turborepo
pnpm dev
```
