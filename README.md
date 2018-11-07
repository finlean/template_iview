# Vue 项目模板--PC 版

## 已有配置

1. `vue-router`：路由文件也进行了封装，具体请看`router文件`
1. `vuex`：Vue 的状态管理模式，具体请看`store文件`
1. `less`

## 未有配置

1. `PC端UI组件`，如有需要请自行安装
1. `接口验签`，后续开发中补上

## 已有插件

1. 封装了`$api`接口请求方法，可通过`this.$api.login()`调用，具体代码请看`api文件`
1. 封装了`$tool`工具方法，可通过`this.$tool.checkValEmpty()`调用。目前只包含`validator.js`里面的方法，之后可以自己往`$tool`中添加方法，具体代码请看`tool文件`
1. 封装了`$getItem,$setItem,$copy`三个常用方法，具体代码请看`main.js`

## 使用方式

1. 先安装纷领脚手架[finlean-cli](https://www.npmjs.com/package/finlean-cli)：`npm i -g finlean-cli`
1. `f -V`：查看版本号，确保安装成功
1. `f i`：根据提示，选择版本`pc`即可
