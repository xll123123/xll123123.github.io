# 个人简历

## 联系方式

- Email：<ethanschen@163.com>
- 微信号：ethanschen

## 个人信息

- 陈亿强/男/1998
- 本科/福建农林大学软件工程系
- 工作年限: 5年
- 技术博客: <https://ethanschen.github.io>
- Github: <http://github.com/ethanschen>
- 期望岗位: 系统架构师
- 期望薪资: 税前月薪20k～25k
- 期望城市: 杭州

## 工作经历

### 华为云

#### OpenStack 云原生化项目

> - 经验与成果：参与`OpenStack`云原生化项目，成功将`CPS`（华为基于`OpenStack`开发的扩展服务）容器化，并基于`CPS`镜像完成`KeyStone`、`Wrap-Trigger`组件容器化并顺利部署`Kubernetes`集群，接入原`OpenStack`承载流量，为整体OpenStack云原生化荡平阻碍。
> - 职责和贡献：作为项目的核心开发人员，负责持续同步CPS新特性与漏洞修复并打包为镜像进行发布（供其他服务，如`Nova`、`Cinder`、`Neutron`基于此构建服务容器化镜像);并在`KeyStone`与`Wrap-Trigger`容器化过程中编写最佳实践文档，极大提高其他服务的组件容器化效率。
> - 其他经验：完成`Java`与`Python`的`Promethues`自定义监控对接;完成`Kuberhealthy`（巡检`Kubernetes`集群功能）对接;熟练使用`Docker`、`Kubernetes`。

#### RabbitMQ 技术支撑及漏洞修复

> - 经验与成果：保障22年版本升级平稳完成；保障3场公有云站点容灾演练平稳完成；响应10余起生产环境紧急事故，阻止影响恶化;处理数十个测试环境问题，保证漏洞及时发现及修复
> - 职责和贡献：作为开发人员，定位`RabbitMQ`脑裂严重`Bug`并修复，定位`Oslo-Messaging`（`RabbitMQ`客户端）消费消息卡住严重`Bug`并修复；作为责任田主，负责`RabbitMQ`的迭代演进，完成切`Pulsar`的`POC`项目，负责测试及生产环境的问题支撑，保障生产流程有序进行
> - 其他经验：熟练掌握`Linux`的常用定位工具（例如`find`、`grep`、`awk`、`sed`、`ps`、`top`、`lsof`、`netstat`）；熟练掌握`Pdb`调试工具；熟练掌握`Ansible`、`Jekins`。

### 福链科技

#### 区块链存证平台

> - 经验与成果：参与区块链存证平台的预研、设计、开发与交付的产品全流程，作为一款`To B`商用系统，已顺利交付三套，后续订单跟进中
> - 职责和贡献：作为项目的开发人员，研究实现数据生产者模块，通过全量同步与增量订阅结合的方式将`MySQL`、`Oracle`、`SQL Server`、文件目录中的数据发送至`RocketMQ`；设计与实现数据消费者模块，完成数据在区块链与`ElasticSearch`的并行存证；
> - 其他经验：熟悉`Tomcat`服务器的应用部署；熟悉`Nginx`代理、反向代理、限流、健康度检查与缓存；熟悉`Samba`文件服务

## 其它作品

### 开源项目

#### [prometheus/client_python] 4k stars

23年7月，公司出于安全因素需要exporter支持HTTPS/TLS，在确认社区未支持该特性后，首先通过patch的方式实现该功能，保障项目按时交付;再利用业余时间提交[PR]到社区，经过与社区核心成员的73次讨论、更新9次代码、耗时4个月将该特性合并到主干;因为该重要特性的合入，社区专门发布了[0.19.0]版本;也因为该特性的合入，下游项目IBM ZHMC Exporter维护者特意发感谢邮件致谢。

### 技术文章

#### 算法

- [一致性Hash算法与虚拟节点]
- [我在Dubbo源码里学到了如何保证虚拟节点均匀分布]
- [待补充一篇] 翻译
  
#### 迁移学习

- [基于F3Net显著性目标检测的蝴蝶图像前背景自动分割] 论文

#### Web3

- [Hello Solidity] 小册

#### K8S

- [一种kubernetes跨版本平滑升级方案] 专利 审核中

## 技术栈

熟练的使用(每周都用)

- 开发语言: Python
- 版本管理: Git
- 持续集成: Jenkins
- 单元测试: UnitTest
- 操作系统: CentOS(HCE)
- 口云原生: Kubernetes

广泛的了解(做过项目)

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

感谢您花时间阅读我的简历，期待能有机会和您共事。

[基于F3Net显著性目标检测的蝴蝶图像前背景自动分割]: http://www.insect.org.cn/CN/10.16380/j.kcxb.2021.05.008
[prometheus/client_python]: https://github.com/prometheus/client_python
[PR]: https://github.com/prometheus/client_python/pull/946
[0.19.0]: https://pypi.org/project/prometheus-client/0.19.0
[一致性Hash算法与虚拟节点]: https://blog.csdn.net/Eazon_chan/article/details/117576686
[我在Dubbo源码里学到了如何保证虚拟节点均匀分布]: https://blog.csdn.net/Eazon_chan/article/details/117888489
[Hello Solidity]: https://ethanschen.github.io/solidity
