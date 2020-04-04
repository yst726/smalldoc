## 项目
一个基于Java标准注释的 RESTful API 文档生成及测试工具。

## 为什么要造轮子？
- 强迫症患者，接受不了 **Swagger** 的各式注解对代码的入侵造成的冗杂，更渴望清洁的代码；
- 注解的使用需要一定的学习成本；
- 随后尝试使用 **Apidoc** ，尽管Apidoc是基于注释生成文档，但是学习成本并没有降低，你需要学习额外的注释 **Tag** ，同时你不得不使用这些特殊的 **Tag** 将你所需接口的相关信息手动写出来，感觉并没有降低书写文档的工作量；
- 也有一些基于Java标准注释生成文档的项目，但是有的无法支持`实体参数`、`泛型变量`，无法支持`多模块`、`第三方依赖`及`微服务文档集成`；有的Bug太多，UI界面不够友好；有的使用方式过于复杂（需要依赖Maven插件和繁琐的配置），甚至逻辑处理上存在问题。
- 如果一个API文档同时集成了类PostMan的测试功能，一锤搞定，不用在`API文档`和`PostMan或RestClient之类的测试工具`间频繁切换，难道不香吗？

## 特性[*详情可见*](https://github.com/liuhuagui/smalldoc/wiki/Features)
- 提供了`smalldoc-spring-boot-starter`及规范配置，让你在`spring-boot`项目中快速集成文档工具
- 基于Java源码、标准注释以及Tag生成文档，无代码入侵，保证代码清洁
- 包含大量的注释检查断言，保证开发人员的注释习惯与注释规范
- 强大的参数配置语法，满足开发者对参数展示的各种要求
- 支持实体参数，泛型字段，集合字段，关联实体等复杂参数的自动解析
- 支持忽略解析指定包或指定类型参数的数据结构
- 可配置的解析类名，支持正则匹配
- 支持多模块及第三方依赖
- 支持微服务文档集成
- 对UNIX系统做了兼容
- 支持接口参数示例值推断
- 集成了API测试功能
- 提供了友好的默认UI，支持离线文档生成；
- 提供了文档RESTEful API，支持实现自定义UI；

## 文档
[documention](https://github.com/liuhuagui/smalldoc/wiki/)

## 快速使用
[quick start](https://github.com/liuhuagui/smalldoc/wiki/Quick-Start)