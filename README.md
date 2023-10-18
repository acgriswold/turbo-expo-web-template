# Turborepo expo next.js start template

This repo is the initial attempt to build a web and mobile app using turbo repo

## Getting started

### Run all
```bash
  pnpm install
  pnpm build
  pnpm dev
```

### Running web
```bash
  pnpm install
  pnpm dev --filter web
```

### Running native (tunnel)
```bash
  pnpm install
  pnpm build --filter native
  cd apps/native
  pnpm run start --tunnel
```

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `native`: a [react-native](https://reactnative.dev/) app built with [expo](https://docs.expo.dev/)
- `web`: a [Next.js](https://nextjs.org/) app built with [react-native-web](https://necolas.github.io/react-native-web/)
- `ui`: a stub [react-native](https://reactnative.dev/) component library shared by both `web` and `native` applications
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [Expo](https://docs.expo.dev/) for native development
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [Prettier](https://prettier.io) for code formatting
