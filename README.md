# DemoAddress
移动端观看效果最佳：
http://www.zenoslin.cn/sell

# How to start
```
git clone
npm install
npm run dev
```

# How to build on server
vue项目部署之前需要先配置好webpack打包的css和js路径，否则打包后会出现资源无法引入的空白页。因为项目中用json文件作模拟数据需要使用node.js,先写好文件prod.server.js。
```
npm install
npm run build
node prod.server.js
```
# Schedule
进度记录
```
>2018.04.11 部署vue项目到服务器上
>2018.04.07 完成商家页面和评论页面
>2018.04.06 完成评论组件，商品详情页
>2018.04.05 完成购物车组件
>2018.04.04 完成商家活动&公告页；商品列表组件
>2018.04.03 完成文件骨架搭建；商品页面中商家头部组件；
```

# Function
- [x] 商家头部组件
- [x] 商家活动&公告页
- [x] 商品列表组件
- [x] 商家页面
- [x] 评论页面
- [x] 购物车
- [x] 商品详情
- [x] 商品评论

# Time
```
> Complete.at 2018.04.07
> Start.at 2018.04.03
```

# Purpose
- 使用Vue-cli快速开发一个WebApp
- 来熟悉并锻炼Vue.js的使用
- 以及webpack的使用
- 同时尝试使用ES6的语法进行开发。

# About
这是一个用Vue.js写的简单型外卖WebApp.
