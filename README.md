<p align="center">
    <a href="https://www.iviewui.com">
        <img width="200" src="https://file.iviewui.com/view-ui-logo-new.svg">
    </a>
</p>

<h1>
View UI Plus
    <h3>An enterprise-level UI component library and front-end solution based on Vue.js 3</h3>
</h1>

> View UI Plus自从发布1.3.1版本后基本上就不再维护更新，但由于工作开发中涉及该UI库，因此本人另开分支继续维护开发使用。

> 二次开发
> ```
> # 打包
> npm run build
> # 发布（发布前需要登录账号，执行npm login根据提示来就行了，第一次发布失败的话，可能还需要执行npm config set access public）
> npm publish
> # 撤销发布
> npm unpublish @leisure01/view-ui-plus@1.3.21 --force
> # 本地调试预览
> npm run dev
>
> ```

[![View UI Plus](https://img.shields.io/npm/v/@leisure01/view-ui-plus.svg?style=flat-square)](https://www.npmjs.org/package/@leisure01/view-ui-plus)
[![NPM downloads](http://img.shields.io/npm/dm/@leisure01/view-ui-plus.svg?style=flat-square)](https://npmjs.org/package/@leisure01/view-ui-plus)
[![NPM downloads](https://img.shields.io/npm/dt/@leisure01/view-ui-plus.svg?style=flat-square)](https://npmjs.org/package/@leisure01/view-ui-plus)
![JS gzip size](http://img.badgesize.io/https://unpkg.com/view-ui-plus/dist/viewuiplus.min.js?compression=gzip&label=gzip%20size:%20JS&style=flat-square)
![CSS gzip size](http://img.badgesize.io/https://unpkg.com/view-ui-plus/dist/styles/viewuiplus.css?compression=gzip&label=gzip%20size:%20CSS&style=flat-square)
[![Join the chat at https://gitter.im/iview/iview](https://img.shields.io/badge/chat-on_gitter-30b392.svg?style=flat-square)](https://gitter.im/iview/iview?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Docs

[https://www.iviewui.com](https://www.iviewui.com)

## Start On Cloud IDE
[https://idegithub.com/view-design/ViewUIPlus](https://idegithub.com/view-design/ViewUIPlus)

### Install View UI Plus

Using npm:
```
npm i @leisure01/view-ui-plus --save
```

Using a script tag for global use:
```html
<script type="text/javascript" src="viewuiplus.min.js"></script>
<link rel="stylesheet" href="dist/styles/viewuiplus.css">
```

You can find more info [on the website](https://www.iviewui.com/view-ui-plus/guide/install).

### Import View UI Plus
```
import { createApp } from 'vue'
import ViewUIPlus from "@leisure01/view-ui-plus"; //引入ViewUIPlus
import App from './App.vue'
import router from './router'
import store from './store'
import "@leisure01/view-ui-plus/dist/styles/viewuiplus.css";

const app = createApp(App)

app.use(store)
  .use(router)
  .use(ViewUIPlus)
  .mount('#app')
```

## Usage

```vue
<template>
    <Slider v-model="value" range />
</template>
<script setup>
    import { ref } from 'vue'
    const value = ref([20, 50])
</script>
```

## Community

If you want to contribute us or in case you are haiving any doubt.

**Questions:** Find other users at the [Gitter chat](https://gitter.im/iview/iview) or post on [StackOverflow using `[iview-ui]` tag](https://stackoverflow.com/questions/tagged/iview-ui)  
**Bugs:** [File a issue here](https://www.iviewui.com/new-issue) - please provide a example so we can help you better  
**Contribute:** Contact us in [Gitter chat](https://gitter.im/iview/iview), WeChat or via mail to `admin@aresn.com`. PRs welcome!

## Major Contributors
|Name|Avatar|Name|Avatar|Name|Avatar|
|---|---|---|---|---|---|
|[Aresn](https://github.com/icarusion) |  ![](https://avatars3.githubusercontent.com/u/5370542?v=3&s=60)  |[jingsam](https://github.com/jingsam) |  ![](https://avatars3.githubusercontent.com/u/1522494?v=3&s=60)  | [rijn](https://github.com/rijn)       |  ![](https://avatars2.githubusercontent.com/u/6976367?v=3&s=60)  |
|[lcx960324](https://github.com/lcx960324)           |  ![](https://avatars3.githubusercontent.com/u/9768245?v=3&s=60)  |[GITleonine1989](https://github.com/GITleonine1989) |  ![](https://avatars1.githubusercontent.com/u/7582490?v=3&s=60)  |[huixisheng](https://github.com/huixisheng)         |  ![](https://avatars1.githubusercontent.com/u/1518967?v=3&s=60)  |
|[Sergio Crisostomo](https://github.com/SergioCrisostomo)           |  ![](https://avatars3.githubusercontent.com/u/5614559?v=3&s=60)  |  [lison16](https://github.com/lison16)           |  ![](https://avatars3.githubusercontent.com/u/20942571?v=3&s=60) |  [Xotic750](https://github.com/Xotic750)    | ![](https://avatars3.githubusercontent.com/u/216041?v=3&s=60)   |
[huanghong1125](https://github.com/huanghong1125) | ![](https://avatars3.githubusercontent.com/u/12794817?v=3&s=60) | [yangdan8](https://github.com/yangdan8) | ![](https://avatars2.githubusercontent.com/u/16515026?v=3&s=60) | [likuner](https://github.com/likuner)| ![](https://avatars3.githubusercontent.com/u/18632318?v=3&s=60)  |


## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present, ViewDesign
