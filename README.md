WEBPACK-CSS

> 使用 webpack 打包 css

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![build status](https://travis-ci.org/nqdy666/webpack-css.svg?branch=master)](https://travis-ci.org/nqdy666/webpack-css.svg?branch=master)

> [English Document](./README_EN.md)

## 特性
- webpack4
- babel7
- dart-sass
- 支持打包多个css

## 案例

打包element ui主题 [vve-element-theme](https://github.com/vue-viewer-editor/vve-element-theme)

打包iconfont字体 [vve-rjyr-iconfont](https://github.com/vue-viewer-editor/vve-rjyr-iconfont)


## 开发

- 安装依赖

```bash
npm install
```

- 开发

```bash
npm start

# 或者指定某个entry
npm start -- --evn.SINGLE_ENTRY=main
```

- 打包

```bash
npm run build
```

- 发布

```bash
npm run release
git push --follow-tags origin master && npm publish
```

## 捐赠

如果你觉得它有用，你可以给我买一杯奶茶。

<img width="650" src="https://raw.githubusercontent.com/nqdy666/webpack-css/master/qrcode-donation.png" alt="donation">
