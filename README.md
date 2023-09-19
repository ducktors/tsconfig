# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ pnpm add -D @ducktors/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@ducktors/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```
Check [fastify-tsconfig](https://github.com/fastify/tsconfig) for other options.

**This project is inspired by**: [sindresorhus/tsconfig](https://github.com/sindresorhus/tsconfig)

## License

MIT © [Ducktors](https://ducktors.dev)
