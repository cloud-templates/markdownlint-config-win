# @winner-fed/markdownlint-config-win

本包提供了《文档规约》配套的 [markdownlint 可共享配置](https://www.npmjs.com/package/markdownlint#optionsconfig)。

## 安装

除了本包，需要同时安装 [markdownlint](https://www.npmjs.com/package/markdownlint)：

```bash
npm install @winner-fed/markdownlint-config-win markdownlint --save-dev
```

## 使用

在 `.markdownlint.json` 中继承本包:

```json
{
  "extends": "./node_modules/@winner-fed/markdownlint-config-win/index.json"
}
```
