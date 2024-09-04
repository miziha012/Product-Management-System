### 项目名称
商品账单管理分析app

### 项目描述

### 项目目录结构
```
根目录/
├─ .hbuilderx/                  HBuilder x编辑器内部设置配置
├─ components/                  公共组件
├─ pages/                       app页面
│   ├─ data                     数据
│   ├─ index                    买卖
│   └─ user                     我的
├─ static/                      静态资源
│   ├─ css  
│   └─ images  
├─ store/                       vuex 全局状态管理
├─ unpackage/              
├─ utils/                       公共方法库
├─ .gitignore                   git配置
├─ App.vue                      应用配置，用来配置App全局样式以及监听
├─ index.html                   入口文件
├─ main.js                      Vue初始化入口文件
├─ manifest.json                配置应用名称、appid、logo、版本等打包信息
├─ pages.json                   配置页面路由、导航条、选项卡等页面类信息
├─ README.md                    项目描述文件
├─ uni.promisify.adaptor.js     Promise转换器
└─ uni.scss                     内置的常用样式变量

```

### 项目插件

### git提交流程
1.提交到暂存库  
`git add .`  

2.提交注释
`git commit -m "提交注释"`

3.拉取代码 防止冲突
`git pull`

4.提交到远程
`git push`

5.随后在github页面上将自己代码合并到master，再将master代码合并入自己分支

> 可以执行`git status`随时查看git状态和下一部需要执行的git指令

### 版本
> 版本编号规范: 
> 1(主版本号).0(次版本号).0(修订版本号)
> - 主版本号: 项目更新重大功能或不能向后兼容,递增主版本号.
> - 次版本号: 项目添加新功能但能向后兼容,递增次版本号.
> - 修订版本号: 项目进行向后兼容的bug修复或小幅度改进,递增修订版本号.

#### v1.0.0 (2024年09月04日)
- **开发人员**: 彭邵武
- **首次发布**: 初始版本