# ThreeUniDemo
uni-app 的 APP 端导入外部 3d 模型

概述
使用 uni-app 框架开发 APP，需要导入外部 3d 模型。就参考这个插件，就写了这个可以导入外部 3D 模型的案例。

此 demo 只适用于 APP 和 H5.

使用技术
使用 uni-app 开发 APP 导入外部模型，用到 renderjs，以及 Threejs 技术。

详细文档：

renderjs：https://uniapp.dcloud.io/frame?id=renderjs

Threejs：http://www.yanhuangxueyuan.com/threejs/docs/index.html

步骤
1.下载源码
先从 GitHub 上面下载 threejs 源码

源码链接：https://github.com/mrdoob/three.js

2.导入文件
把整个 threejs 源码放入创建好的 uni-app 项目的 static 文件夹里，如下图


3.代码功能
（1）打开 index.vue 文件，在 标签里加上如下代码，这里是 3d 模型在页面上展示的位置

（2）使用 renderjs 在 js 代码里，在

（3）导入 threejs 文件，以及 OrbitControls 和 GLTFLoader 文件

OrbitControls：是对 Threejs 的三维场景进行缩放、平移、旋转操作

GLTFLoader：导入 glb 格式模型，若要导入其他格式模型，可尝试在 loaders 目录下加载其他文件，点击查看其它文件

（5）接下来就是创建场景，导入模型以及渲染了

