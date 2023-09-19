# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ npm install --save-dev @ducktors/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@ducktors/tsconfig",
  "compilerOptions": {
    "outDir": "build",
    "target": "es2022",
    "lib": ["es2022"]
  }
}
```

**This project is inspired by**: [sindresorhus/tsconfig](https://github.com/sindresorhus/tsconfig)

## License

MIT © [Ducktors](https://ducktors.dev)
