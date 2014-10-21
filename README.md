Drupal-7-Database-API
=====================

Drupal 7 数据库接口官网文档翻译

Drupal 7 数据库 API 为访问数据库服务器提供了一个标准化的，引擎无关的抽象层。API 被设计成尽可能的保留了SQL和语法和能力，同时还具有以下特性：

* 很容易地支持多个数据库服务器。
* 允许开发者使用更复杂的功能，例如事务。
* 为动态构建查询提供了一个结构化的接口。
* 强制安全检查以及其他一些最佳实践。
* 为第三方模块提供了简洁的接口拦截和修改网站的查询。

主要的数据库 API 文档是从代码注释自动生成的。而这个手册通过为想与数据库系统交互的模块开发者提供必要的指导信息扩展了这些 API 文档。而且本手册从管理员的视角也是对系统的一个综述。注意，本手册可能不会覆盖到 API 的所有特性。

数据库 API 是基于面向对象的设计理念构建的，本手册假设你对这些概念有部分了解。然而，大多数的操作都有一个面向过程的接口可以使用，开发者可以选择使用这些面向过程风格的接口以提高代码的可读性。
