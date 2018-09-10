# 个人简历
[![NPM version](https://badge.fury.io/js/yangjunlong.png)](http://badge.fury.io/js/yangjunlong)
> There is only one heroism in the world：to see the world as it is and to love it.

## 自我介绍
> 热衷于软件开发行业，具有 7 年开发经验和 1 年实习经验，同时具备大型项目经验和项目管理经验。目前担任 Server Leader，具有良好的团队协作和沟通能力

## 个人信息
姓名：徐士宽

## 联系方式
邮箱：heixiushamao@gmail.com
职业：`高级软件开发工程师` · `新加坡`
<del>博客：[http://xxxxxx.com](http://xxxxxx.com)</del>
## 工作经历

### Mozat `Singapore`
> Server Leader `July 2017` ~ `Present`
```
主要负责对 Deja 项目的研发工作，搭建 Deja 平台在线购买架构，完成公司整体业务架构向微服务架
构的转换。完成部分业务的读写分离工作。完成公司基础服务从 Java 项目向 Golang 项目的转换工作。
完成 Golang 项目的 router 功能。
```
### 平安科技 `China`
> 高级软件开发工程师` May 2015`–`July 2017`
```
主要负责对知鸟移动学习平台的研发工作。平台主要实现随时随地高效员工培训，解决企业人才内训瓶
颈，帮助员工实现能力提升，助力企业业务发展。
```

### MPOS `China`
> 软件开发工程师 `December 2012`–`May 2015`
```
香港企业，前期主要是研发欧洲与非洲的彩票系统，开发各个彩票的不同玩法。后期企业转型，做 ToB
业务，独自封装了基于 Activiti 流程引擎的流程框架。
```

### 东软集团股份有限公司 `China`
> 软件开发工程师 `July 2010`–`December 2012`
```
在大四时进入东软实习，实习期间配合完成简单开发工作，毕业后直接入职东软-政府事业部-财政开发
部. 参与辽宁省，贵州省的非税收入收缴管理系统的客户现场调研工作，采集客户需求，并完成开发。
独自完成学校端子系统。
```

## 教育经历

 `2007` ~ `2011` [东北林业大学](https://www.nefu.edu.cn/) `信息管理与信息系统` 本科

## 项目经验

> Mozat

- Deja(Ongoing) `July 2017` ~ `Present`
  - [x] 相关技术: `Java`,`Golang`,`Spring Boot`,`String Cloud`,`JPA`,`Kafka`,`Redis`,`Elasticsearch`,`ELK`,`Consul`,`Docker`
  - [x] 完成 Deja 项目微服务架构设计
  - [x] 将核心业务向 Go 技术栈迁移
  - [x] Eureka 转换 Consul
  - [x] 通过 Kafka 异步方式同步数据（9000W），并上传 Elasticsearch
  - [x] 开发支付接口（对接 Stripe）
  - [x] 通过扫描收据图像识别客户购买服装
  - [x] 搭建 ELK，KAFKA，Redis，CI（Jenkins）环境（docker 方式 docker stack deploy）
  - [x] 引入 Spark 进行单元测试，形成标准化的软件代码和单元测试文档
  - [x] 标准化 AWS 权限
  - [x] 组织相关人员进行代码走读和单元测试，对发现的问题及时与系统设计及其他相关人员协商解决，并及时将走读及编译和单元测试通过的软件代码纳入配置管理
  - [x] 在整个项目生命周期过程中，维护软件程序，根据相关规范处理各种程序变更，修复后续测试中发现的任何程序缺陷，确保软件程序符合系统设计要求
  - [x] 从程序开发角度，协助所属项目或任务的系统设计，并参与其评审
  - [x] 指导开发工程师的工作并参与规范的开发


- go-router(Ongoing) `July 2017` ~ `Present`
  - [x] 相关技术: `Golang`,`Consul`,`Docker`
  - [x] 开发对 Golang 向 Consul 注册的封装工作
  - [x] 开发 Golang 项目健康检查接口
  - [x] 完成基于负载感知的数据流动态负载均衡策略
  - [x] 实现基于 Router 级别的熔断功能


> 平安科技

- 知鸟 `July 2017` ~ `Present`
  - [x] 相关技术: `Java`,`SpringMVC`,`Mybatis`,`KAFKA`,`Elasticsearch`,`Redis`
  - [x] 开发组织模块，对接平安集团组织数据，提供第三方企业上传组织数据接口，通过 KAFKA 实现异步同步功能。
  - [x] 开发课程模块，实现企业自定义课程维护。根据先关配置，自动同步到相关组件中
  - [x] 开发问券模块，实现企业自定义问券调查，并根据配置同步到相关组织中
  - [x] 开发考试模块，实现企业自定义考试功能，根据配置，同步到相关组织中
  - [x] 参与需求评审，根据需求完成设计并分配工作

> MPOS

- M.Lottery `July 2017` ~ `Present`
  - [x] 相关技术: `Java`,`Flex`,`Activiti`,`Hibernate`,`Redis`
  - [x] 开发彩票基础数据部分
  - [x] 开发彩票不同玩法 Lotto，IG，Toto，Raffle，5/90，Magic 100，Digit，Bingo，Lucky Draw，Pick3
  - [x] 开发彩票数据报表
  - [x] 根据录入派彩结果和相关配置，计算中奖人员名单并计算奖金
  - [x] 封装 Activiti 流程引擎，减少流程开发成本

> 东软

- 非税收入收缴管理系统 `July 2017` ~ `Present`
  - [x] 相关技术: `Java`,`SpringMVC`,`Mybatis`
  - [x] 开发财政基础数据模块
  - [x] 开发票据管理模块，实现财政厅对票据的印刷，入库，发放，销毁等管理
  - [x] 对接银行系统，实现执收单位开票后，银行顺利缴款操作
  - [x] 完成财政票据相关报表
  - [x] 完成学校端集中汇缴子系统，实现票据申请，入库，销毁，开票，报表查询，组织配置等功能

## 最后
如果你觉得我的简历还不错的话，通过支付宝打赏我

<img src="https://raw.githubusercontent.com/yangjunlong/resume/master/assets/weixin.jpg" alt="微信捐赠" title="微信捐赠" />

又或者，你跟我很熟？

<img src="https://raw.githubusercontent.com/yangjunlong/resume/master/assets/zhuang13.jpg" alt="简历求扩散" title="简历求扩散~" width="250px" />

那么，请`速扩散`此`简历`~

#### 彩蛋? :blush:
[前端面试题库](https://github.com/yangjunlong/resume/wiki)

## 致谢
谨在此向所有在我求职过程中帮助过我的小伙伴们表示感谢！

如果你对此简历有任何问题，欢迎提[issue](https://github.com/yangjunlong/resume/issues)。
