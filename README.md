# [koa](https://github.com/careteenL/koa)
[![](https://img.shields.io/badge/Powered%20by-koa-brightgreen.svg)](https://github.com/careteenL/koa)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/careteenL/koa/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/careteenL/koa.svg?branch=master)](https://travis-ci.org/careteenL/koa)
[![npm](https://img.shields.io/badge/npm-0.1.0-orange.svg)](https://www.npmjs.com/package/@careteen/koa)
[![NPM downloads](http://img.shields.io/npm/dm/@careteen/koa.svg?style=flat-square)](http://www.npmtrends.com/@careteen/koa)

<!-- [English Document](./README.en_US.md) -->

学习并仿写`koa`，目前已提供基础功能。

- [x] 基础功能
- [ ] 完善`request.js`
- [ ] 完善`response.js`

## 快速使用

安装
```shell
npm i -D @careteen/koa
```

使用方式和`koa`一样

```js
const Koa = require('@careteen/koa')
const app = new Koa()
// response
app.use(ctx => {
  ctx.body = 'Hello Koa'
})
app.listen(3000)
```

## 使用文档

- [对该库的源码解析](https://github.com/careteenL/66ball/tree/master/src/20181218-koa)

## issue模板

- [Issue Template](./ISSUETEMPLATE.md)

## 贡献者指南

clone仓库并引入依赖
```shell
git clone git@github.com:careteenL/koa.git
npm install
```
开始开发：）

...

启动本地服务器编写示例
```shell
npm run example
```
- [Contributors](https://github.com/careteenL/koa/graphs/contributors)

## 更新日志

- [Changelog](./CHANGELOG.md)
