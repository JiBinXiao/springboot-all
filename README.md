# 基于SpringBoot的一些通用框架集成，实现分布式web后端应用
springboot+dubbo+zk+mybatis+redis<br>
实现用户管理功能
***
## 初步实现功能
* 集成dubbo+zk分布式应用搭建
* 集成一些常用的工具包，如StringUtils等
* 构建一些通用类
* 集成mybatis，搭建druid连接池
* 集成redis实现数据缓存
* 使用shiro实现分布式登录控制
* 使用aspect实现切面日志记录
* 使用filter实现request参数加密和response返回结果加密
* 使用filter实现非法参数拦截

***
## 更新日志

* 2019.02.25<br>
maven上 SpringBoot+dubbo+zk项目初始化
* 2019.02.27<br>
集成mybatis框架和mybatis-generator插件
* 2019.02.28<br>
新增Lombok依赖
* 2019.03.06<br>
新增druid连接池<br>
新增数据库多数据源配置
* 2020.03.26<br>
集成swagger2在线文档
统一api返回格式RtnResult<br>
新增自定义消息转换器 将null->""<br>
添加防止XSS攻击功能<br>
使用aspect实现切面日志记录<br>
***
## 如何搭建环境参考文章<br>
[一.zookeeper安装-linux环境下](https://blog.csdn.net/weixin_33805152/article/details/87916409?_blank)<br>
[二.SpringBoot+Dubbo整合入门Demo](https://blog.csdn.net/weixin_33805152/article/details/87919394?_blank)<br>
[三.SpringBoot+Mybatis集成入门Demo（Mybatis-Generator插件集成）](https://blog.csdn.net/weixin_33805152/article/details/87978315?_blank)<br>
[Lombok 介绍(转)](https://blog.csdn.net/weixin_33805152/article/details/88035898?_blank)<br>
[Springboot框架自定义消息转换器](https://www.cnblogs.com/mrBeany/p/10649552.html)<br>
[Springboot框架添加防止XSS攻击功能](https://www.cnblogs.com/mrBeany/p/10649853.html)<br>


