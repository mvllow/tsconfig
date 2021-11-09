# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```sh
npm install --save-dev @mvllow/tsconfig
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@mvllow/tsconfig",
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

When targeting a higher version of Node.js, check the relevant ECMAScript version and add it as target:

```json
{
	"extends": "@mvllow/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2021"
	}
}
```

_Inspired by [@sindresorhus](https://github.com/sindresorhus)_
