> 喜欢就Star，不只是Fork；

> 想要分享的动机才是驱动力，而技术仅仅是一种方法。

> 数据库文件已经上传，安装配置就可以使用

======================

# TP-Web(简称Web)

TP-Web即基于ThinkPHP5的web后台管理系统

## 官方文档
地址：[http://doc.web.shijinrong.cn/](http://doc.web.shijinrong.cn/)

## 在线体验
地址：[http://web.shijinrong.cn/admin/login](http://web.shijinrong.cn/admin/login) 

账户：13330613321

密码：123


## 线上仓库

在线地址：[https://github.com/Aierui/web](https://github.com/Aierui/web)

### 源代码下载

**git克隆**：``git clone https://github.com/Aierui/web`` 

**直接下载**：[https://github.com/Aierui/web/archive/master.zip](https://github.com/Aierui/web/archive/master.zip) 

## 本地部署

**运行环境要求**

> * PHP >= 5.4.0
> * PDO PHP Extension
> * MBstring PHP Extension
> * CURL PHP Extension



建议配置虚拟域名（若不清楚，请自行解决之），方便接下来开展你的开发工作。
> 按照TP5默认，入口文件位于`public/index.php`
> 入口文件位置的设计是为了让应用部署更安全，public目录为web可访问目录，其他的文件都可以放到非WEB访问目录下面。


除非
> 你是一名高级PHPer，也可以为每一个模块自定义入口文件


**部署完成后**

~~~
http://your-domain/ 例如虚拟域名配置为www.web.com 则http://www.web.com
~~~


**详细参考**[ThinkPHP5官方手册中的部署部分](http://www.kancloud.cn/manual/thinkphp5/129745)官方手册更加完善且很清楚

## 开发规范
tp-web-admin框架严格遵循ThinkPHP5开发规范，详情请参照[官方手册](http://www.kancloud.cn/manual/thinkphp5/118007)

# TP-Web——拿来即用高性能后台管理系统

TP-Web即基于ThinkPHP5的web后台管理系统

### 主要特性：

- **菜单管理**：自定义添加菜单，自动生成菜单节点
- **角色管理**：自定义后台各菜单各节点权限分配
- **账号管理**：平台后台账号统一管理，自定义分配角色
- **日志记录**：自动记录网站操作写入数据库
- **数据验证**：表单数据自动验证
- **基础封装**：后台基础类，如权限验证、实时登录等

- **[系统集成js](https://github.com/Aierui/web/blob/master/public/js/admin/main.js)**:初始化selector、空对象判断、重定向、modal、封装全局ajax请求、下载js、下载样式、表单验证、jquery扩展ajax提交表单、弹出提示信息alertMsg()、弹出确认提示框alertConfirm()等

- **[GridViewjs](https://github.com/Aierui/web/blob/master/public/js/admin/gridview.js)**:数据表格显示优化、表格数据初始化、关键词搜索、支持4种事件类型（1. 自定义 2.视图  3.默认 4.脚本）、视图事件支持3种新页面打开方式（1.**模态框**2.本页打开 3.在新窗口打开）

- **小特性，自己挖掘哦~~ 更多新特性、正在完善中……**
- **也期待有想法的你加入**

### 支持TP-web的用户请到 [GitHub](https://github.com/Aierui/web) 给我一个star ^_^

### 为什么要选择TP5
因为TP5在框架中就有如下高级特性
* * * * *

- **规范**：遵循PSR-2、PSR-4规范，Composer及单元测试支持；
- **严谨**：异常严谨的错误检测和安全机制，详细的日志信息，为你的开发保驾护航；
- **灵活**：减少核心依赖，扩展更灵活、方便，支持命令行指令扩展；
- **API友好**：出色的性能和REST支持、远程调试，更好的支持API开发；
- **高效**：惰性加载，及路由、配置和自动加载的缓存机制；
- **ORM**：重构的数据库、模型及关联，MongoDb支持；

### 合理使用轮子
排名部分先后顺序
- 框架：ThinkPHP5.0.2、jQuery3.1.0
- 插件：bootstrap3.3.0、bootstrap-table1.11.0、validate.js0.10.0、jstree3.1.1、font-awesome4.6.3
- 平台：Github
- ……

> 在此非常感谢各框架、插件、平台的支持


## 交流
- 大家可以在github上Issues
- 在[这个后台](http://web.shijinrong.cn/admin/)我增加了一个用户建议、也可以留言
- 欢迎提出bug、便于我接下来修改
- 若你还有足够的精力和时间，欢迎你也加入进来
- 邮箱：imland@outlook.com
- 微信：imland
