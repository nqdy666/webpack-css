WEBPACK-CSS

> package css with webpack

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![build status](https://travis-ci.org/nqdy666/webpack-css.svg?branch=master)](https://travis-ci.org/nqdy666/webpack-css.svg?branch=master)

> [中文](./README.md)

## Features
- webpack4
- babel7
- dart-sass
- support package multi css

## Cases

Package element ui theme [vve-element-theme](https://github.com/vue-viewer-editor/vve-element-theme)

Package iconfont [vve-rjyr-iconfont](https://github.com/vue-viewer-editor/vve-rjyr-iconfont)

## Development

- Installation dependencies

```bash
npm install
```

- Development

```bash
npm run dev

# or designate a entry
npm start -- --evn.SINGLE_ENTRY=main
```

- Package

```bash
npm run build
```

- Release

```bash
npm run release
Git push --follow-tags origin master && npm publish
```

## Donation
If you find it useful, you can buy us a cup of coffee.

<img width="650" src="https://raw.githubusercontent.com/nqdy666/webpack-css/master/qrcode-donation.png" alt="donation">
