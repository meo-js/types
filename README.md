<!-- <p align="center">
<img src="https://raw.githubusercontent.com/unocss/unocss/main/playground/public/icon-gray.svg" style="width:100px;" />
</p> -->

<h1 align="center">
@meojs/types
</h1>

<p align="center">
Some useful TypeScript types.
</p>

<!-- <br>
<p align="center">
<a href="https://unocss.dev/">Documentation</a> |
<a href="https://unocss.dev/play/">Playground</a>
</p>
<br> -->

<br>
<p align="center">
<span>English</span> |
<a href="./README_zh-CN.md">简体中文</a>
</p>

## Introduction

```bash
npm i @meojs/types
```

All type definitions can be used by adding the corresponding path to the `compilerOptions.types` field array in your project's `tsconfig.json` file:

```jsonc
{
  "compilerOptions": {
    "types": [
      "@meojs/types/xxx",
    ]
  }
}
```

### Cocos Creator Types

This package provides type definitions for Cocos Creator until the official type package [@cocos/creator-types](https://github.com/cocos/creator-types) is updated in a timely manner.

Import path list:

- v3.8.5
  - `@meojs/types/cocos-creator/3.8.5/editor`
  - `@meojs/types/cocos-creator/3.8.5/engine`

## Contributing

- Run `npm version patch && npm publish` to push a new version.

## License

[MIT @ SmallMain](./LICENSE)
