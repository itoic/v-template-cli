# v-template-cli

English | [简体中文](./README-zh.md)

Cli tool for automatically pulling vue project templates

Include：

- [vue-admin-template](https://github.com/lyhmyd1211/v-templates/tree/admin)：Based on [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template) backend management system template, and adds commonly used tool functions and some packaging and compatibility modifications to element-ui components.

* [vue-app-template](https://github.com/lyhmyd1211/v-templates/tree/app)：Lightweight WebApp template. Use [vant](https://youzan.github.io/vant/#/) as the basic ui component library, and use [lib-flexible](https://github.com/amfe/lib-flexible/) Rem adaptation with [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem).

- [vue-visual-template](https://github.com/lyhmyd1211/v-templates/tree/visual)：Visualize large-screen project templates. Simple vue component packaging for Echarts; preset [jiaminghi's DataV (a vue large-screen data display component library)](http://datav.jiaminghi.com/) (not Alibaba Cloud's data visualization solution, visible access The importance of the name), and dealt with its compatibility on ie; added full-screen components and adaptive wrapper components.

## Environmental dependence

```
"node": ">= 10.0.0",
"npm": ">= 5.6.0"

"Other versions are not tested yet"
```

## install

```
npm i v-template-cli -g
```

or

```
yarn global add v-template-cli
```

## use

### create a project

#### vt create

To create a new project, run:

```
vt create hello-world
```

Choose the template you want to pull：

![Choose the template you want to pull](https://github.com/lyhmyd1211/pictures/blob/master/cli1.png?raw=true)

Choose whether to install dependencies immediately：

![Choose whether to install dependencies immediately](https://github.com/lyhmyd1211/pictures/blob/master/cli2.png?raw=true)

After the installation is complete, enter the directory and start the project：

![After the installation is complete, enter the directory and start the project](https://github.com/lyhmyd1211/pictures/blob/master/cli3.png?raw=true)

When the file name is repeated and you want to create the template again, you can choose whether to overwrite the original folder：

![Choose whether to overwrite the original folder](https://github.com/lyhmyd1211/pictures/blob/master/cli4.png?raw=true)

## Browsers support

Modern browsers and Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IE10, IE11, Edge                                                                                                                                                                                                | last 2 versions                                                                                                                                                                                                   | last 2 versions                                                                                                                                                                                               | last 2 versions                                                                                                                                                                                               |

## License

[MIT](https://github.com/PanJiaChen/vue-admin-template/blob/master/LICENSE) license.

Copyright (c) 2020-present LuYingHeng
