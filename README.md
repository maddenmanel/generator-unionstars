# generator-unionstars [![Build Status](https://travis-ci.org/unionstars/generator-unionstars.svg?branch=master)](https://travis-ci.org/unionstars/generator-unionstars)

A [Yeoman](http://yeoman.io) generator for scaffolding and bootstrapping [Spring Boot](http://projects.spring.io/spring-boot/) and [Spring Cloud](http://projects.spring.io/spring-cloud/) applications. Provides the same selectable options as [Spring Initializr](http://start.spring.io), but with and interactive CLI interface so your hands can stay where they belong, on the keyboard!

## 适用对象

减少工程创建时大量的重复工作、统一代码风格，提供开发样例、对maven仓库的依赖进行统一约束，并提供非springboot生态下的自研中间件的starter组件，以实现完整的开箱即用体验。

## 规范中默认约束的组件和版本

| 基础组件 | 版本           | 自研组件|版本|
|---|---|---|---|
|  spring-boot |2.1.7.RELEASE|  jsf |1.6.9|
|  jdk |1.8|||
|  lombok |1.18.8|||
|  gson |2.8.5|||



## 快速开始

**安装 Yeoman**

```
$ npm install -g yo
```

**安装 generator-unionstars**

```
$ npm install -g generator-unionstars
```

**初始化一个开箱即用的后端服务中心工程**

```
$ yo unionstars
```
_The interactive CLI menu will guide the way._


**初始化一个接口工程**

```
$ yo unionstars:api
```


**初始化一个前端网关工程**

```
$ yo unionstars:application
```

## TODO


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)



