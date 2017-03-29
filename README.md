Aresgo
======
aresgo是一个快速开发go应用的高性能框架，你可以用她来开发一些Api、Web及其他的一些服务应用，她是一个RESTful的框架。她包含快速的Http实现、Url路由与转发、Redis的实现、Mysql的CURD实现、JSON和INI配置文件的读写，以及其他一些方法的使用。后续会继续将一些常用应用添加到框架中。


产品特点（Features）
-----------------

* 实现思路借鉴iris-go,beego等框架
* http实现封装了fasthttp，fasthttp的方法和实现可以直接使用
* mysql的实现封装了go-sql-driver，并作了CURD的扩展，同时考虑mysql的主从结构，可以通过配置文件进行主从配置，读写分离，从而使用更灵活更方便
* redis的实现封装garyburd/redigo，可以通过配置文件进行主从配置
* 配置文件管理（Json和ini）采用beego的框架方法

安装（Installation）
--------------------
使用“go get”命令：

>go get github.com/misgo/aresgo

用法（Usage）
-------------------

