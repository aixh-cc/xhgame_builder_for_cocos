# xhgame的cocos在线构建器

## 使用说明
注意这个是cocos的一个【插件】，使用前，需要你创建一个空的cocos3.x的空项目

- 第一步: 创建一个新cocos项目，项目->项目设置->长宽640,960

- 第二步: 在cocos项目根目录安装依赖`npm install @aixh-cc/xhgame_ec_framework`

- 第三步：将当前【插件】的放到`项目/extensions`下面,并也安装本插件的依赖`npm install`

- 第四步：`npm run dev:node` 启动后端服务

- 第五步：`npm run dev` 启动在线安装网页

- 第六步：点击安装所有插件



## 其他说明

选择游戏所用到的单位有哪些。当前共有6种单位模板可供选择：

   - 1、uiItem 普通的ui单位
   - 2、effectItem 特效item
   - 3、tiledItem 地板单位
   - 4、textUiItem 漂浮字item
   - 5、unitItem 游戏单位
   - 6、unitUiItem 单位跟随的ui（一般是血条）




## 其他安装说明
npm run build 打包成cocos的插件dist包

npm run build:web 打包成网页（后期如果组件都在线上安装可能会用到）

npm run build:node 后端服务打包（一般用不上）

## 体验
如果你不想使用构建器构建一步步构建，可以直接使用开源的框架demo 地址：https://github.com/aixh-cc/xhgame_demo
