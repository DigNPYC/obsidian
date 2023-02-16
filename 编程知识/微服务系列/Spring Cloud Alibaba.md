[Spring Cloud Alibaba (antfin.com)](https://yuque.antfin.com/faw-tech/qahn1l/st9nqfs7on38k1y3)

# Spring Cloud Alibaba简介

  

Spring Cloud Alibaba 致力于提供微服务开发的一站式解决方案。此项目包含开发分布式应用微服务的必需组件，方便开发者通过 Spring Cloud 编程模型轻松使用这些组件来开发分布式应用服务。

依托 Spring Cloud Alibaba，您只需要添加一些注解和少量配置，就可以将 Spring Cloud 应用接入阿里微服务解决方案，通过阿里中间件来迅速搭建分布式应用系统。

官网地址：[https://spring.io/projects/spring-cloud-alibaba](https://spring.io/projects/spring-cloud-alibaba)

github项目地址：[https://github.com/alibaba/spring-cloud-alibaba](https://github.com/alibaba/spring-cloud-alibaba)

## 为什么选择 Spring Cloud Alibaba

  

Spring cloud alibaba在 Spring Cloud家族产品的一个套件，跟Netflix套件一样，涵盖了非常多的实用组件，其中很多跟Netflix一样，内容和功能存在重叠，那我们为什么放弃Netflix，转而选择Spring cloud alibaba呢，两个原因如下：

-   Spring Cloud NetFlix项目进入维护模式，维护模式意味着Spring Cloud团队将不再向改团队添加新功能，修复block级别的Bug以及安全问题，会考虑审查社区的小型pull requests，参考文档[https://spring.io/blog/2018/12/12/spring-cloud-greenwich-rc1-available-now](https://spring.io/blog/2018/12/12/spring-cloud-greenwich-rc1-available-now)
-   对于中国用户来说，spring cloud alibaba还有一个非常特殊的意义：他将红极一时的Dubbo，以及阿里巴巴强力消息中间件RocketMQ融入到spring cloud体系，同时spring cloud Alibaba中间件产品通过应对阿里的各种实际高并发场景，在实际案例中验证了足够优秀，值得信赖

![](https://intranetproxy.alipay.com/skylark/lark/0/2022/png/128606/1650808666712-aef11a7f-dd43-4a21-b7c6-d0f8429e3540.png)

## 主要功能

  

-   服务限流降级：默认支持 WebServlet、WebFlux, OpenFeign、RestTemplate、Spring Cloud Gateway, Zuul, Dubbo 和 RocketMQ 限流降级功能的接入，可以在运行时通过控制台实时修改限流降级规则，还支持查看限流降级 Metrics 监控。
-   服务注册与发现：适配 Spring Cloud 服务注册与发现标准，默认集成了 Ribbon 的支持。
-   分布式配置管理：支持分布式系统中的外部化配置，配置更改时自动刷新。
-   消息驱动能力：基于 Spring Cloud Stream 为微服务应用构建消息驱动能力。
-   分布式事务：使用 @GlobalTransactional 注解， 高效并且对业务零侵入地解决分布式事务问题。
-   阿里云对象存储：阿里云提供的海量、安全、低成本、高可靠的云存储服务。支持在任何应用、任何时间、任何地点存储和访问任意类型的数据。
-   分布式任务调度：提供秒级、精准、高可靠、高可用的定时（基于 Cron 表达式）任务调度服务。同时提供分布式的任务执行模型，如网格任务。网格任务支持海量子任务均匀分配到所有 Worker（schedulerx-client）上执行。
-   阿里云短信服务：覆盖全球的短信服务，友好、高效、智能的互联化通讯能力，帮助企业迅速搭建客户触达通道。

## 主要组件

  

-   Sentinel：把流量作为切入点，从流量控制、熔断降级、系统负载保护等多个维度保护服务的稳定性。
-   Nacos：一个更易于构建云原生应用的动态服务发现、配置管理和服务管理平台。
-   Seata：阿里巴巴开源产品，一个易于使用的高性能微服务分布式事务解决方案。
-   RocketMQ：一款开源的分布式消息系统，基于高可用分布式集群技术，提供低延时的、高可靠的消息发布与订阅服务。
-   Dubbo：Apache Dubbo™ 是一款高性能 Java RPC 框架。
-   Alibaba Cloud OSS: 阿里云对象存储服务（Object Storage Service，简称 OSS），是阿里云提供的海量、安全、低成本、高可靠的云存储服务。您可以在任何应用、任何时间、任何地点存储和访问任意类型的数据。
-   Alibaba Cloud SchedulerX: 阿里中间件团队开发的一款分布式任务调度产品，提供秒级、精准、高可靠、高可用的定时（基于 Cron 表达式）任务调度服务。
-   Alibaba Cloud SMS: 覆盖全球的短信服务，友好、高效、智能的互联化通讯能力，帮助企业迅速搭建客户触达通道。

## 版本说明

![[Pasted image 20230201094824.png]]

![[Pasted image 20230201094915.png]]

