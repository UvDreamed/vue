# Vuejs源码阅读
```shell
|-- Vuejs
  |-- .circleci
  |-- .github
  |-- benchmarks
  |-- dist
  |-- examples
  |-- flow
  |-- packages
  |-- script
  |-- src
      |-- compiler    //编译相关,包含所有编译相关的代码,包括把模板解析成ast语法树,ast语法树优化,代码生成等功能,编译的工作可以再构建时做(借助webpack,vue-loader等辅助插件),也可以在运行时做,使用包含构建功能的Vue.js
      |-- core        //核心代码,包括内置组件,全局API封装,Vue实例化,观察者,虚拟DOM,工具函数等等
      |-- platforms   //不同平台支持
      |-- server      //服务端渲染,这部分代码跑在Nodejs
      |-- sfc         //.vue文件解析,解析成JavaScript的对象
      |-- shared      //共享代码,定义的工具方法,这里定义的工具方法都是被浏览器端Vuejs和服务端Vue.js所共享
  |-- test
  |-- types
  |-- .babelrc.js
  |-- .editorconfig
  |-- .eslintignore
  |-- .eslintrc
  |-- .gitignore
  |-- BACKERS
  |-- LICENSE
  |-- package
  ```




