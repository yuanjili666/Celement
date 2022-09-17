<p align="center">
  <img src="https://cdn.rawgit.com/ElemeFE/element/dev/element_logo.svg">
</p>

# 项目介绍
1.当前这个项目是是element ui 2.15.10 版本的 源码 继续进行二次改造，并且更改了包名上传到个人的npm 上
2.上传的npm 包名是 celemui  ，npm 上的连接：https://www.npmjs.com/package/celemui


# 版本变更介绍

### 1、初始版本2.0.1
  1.修改级联组件的多选回显问题，cy 设置，可以实现父级别设置后子级别也能够回显选中效果
  2.

### 2、V 2.0.2
1.修改README 文件的介绍
2.修改git 地址


> A Vue.js 2.0 UI Toolkit for Web.

Element will stay with Vue 2.x 

For Vue 3.0, we recommend using [Element Plus](https://github.com/element-plus/element-plus) from the same team (Element Plus is a community develop project)

## Links
- Homepage and documentation
  - [International users](http://element.eleme.io/#/en-US)
  - [Chinese users](http://element-cn.eleme.io/#/zh-CN)
  - [Spanish users](http://element.eleme.io/#/es)
  - [French users](http://element.eleme.io/#/fr-FR)
- [awesome-element](https://github.com/ElementUI/awesome-element)
- [FAQ](./FAQ.md)
- [Vue.js 3.0 migration](https://github.com/element-plus/element-plus)
- [Customize theme](http://element.eleme.io/#/en-US/component/custom-theme)
- [Preview and generate theme online](https://elementui.github.io/theme-chalk-preview)
- [Element for React](https://github.com/elemefe/element-react)
- [Element for Angular](https://github.com/ElemeFE/element-angular)
- [Atom helper](https://github.com/ElemeFE/element-helper)
- [Visual Studio Code helper](https://github.com/ElemeFE/vscode-element-helper)
- Starter kit
  - [element-starter](https://github.com/ElementUI/element-starter)
  - [element-in-laravel-starter](https://github.com/ElementUI/element-in-laravel-starter)
- [Design resources](https://github.com/ElementUI/Resources)
- Gitter
  - [International users](https://gitter.im/element-en/Lobby)
  - [Chinese users](https://gitter.im/ElemeFE/element)

## Install
```shell
npm install celemui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'celemui'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'celemui'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.

## Browser Support
Modern browsers and Internet Explorer 10+.

## Development
Skip this part if you just want to use Element.

For those who are interested in contributing to Element, please refer to our contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md) | [Español](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.es.md) | [Français](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.fr-FR.md)) to see how to run this project.

## Changelog
Detailed changes for each release are documented in the [release notes](https://github.com/ElemeFE/element/releases).

## FAQ
We have collected some [frequently asked questions](https://github.com/ElemeFE/element/blob/master/FAQ.md). Before reporting an issue, please search if the FAQ has the answer to your problem.

## Contribution
Please make sure to read the contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md) | [Español](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.es.md) | [Français](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.fr-FR.md)) before making a pull request.

## LICENSE
[MIT](LICENSE)
