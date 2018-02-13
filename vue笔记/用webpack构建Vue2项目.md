# 用webpack一步步构建Vue2项目 

参考：https://www.tech1024.cn/original/2948.html

## 创建项目## 如果使用cnpm，将npm替换成cnpm即可。

```
## 全局安装 vue-cli

npm install --global vue-cli

## 创建一个基于 webpack 模板的新项目，my-project为项目目录名称

vue init webpack my-project

## 接着会提示一些选项，根据自己的需求填写或选择y/n
## 项目名称
? Project name (my-project)? Project name my-project
## 项目描述
? Project description (A Vue.js project)? Project description A Vue.js project
## 项目作者
? Author (techlee <xxx@xxx.com>) 
? Author xxx@xxx.com
? Vue build standalone
## 是否安装vue-router路由，这里选是
? Install vue-router? (Y/n) y
? Install vue-router? Yes
## 是否需要ESLint代码检查，这里选否
? Use ESLint to lint your code? (Y/n) n
? Use ESLint to lint your code? No
## 是否需要unit单元测试，这里选否
? Setup unit tests with Karma + Mocha? (Y/n) n
? Setup unit tests with Karma + Mocha? No
## 是否需要e2e，这里选否
? Setup e2e tests with Nightwatch? (Y/n) n
? Setup e2e tests with Nightwatch? No
```

## 安装相关依赖

```
## 走你
 
## 切换到项目目录
cd my-project

## 使用npm安装依赖
npm install

## 运行项目
npm run dev
```


## 大功告成

```
如果没有报错，则会自动打开 http://localhost:8080/#/ ，到这里就项目就搭建好了。
```



