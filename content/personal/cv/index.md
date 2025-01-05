+++
date = '1998-06-16T12:00:00+08:00'
draft = false
title = '个人简历'
+++
## 联系方式

- 邮箱：[ethanschen@163.com](mailto:ethanschen@163.com)
- 微信：[ethanschen](https://www.ethans.space/personal/wechat/)

## 求职信息

- 男/1998/本科/福建农林大学软件工程
- 工作年限: 5年
- 技术博客: [www.ethans.space](https://www.ethans.space)
- 期望岗位: 软件架构师
- 期望薪资: 税前月薪23k～25k
- 期望城市: 杭州、厦门

## 开源作品

- [prometheus/client_python](https://github.com/prometheus/client_python)

23年7月，公司出于安全因素需要exporter支持HTTPS/TLS，在确认社区未支持该特性后，首先通过patch的方式实现该功能，保障项目按时交付;再利用业余时间提交[PR](https://github.com/prometheus/client_python/pull/946)到社区，经过与社区核心成员的73次讨论、更新9次代码、耗时4个月将该特性合并到主干;因为该重要特性的合入，社区专门发布了[0.19.0](https://pypi.org/project/prometheus-client/0.19.0)版本;也因为该特性的合入，下游项目IBM ZHMC Exporter维护者特意发感谢邮件致谢。

- [一致性Hash算法与虚拟节点](https://www.ethans.space/tech/2021-06-05-consistent-hash/)
- [我在Dubbo源码里学到了如何保证虚拟节点均匀分布](https://www.ethans.space/tech/2021-06-13-virtual-nodes-distribution/)
- [基于F3Net显著性目标检测的蝴蝶图像前背景自动分割](http://www.insect.org.cn/CN/10.16380/j.kcxb.2021.05.008)
- [Hello Solidity 小册](https://ethanschen.github.io/solidity)

## 工作经历

### 华为云-OpenStack云原生化项目

- 经验与成果：参与OpenStack云原生化项目，成功将CPS（华为基于OpenStack开发的扩展服务）容器化，并基于CPS镜像完成KeyStone、Wrap-trigger组件容器化并顺利部署Kubernetes集群，接入原OpenStack承载流量，为整体OpenStack云原生化荡平阻碍。
- 职责和贡献：作为项目的核心开发人员，负责持续同步CPS新特性与漏洞修复并打包为镜像进行发布（供其他服务，如Nova、Cinder、Neutron基于此构建服务容器化镜像);并在KeyStone与Wrap-trigger容器化过程中编写最佳实践文档，极大提高其他服务的组件容器化效率。
- 其他经验：完成Java与Python的Promethues自定义监控对接;完成Kuberhealthy（巡检Kubernetes集群功能）对接;熟练使用Docker、Kubernetes。

### 华为云-RabbitMQ技术支撑及漏洞修复

- 经验与成果：保障22年版本升级平稳完成；保障3场公有云站点容灾演练平稳完成；响应10余起生产环境紧急事故，阻止影响恶化;处理数十个测试环境问题，保证漏洞及时发现及修复
- 职责和贡献：作为开发人员，定位RabbitMQ脑裂严重Bug并修复，定位Oslo-Messaging（RabbitMQ客户端）消费消息卡住严重Bug并修复；作为责任田主，负责RabbitMQ的迭代演进，完成切Pulsar的POC项目，负责测试及生产环境的问题支撑，保障生产流程有序进行
- 其他经验：熟练掌握Linux的常用定位工具（例如find、grep、awk、sed、ps、top、netstat）；熟练掌握pdb调试工具；熟练掌握Ansible、Jekins。

### 福链科技-区块链存证平台

- 经验与成果：参与区块链存证平台的预研、设计、开发与交付的产品全流程，作为一款To B商用系统，已顺利交付三套，后续订单跟进中
- 职责和贡献：作为项目的开发人员，研究实现数据生产者模块，通过全量同步与增量订阅结合的方式将MySQL、Oracle、SQL Server、文件目录中的数据发送至RocketMQ；设计与实现数据消费者模块，完成数据在区块链与ElasticSearch的并行存证；
- 其他经验：熟悉Tomcat服务器的应用部署；熟悉Nginx代理、反向代理、限流、健康度检查与缓存；熟悉Samba文件服务

## 技术栈

熟练使用(每周都用)

- 开发语言: Python
- 版本管理: Git
- 持续集成: Jenkins
- 单元测试: UnitTest
- 操作系统: CentOS(HCE)
- 口云原生: Kubernetes

广泛了解(做过项目)

- 后端框架: SprinBoot/Django
- 前端框架: Vue/Next.Js/Bootstrap
- 服务部署: Tomcat/Nginx
- 口中间件: RabbitMQ/Redis/Kafka/RocketMQ
- 口数据库: MySQL/SQLite/Oracle
- 终端开发: Android应用/IOS应用/微信小程序/微信公众号
- 游戏开发: C#/Unity3D
- 运维工具: Ansible
- 技术文档: Jupyter
- 数据处理: Matlab

## 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事~
