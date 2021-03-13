# DaoDao
## 简介
[DaoDao](https://firezr.github.io/MyDaoDao/)是一个基于vue.js和echarts.js的单页面记账应用。
项目采用了vue.js提供的组件化的开发方式, 采用 ts+装饰器 进行开发。项目应用了许多vue的特性, 包括slot插槽机制,组件通信等。

## 功能介绍
- 记账：金额，标签，备注，收入/支出
  - 管理标签：添加，删除， 修改
- 查看明细：收入/支出（具体到每月）
查看报告：总收入/支出（具体到每月），ECharts饼图
## 技术栈
Vue 2 + TypeScript + Vue Router + Vuex

## 项目运行
```
    git clone git@github.com:Firezr/daodao.git
    cd daodao
    npm install
    npm run serve
```

## 效果演示
[查看demo](https://firezr.github.io/MyDaoDao/) (建议使用chrome手机模式预览)  

#### 移动端可扫描下方二维码访问
![扫描二维码访问应用](./src/assets/qrcode.png)


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
