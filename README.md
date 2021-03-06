<p align="center">
  <img src="https://raw.githubusercontent.com/mtobeiyf/pile/master/build/icons/pile.png" width="200px" alt="">
</p>

<p align="center">
  <a href="https://github.com/mtobeiyf/pile/releases">
    <img src="https://img.shields.io/github/release/mtobeiyf/pile.svg" alt="">
  </a>
  <a href="http://perso.crans.org/besson/LICENSE.html">
    <img src="https://img.shields.io/badge/License-GPLv3-green.svg" alt="">
  </a>
</p>

# Pile

> Organize your piled work at one place.

[README](https://github.com/mtobeiyf/pile/blob/master/README.md) | [中文说明](https://github.com/mtobeiyf/pile/blob/master/README_zh.md)

<p align="center">
  <img src="https://s18.postimg.org/8xfca4ad5/sshot-1.png" width="600px" alt="">
</p>

## Why Pile?

The way we get things done is often project-oriented. However, the files, applications, tasklists, etc. are **scattered everywhere**. Pile is a place for you to **put them all together**.

## Usage

Before we get started, let me help you get it more clear how to use Pile.

### Board

A board (or tab) is a place to hold all the resources of your **project** or **workspace**. You can organize your things related to the project/workspace using *hubs*.

### Hub

A hub (or card) is an area for specific stuff. There are currently three kinds of hubs:

#### App/File

You can add apps or files you may use in this area so that you can quickly access them and open them.

<p align="center">
  <img src="https://s18.postimg.org/l6yd1ahux/pile11.gif" width="700px" alt="">
</p>

#### Notes

Online resources (often appeared as links) or your thoughts can be taken down here. **Markdown** is supported! :tada:

<p align="center">
  <img src="https://s18.postimg.org/gauq96hl5/pile2.jpg" width="700px" alt="">
</p>

#### Todo

A simple todolist related to the project.

<p align="center">
  <img src="https://s18.postimg.org/732hsukx5/pile3.jpg" width="700px" alt="">
</p>

## Features

- Drag and drop, easy and convenient.
- Various application scenarios.
- Endless possibilities. Developer, designer, writer...
- Markdown support, emoji included.

## Installation

Go to the [release page](https://github.com/mtobeiyf/pile/releases)

Download and run the setup **.exe** file and Pile will be insalled automatically

Or download the portable **.zip** file, unzip it and run `Pile.exe`

## Technical

### Stack

- [Electron](https://electronjs.org/) : Framework
- [electron-vue](https://github.com/SimulatedGREG/electron-vue) : Skeleton
- [iView](https://www.iviewui.com/) : UI toolkit

### Build Setup

``` bash
# install dependencies
yarn # or npm install

# serve with hot reload at localhost:9080
yarn run dev # or npm run dev

# build electron application for production
yarn run build:dir # or npm run build:dir

```

---

## Versions

### 0.1.1

#### Features
- Tray icon support
- Edit boards in settings
- One instance restriction

#### Fixes

- Context menu missing for items
- Wrong tooltip for setting button

### 0.1.0

- Initial release

## Acknowledgment

- [Vue.js](https://vuejs.org/)
- [vue-markdown](https://github.com/miaolz123/vue-markdown)
- [lowdb](https://github.com/typicode/lowdb)
- [Backlog](https://github.com/czytelny/backlog)

## License

Licensed under the [GPL v3.0](https://opensource.org/licenses/GPL-3.0) License.

Copyright (c) 2018 [Fing](http://imfing.com). 
All rights reserved.
