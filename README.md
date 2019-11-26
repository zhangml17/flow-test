# Flow
flow是JavaScript代码的静态类型检查的一个工具
## Install
```
npm i -g flow-bin
```
安装完执行flow命令发现报错:
```
Could not find a .flowconfig in . or any of its parent directories.
```
没关系，执行：
```
flow init
```
会自动生称.flowconfig配置文件

# Vue SourceCode
Vue.js源码是基于Rollup构建的，它的构建相关配置都在scripts目录下