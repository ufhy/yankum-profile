# electron-vite-vue

[![awesome-vite](https://awesome.re/mentioned-badge.svg)](https://github.com/vitejs/awesome-vite)
[![Netlify Status](https://api.netlify.com/api/v1/badges/ae3863e3-1aec-4eb1-8f9f-1890af56929d/deploy-status)](https://app.netlify.com/sites/electron-vite/deploys)
![GitHub license](https://img.shields.io/github/license/caoxiemeihao/electron-vite-vue?style=flat)
![GitHub stars](https://img.shields.io/github/stars/caoxiemeihao/electron-vite-vue?color=fa6470&style=flat)
![GitHub forks](https://img.shields.io/github/forks/caoxiemeihao/electron-vite-vue?style=flat)


**English | [็ฎไฝไธญๆ](README.zh-CN.md)**

๐ฅณ Really simple `Electron` + `Vue` + `Vite` boilerplate.

## Overview

๐ฆ Out of the box  
๐ฏ Based on [vue-ts](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-vue-ts) template, less invasive  
๐ฑ Simple directory structure๏ผreal flexible  
๐ช Support Use ElectronใNode.js API and in Renderer-process  
๐ฉ Support C/C++ native addons  
๐ฅ It's easy to implement multiple windows  

## Quick Start

```sh
npm create electron-vite
```

<!-- [![quick-start](https://asciinema.org/a/483731.svg)](https://asciinema.org/a/483731) -->

![electron-vite-vue.gif](https://github.com/electron-vite/electron-vite-vue/blob/main/public/electron-vite-vue.gif?raw=true)

## Debug

![electron-vite-react-debug.gif](https://github.com/electron-vite/electron-vite-react/blob/main/public/electron-vite-react-debug.gif?raw=true)

## Directory

```diff
+ โโโฌ electron
+ โ โโโฌ main
+ โ โ โโโ index.ts    entry of Electron-main
+ โ โโโฌ preload
+ โ   โโโ index.ts    entry of Electron-preload
  โโโฌ src
  โ โโโ main.ts       entry of Electron-renderer
  โโโ index.html
  โโโ package.json
  โโโ vite.config.ts
```

## List the modules you may use as far as possible

Used in `Main-process` ๐ [electron-vite-boilerplate](https://github.com/caoxiemeihao/electron-vite-boilerplate)

Used in `Renderer-process` ๐ [electron-vite-boilerplate/tree/nodeIntegration](https://github.com/caoxiemeihao/electron-vite-boilerplate/tree/nodeIntegration)

**ES Modules**

- [execa](https://www.npmjs.com/package/execa)
- [node-fetch](https://www.npmjs.com/package/node-fetch)
- [file-type](https://www.npmjs.com/package/file-type)

**Native Addons(C/C++)**

- [sqlite3](https://www.npmjs.com/package/sqlite3)
- [serialport](https://www.npmjs.com/package/serialport)
