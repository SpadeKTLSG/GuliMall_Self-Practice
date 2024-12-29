# GuliMall_Self-Practice

从大佬拷过来的谷里源码学习

前台商城系统包括：用户登录、注册、商品搜索、商品详情、购物车、订单、秒杀活动等模块。后台管理系统包括：系统管理、商品系统、优惠营销、库存系统、订单系统、用户系统、内容管理等七大模块（暂未完全实现）。

## 项目介绍

### 微服务架构

- mall-cart 购物车模块
- mall-common 公共依赖模块
- mall-coupon 优惠服务，包含秒杀场次、优惠券等
- mall-gateway 网关
- mall-member 会员服务
- mall-order 订单服务
- mall-product 商品服务
- mall-search 搜索服务，使用elasticsearch
- mall-seckill 秒杀服务
- mall-third-party 第三方服务-短信、OSS
- mall-ware 库存服务
- mall-authentication 权限模块，目前只针对登录
- renren-fast 商城后台的后端系统
- renren-generator 后端增删改查生成模块
- 前端他人实现内容

### 技术选型

#### 后端技术

| 技术                 | 说明           | 官网                                                    |
|--------------------|--------------|-------------------------------------------------------|
| SpringBoot         | 容器+MVC框架     | https://spring.io/projects/spring-boot                |
| SpringCloud        | 微服务架构        | https://spring.io/projects/spring-cloud               |
| SpringCloudAlibaba | 一系列组件        | https://spring.io/projects/spring-cloud-alibaba       |
| MyBatis-Plus       | ORM框架        | [https://mp.baomidou.com](https://mp.baomidou.com/)   |
| renren-generator   | 人人开源项目的代码生成器 | https://gitee.com/renrenio/renren-generator           |
| Elasticsearch      | 搜索引擎         | https://github.com/elastic/elasticsearch              |
| RabbitMQ           | 消息队列         | [https://www.rabbitmq.com](https://www.rabbitmq.com/) |
| Springsession      | 分布式缓存        | https://projects.spring.io/spring-session             |
| Redisson           | 分布式锁         | https://github.com/redisson/redisson                  |
| Docker             | 应用容器引擎       | [https://www.docker.com](https://www.docker.com/)     |
| OSS                | 对象云存储        | https://github.com/aliyun/aliyun-oss-java-sdk         |

#### 前端技术

| 技术        | 说明     | 官网                                                      |
|-----------|--------|---------------------------------------------------------|
| Vue       | 前端框架   | [https://vuejs.org](https://vuejs.org/)                 |
| Element   | 前端UI框架 | [https://element.eleme.io](https://element.eleme.io/)   |
| thymeleaf | 模板引擎   | [https://www.thymeleaf.org](https://www.thymeleaf.org/) |
| node.js   | 服务端的js | https://nodejs.org/en                                   |

#### 开发工具

| 工具           | 说明           | 官网                                                      |
|--------------|--------------|---------------------------------------------------------|
| InteliJ IDEA | 开发Java程序     | https://www.jetbrains.com/idea/download                 |
| RDM          | redis客户端连接工具 | https://redisdesktop.com/download                       |
| SwitchHosts  | 本地host管理     | https://oldj.github.io/SwitchHosts                      |
| Termius      | Linux远程连接工具  | http://www.netsarang.com/download/software.html         |
| Navicat      | 数据库连接工具      | http://www.formysql.com/xiazai.html                     |
| Postman      | API接口调试工具    | [https://www.postman.com](https://www.postman.com/)     |
| Jmeter       | 性能压测工具       | [https://jmeter.apache.org](https://jmeter.apache.org/) |
| Typora       | Markdown编辑器  | [https://typora.io](https://typora.io/)                 |

#### 开发环境

纯docker云服务器部署

| 工具            | 版本号    | 下载                                                                         |
|---------------|--------|----------------------------------------------------------------------------|
| JDK           | 1.8    | https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html |
| Mysql         | 8.0    | [https://www.mysql.com](https://www.mysql.com/)                            |
| Redis         | Redis  | https://redis.io/download                                                  |
| Elasticsearch | 7.17.0 | https://www.elastic.co/downloads                                           |
| Kibana        | 7.17.0 | https://www.elastic.co/cn/kibana                                           |
| RabbitMQ      | 3.9.11 | http://www.rabbitmq.com/download.html                                      |
| Nginx         | 1.20.2 | http://nginx.org/en/download.html                                          |
