---
layout: cv
title: coder
email:
  url: mailto:yuancodelab@gmail.com
  text: yuancodelab@gmail.com
homepage:
  url: https://github.com/javaCodeLab
  text: JavaCodeLab
phone: 18927470422
---

# 元

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}


## 工作经历
### **深圳中顺易金融服务有限公司** `2015.9 - 现在`

_基础平台 - 高级软件工程师、研发经理、架构师_<br>
负责基础平台的技术选型与开发，主导研发的平台与系统，包括快速开发平台、工作流平台、日志平台、运营平台、开放平台、调度、监控、协议、消息通知、单点登入、权限模块、大数据报表查询、自动部署平台等。引入框架与技术包括Activiti、Camunda、Quartz、Xxl-Job、Minio、Pinpoint、SpringBoot Alibaba全家桶、Mybatis-Plus、ElasticSearch、Logstash、Kibana、Datax、Canal、Aspose、Cdp4j、Swagger、Druid、ApiSix等。
调研过的领域，包括数据交换（Camel、Spring Integration、Roma Connect、腾讯轻联），数据库（达梦、OceanBase），BI（FineBI、润乾、Tableau、CBoard、网易有数），许可证（TrueLicense、License3j），代码混淆（ProGuard、Allatori），字节码编程（Jclasslib、Javassist）等。
带过团队开发项目，其中带领10+团队3年以上。

### **平安科技** `2014.3 - 2015.4`

_产险项目组 - 软件工程师_<br>
主要参与车险合作伙伴项目的开发。在此期间，主要学习并掌握了Oracle存储过程开发，Oracle亿级数据调优，AngularJs前端开发等。接触了敏捷开发模式。


### **比亚迪汽车工业有限公司** `2010.10 - 2014.3`

_技术中心ERP项目组 - 软件工程师_<br>
主要参与比亚迪集团ERP系统的二次开发。技能提升，框架包括Spring全家桶、Hibernate、Mybatis，数据库主要掌握Oracle Sql的语法规则，前端掌握Html、JavaScript、CSS、Jquery、EasyUI、ExtJs等前端技术与框架。除了技术能力提升之外，提升了和集团各部门需求对接与分析的能力。

### **中科天翔（杭州）科技有限公司** `2009.2 - 2010.4`

_技术部 - 软件工程师_<br>
参与财政行业应用软件产品的研发。技能掌握，Java基础、Html、JavaScript、Css，框架包括Strusts、Hibernate，开始接触Oracle数据库的Sql编写，存储过程的调试。参与过客户现场需求调研与开发，异地封闭开发。

## 技能

### 基础知识
- 熟练掌握Java，多线程，网络等基础知识，掌握JVM调优
- 熟练掌握框架Spring全家桶、SpringBoot Alibaba全家桶、Mybatis、Mybatis-Plus
- 熟练掌握工作流框架Activiti、Camunda，调度框架Quartz
- 掌握中间件Redis、RabbitMq、Minio
- 系统读过源码，包括Spring、SpringMvc、Mybatis、Dubbo、Zookeeper、Tomcat等
- 掌握Nginx、Docker、K8s
- 掌握Oracle、Mysql数据库的开发和Sql调优
- 掌握Html、JavaScript、Css、Jquery、Extjs、
AngularJs开发，阅读过基于Vue框架的代码，
能参与前端技术方案讨论
- 掌握字节码开发，掌握代码混淆技术

### 架构设计与需求分析
- 擅长分析需求与设计系统，能基于需求选择合适的技术方案
- 能独立带领团队开发技术平台和项目
- 擅长基于开源框架和开源项目进行定制化开发

### 工具
- 掌握工具Idea、Eclipse、Maven、Git、Markdown、Xshell、Arthas、Axure等


## 项目经验

### 工作流平台 `2023 - 现在` <br>
- 后端框架基于SpringBoot、Camunda、Dubbo、Mybatis、Mybatis-Plus，前端框架基于Vue2.0
- 一个通用的可独立可嵌入部署的工作流平台，支持中国式工作流，支持微服务架构，支持与其他系统模块快速对接
- 负责需求、产品设计、技术选型、核心功能设计开发，带领团队技术问题公关， 把握项目研发进度
- 目前已在客户方部署联调，已支持客户80+金融业务流程，计划明年1月正式上线

### 快速开发平台 `2019 - 2021` <br>
- 采用前后端分离架构，其中前端主要是基于vue框架，结合公司金融业务，进行扩展和封装，使之更适配公司业务，并且支持在线设计页面，可实现在页面拖拽生成页面；后端框架主要是基于Spring，对常用的中间件进行了封装，并且封装了数据访问层;
- 已将系统中常用业务模块包装成组件，新对接的系统，可以随意组装，目前已封装的组件比如流程引擎平台、单点登入、导入导出、大表归档、对账、操作日志、系统监控、轻量级调度、监控预警平台等，这些组件可独立运行，也可集成到新系统中;
- 负责需求、产品设计、框架设计、核心功能设计开发，带领团队技术问题公关，把握项目研发进度;
- 目前已支撑公司所有部署在客户方的信托管理系统，已部署的系统20+，例如，在19年11月底，一个评估100人天左右的仓管项目，在基于快速开发平台开发后，缩短为实际只花30人天左右的工作量，并且在12.26号上线稳定运行。在可靠性、可伸缩性、可移植性和可用性上面得到了实际的检验 。

---

## 拥有解决方案的领域 

- 工作流
- 调度
- 权限
- 单点登入
- 部署平台
- 协议
- 消息通知
- 网关
- 开放平台
- 系统集成
- 规则引擎
- 监控
- BI报表


## 教育

### **江苏师范大学** `2005.9 - 2009.6`


- 计算机科学与技术专业
- 参加全国计算机应用水平考试，并获得高级软件工程师(JAVA)证书


## 我能做什么

基于业务快速搭建技术平台 <br>
基于业务选择合适的技术，优化已有的框架和技术 <br>
基于公司现有技术体系，封装通用功能，降本增效 <br>
参与公司的开发流程与标准的建设 <br>
参与业务需求的分析与过滤，参与技术难题的公关 <br>
可独立带团队开发功能需求，指导和培养技术队伍 <br>

<!-- ### Footer

Last updated: Dec 2023 -->
