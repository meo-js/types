<!-- <p align="center">
<img src="https://raw.githubusercontent.com/unocss/unocss/main/playground/public/icon-gray.svg" style="width:100px;" />
</p> -->

<h1 align="center">
@meojs/types
</h1>

<p align="center">
一些有用的 TypeScript 类型。
</p>

<!-- <br>
<p align="center">
<a href="https://unocss.dev/">Documentation</a> |
<a href="https://unocss.dev/play/">Playground</a>
</p>
<br> -->

<br>
<p align="center">
<a href="./README.md">English</a> |
<span>简体中文</span>
</p>

## 简介

```bash
npm i @meojs/types
```

所有类型定义可通过在项目的 `tsconfig.json` 文件中的 `compilerOptions.types` 字段数组中添加对应路径来使用：

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

虽然官方提供了类型包 [@cocos/creator-types](https://github.com/cocos/creator-types)，但存在以下问题：

- 不及时更新。
- 缺少 `cc/env` 类型文件。

导入路径列表：

- v3.8.5
  - `@meojs/types/cocos-creator/3.8.5/editor`
  - `@meojs/types/cocos-creator/3.8.5/engine`

## 贡献

- 执行 `npm version patch && npm publish` 推送新版本。

## 许可证

[MIT @ SmallMain](./LICENSE)
