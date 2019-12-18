## 个人信息
- 陈嘉伟/男/1997
- 毕业院校：广东工业大学/电子科学与技术
- 手机: 18588557892 / Email: jerrychaox8406@gmail.com
- 求职意向：Java开发工程师/服务端工程师

## 简介
**2020应届生**，有两年的互联网工作经验，以**技术负责人**身份带领**10-20人**的技术团队进行电商、点餐、支付类系统开发。本人的主要职责是负责核心系统核心模块的设计、开发、以及整体技术管理，从0到1，从1到2，整个闭环流程。

### 广州市墨锋信息科技有限公司(2017.9 ‒ 至今)
- 项目开发，负责**框架与组件**的选配及设计、模块的业务**职责划分**，**核心**模块的数据库设计把控、**线上杂难问题**定位。
- 技术管理，负责团队**技术人员**招聘与管理、**开发流程**规划及制定，以及开发**基础设施**建设，包括分支管理模式、持续集成方案、通用权限系统设计开发、代码分层设计。
- 项目管理，负责技术排期-研发-测试-验收-持续迭代整个**开发闭环管理**，与研发、设计、产品、运营**各部门沟通**，推动产品、需求优化落地。

## 项目经历

### 校园外卖购 (2019.02 ‒ 至今)

本系统为校园外卖提供线上运营的解决方案，支持多所学校和饭堂的入驻。业务上分为点餐、学生跑腿、营销三大板块，包含一元券、秒杀、抽奖等营销功能。目前日均交易流水达10W+，已入驻8所学校，几十余饭堂。

> 担任服务端优化，主要负责线上服务器高负载排查、性能优化，保证**高峰时段的可用性保障与整体性能**

- 利用**htop pidstat perf**等命令进行高峰期**CPU100%**负载分析，排查定位并分析具体问题。
- 优化**nginx+php-fpm**配置，最大化利用核心与内存资源，热点接口用swoole的**协程API**重写
- 针对慢SQL日志，Explain，优化联合索引编排，强制指定索引；排查**长事务**，进行小事务拆分；分析Gap Lock、死锁等**INNODB锁**问题。
- 对整个后端服务进行了容器化，利用阿里云-**Serverless Kubernetes**快速实现了负载均衡、滚动更新、自动伸缩（HPA）三大功能

### 聚合支付系统——支付服务SaaS化 (2017.9 ‒ 至今)

本系统主要为各软件系统提供**支付解决方案**，聚合了多个三方支付通道，提供交易、分账、资金清算管理后台，同时具备代理机制作为推广手段。
目前约有15个活跃商户，日交易流水约**15W+**。

> 担任后端开发，独立完成数据库设计、API设计、核心功能编码。

- 定义了通用的第三方 RPC 调用流程，统一订单类调用状态流转
- 利用了**RocketMQ**间接入库，优化核心下单逻辑**QPS**，配合**事务回查**机制保证数据一致性。
- 利用了**A/B**部署方案，实现不停机更新，可回滚的部署机制
- 利用面向对象设计了**服务层、渠道适配层、渠道 RPC 层**的架构来处理上游接口的异构性问题

## 技能清单
- 英语水平：CET6，英语文档阅读无障碍，英语口语沟通能力良好
- 开发语言：Java/PHP
- Sql/NoSql：MySQL/Redis/MongoDB
- 后端框架: Spring/SpringBoot
- 中间件: RocketMQ
- 容器云：docker/kubernetes
- 前端框架：Layui/Vue/Flutter
- 版本管理：Git
- CI：Jenkins/Drone
- 项目管理：Tower


## 自我评价
- 具备创业精神、极客精神，逻辑思维缜密，对技术充满热情，热衷探究对各类技术框架、中间件设计模式、原理。
- 擅长对软件系统进行宏观的复杂度分析，制定架构方案，能够科学地分析问题。
- 拥有极强的快速学习应用能力，知识体系构建能力、出色的沟通协作能力，良好的产品意识、以及一定的项目管理能力。
    
## 校园经历
- 担任广东工业大学2015届辩论队队长
- 担任广东工业大学材料与能源学院2015届队长及教练
- 担任学校创新创业孵化基地工作室核心成员
- 第四届“泰迪杯”全国大学生数学挖掘竞赛B题(高铁客流量)二等奖
- 2017年美国大学生数学建模竞赛B题二等奖
- 2018年美国大学生数学建模竞赛C题三等奖



