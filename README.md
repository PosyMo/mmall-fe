## 前言
商城网站前端项目，参照慕课实战课程的个人练习项目，学习者请至慕课网购买原版课程：[课程链接](http://coding.imooc.com/class/109.html)

### 技术栈
jQuery + hogan + webpack
#### 项目运行

```
$ git clone https://github.com/PosyMo/mmall-fe.git
$ npm install
$ npm run dev
```

## 说明
### 涉及的技术点
1. webpack搭建项目脚手架
2. ejs语法
3. hogan模板引擎
4. CommonJs模块化开发

## 效果演示
<img src="https://github.com/PosyMo/mmall-fe/blob/master/screenshots/effect.gif" width="800" height="380"/>

## 项目布局
```
.
├── src                                         // 源码目录
│   ├── image                                   // 图片资源
│   ├── page                                    // 对应页面逻辑
│   │   ├── common
│   │   │   ├── header
│   │   │   ├── nav
│   │   │   ├── nav-simple
│   │   │   ├── nav-side
│   │   │   ├── footer
│   │   │   ├── index.js
│   │   │   └── layout.css                      // css reset
│   │   ├── index
│   │   ├── list
│   │   ├── detail
│   │   ├── cart
│   │   ├── order-confirm
│   │   ├── order-list
│   │   ├── order-detail
│   │   ├── payment
│   │   ├── result
│   │   ├── user-center
│   │   ├── user-center-update
│   │   ├── user-login
│   │   ├── user-pass-reset
│   │   ├── user-pass-update
│   │   └── user-register
│   ├── service                                 // api请求相关
│   │   ├── cart-service.js                     // 购物车相关请求
│   │   ├── address-service.js                  // 收货地址相关请求
│   │   ├── order-service.js                    // 订单相关请求
│   │   ├── payment-service.js                  // 支付相关请求
│   │   ├── product-service.js                  // 支付相关请求
│   │   └── user-service.js                     // 商品相关请求
│   ├── util                                    // 通用工具类
│   └── view                                    // 页面入口
│       ├── layout                              // 页面通用部分
│       │   ├── header-common.html              // 头部meta标签
│       │   ├── header.html                     // 通用头部
│       │   ├── nav.html                        // nav栏
│       │   ├── nav-simple.html                 // nva简化版
│       │   ├── na-side.html                    // 侧导航栏
│       │   └── footer.html                     // 通用footer
│       ├── index.html                          // 首页
│       ├── list.html                           // 商品列表页
│       ├── detail.html                         // 商品详情页
│       ├── cart.html                           // 购物车页
│       ├── order-confirm.html                  // 确认订单页
│       ├── order-list.html                     // 订单列表页
│       ├── order-detail.html                   // 订单详情页
│       ├── payment.html                        // 订单支付页
│       ├── result.html                         // 操作结果页
│       ├── user-center.html                    // 个人中心页
│       ├── user-center-update.html             // 修改个人信息
│       ├── user-login.html                     // 用户登录页
│       ├── user-pass-reset.html                // 找回密码
│       ├── user-pass-update.html               // 修改密码
│       └── user-register.html                  // 用户注册
├── package.json                                // 项目依赖
├── webpack.config.js                           // webpack配置
.
```
