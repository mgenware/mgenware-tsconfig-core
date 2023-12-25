# mgenware-tsconfig-core

[![npm version](https://img.shields.io/npm/v/mgenware-tsconfig-core.svg?style=flat-square)](https://npmjs.com/package/mgenware-tsconfig-core)

Base `tsconfig.json` for Mgenware TypeScript projects. TypeScript 5+, node 18+.

## Installation

```sh
npm i -D mgenware-tsconfig-core
```

NOTE: package major version indicates the minimum supported node version.

## Usage

Extend this config:

```json
{
  "extends": "mgenware-tsconfig-core"
}
```

Set the following compiler options based on your needs:

- `lib`
- `target`
