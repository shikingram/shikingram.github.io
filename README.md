# 个人信息
- 姓名：石坤
- 出生年月：1997年1月
- 邮箱：kingram@163.com
- 电话：17625952168（同微信）
- Github: https://github.com/shikingram
- 职位：Golang开发工程师

# 技能清单
以下为主开发语言的技术栈
- Golang 是主要编程语言
- Gin 是主要Web开发框架
- 云原生知识结构，工具使用
	- docker、harbor、k8s、helm
	- devops流程
	- gitops流程
	- runner、pipeline 触发器
	- Prometheus监控
 	- ELK日志分析 
- 数据库
	- MySQL，熟练使用gorm
	- RabbitMQ、Redis缓存技术，在项目中可以熟练使用
- 其他工具
	- Git熟练使用
	- Make构建项目
	- PostMan使用、自动化测试脚本
	- Linux运维、 熟练掌握常见问题排查命令
	- ChatGPT

以下为掌握/了解语言的技术栈
- Java 有两年工作经验 
- Python可以读懂代码
- Elixer可以读懂代码，做过相关技术调研
- 简单智能合约

# 个人亮点
- 学习能力强，拥抱新技术、涉及技术面广，从写Java+前端出生，因工作机缘主编程语言转为Go、学习并使用K8s知识体系，学习Elixer、智能合约等技术
- 解决问题能力，有较强的责任感，以解决问题为目标动用一切资源能力、结果导向
- 快速上手项目、熟练丰富的工作项目经验，对新项目上手较快

# 工作经历
## 育儿网(Golang开发工程师)(2021年11月-2023年6月)
**K8SWorker项目**

worker项目的目的是简化用户部署资源到k8s集群过程，实现统一管理，同时监听资源状态、同步系统应用状态给用户

相关工作：
- 参与oam资源kubevela的兼容原生kubernetes落地
- 基于k8s client-go实现威胁巡检实时监听资源变化上报差异信息
- 基于区块链存证实现部署防篡改，数据库+k8s+链上三方校验（[专利号:**2022108564045**](https://cpquery.cponline.cnipa.gov.cn/detail/index?zhuanlisqh=2022108564045&anjianbh)）
- 监控指标改进适配prometheus
- 结合边缘节点支持边缘应用部署管理

**区块链项目组-后端开发**

参与startupdao与investmentdao项目后端服务开发   
dao应用是微服务架构，由多个服务、工具组合而成，前端使用低代码平台(GUI)组合下层服务实例，后端为调用链引用

相关工作：
- 负责应用层(startupdao)、业务服务层(项目、任务、自荐、众筹等)代码开发维护
- 参与投融资服务(investmentserver)设计工作(类图、E-R图、数据表、API)
- 实现链上链下权限互通，链上投票成功后链下分配
- 参与dao运营文案编辑，网站设计

**SOPA交付**

SOPA是一个需要使用Docker环境部署的项目，客户要求不使用K8S集群部署，同样是由多个服务组合的项目，包含40多个服务，因此我们开发了[ADCTL](https://github.com/shikingram/adctl)工具来协助部署

ADCTL是一个类似于HELM的一个管理Chart包的工具，针对底层不使用K8S编排而是Docker compose管理容器应用的场景

相关工作：
- 项目代码开发、调试
- 协助客户解决问题

## 感动科技(Golang开发工程师)(2019年9月-2021年11月)
**ETC支付网关 & 结算开放平台**

该项目对现有停车场系统进行软件+硬件改造，快速接入etc支付，结算开放平台对接联网中心且提供API对接第三方客户

主要工作如下：
- 实现集成协议、透传协议、在线密钥版本的网关产品开发迭代
- 完成加油站的 ETC 扣费网关设计、开发、接口对接、上线等工作
- 与捷顺、科拓、宁沪、中润、等合作公司软件技术对接
- 与金溢、万集、伟龙金溢等 RSU 厂商协议的对接适配
- 南通智慧城市项目的 ETC 追缴网关设计开发
- 南京站、禄口机场、扬州、滁州高铁站等停车场上线对接

## 华脉科技(Java开发工程师)(2017年12月-2019年8月)
**华脉光电 MES 系统**

MES系统是一个工厂的管理系统，包含OA（请假、排班、打卡、人事管理）、采购、设备管理、仓储管理、生产流程物料追踪等功能

主要工作如下：
- 驻场开发，车间系统问题收集
- 负责本纤染色流程、配纤流程、质检管理、仓库管理、开完工、排班、等等生产过程模块化开发

# 其他
**Kubevela PR**   
- [Feat: add Harbor webhook trigger](https://github.com/kubevela/kubevela/pull/3065)
- [Fix: Fix the inaccurate judgment of ready status](https://github.com/kubevela/kubevela/pull/3317)

**技术文章**   
- [kubeedge](http://kingram.top/posts/cloud_native/kubeedge/)
- [wadm oam模型设计](http://kingram.top/posts/wadm/wadm/)
