# vscode-iconfont-preview

在 VSCode 中直接预览你的 iconfont 图标，无需任何配置。

[English](./README.md)

![vscode iconfont preview](https://img.alicdn.com/tfs/TB1sLl_dhGYBuNjy0FnXXX5lpXa-1414-1112.png)

## 使用须知

目前仅支持 [iconfont.cn](iconfont.cn) 自动生成的 iconfont 样式（需包含 `@font-family` 定义及 `.svg` 格式的 iconfont 地址引用），但是本插件可以通过简单的修改支持其他 iconfont 服务（如 font-awesome）。

## 已知限制

如果在一个样式文件中定义了多个 `@font-family`，只会解析第一个 iconfont 对应的图标。

## 发布记录

### 0.1.0

第一版发布
