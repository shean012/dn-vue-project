#### 懂牛科技 vue 项目模版

##### 配置 webpack 打包方式，使其符合 cms 系统管理方式。

##### 图片必须通过 调用全局组件 Images 来展示。 并通过 src 参数传入图片的相对路径；

#### 安装依赖

> <code> npm install </code>

#### 启动项目

> <code> npm run dev </code>

### 注意事项：

1. 如果小于 10000 byte 的图片，会自动打包成 base64。 如果在 v-for 指令中使用 小于 10000 byte 的本地图片。 需要先 通过 import 导入成变量再使用。
