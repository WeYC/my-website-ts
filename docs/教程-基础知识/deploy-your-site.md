---
sidebar_position: 5
---

# 部署您的网站

Docusaurus 是一个 **静态站点生成器**（也称为 **[Jamstack](https://jamstack.org/)**）。

它将您的网站构建为简单的**静态 HTML、JavaScript 和 CSS 文件**。

## 建立您的网站

构建您的网站用于生产(**production**)：


```bash
npm run build
```

静态文件在 `build`  文件夹中生成。

## 部署您的站点

在本地测试您的生产(**production**)版本：


```bash
npm run serve
```

`build` 文件夹现在位于 [http://localhost:3000/](http://localhost:3000/)。

您现在可以轻松部署 `build` 文件夹**几乎任何地方**，**免费**或只需很少的成本（阅读**[部署指南](https://docusaurus.io/docs/deployment)**）。
