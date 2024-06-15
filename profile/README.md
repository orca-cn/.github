# 🐳 虎鲸云直播


# 👏 项目立项
- Orca 是为了在 私域下，历史的均是社群模式，当前直播火爆场景下，而为了在私域下引入直播方案而立项。 简单概述：虎鲸云是 企业私域直播的开源解决方案

# 🏠 项目开源组件列表


## 前端组件
> orca-admin       运营管理端（Web模式）

> assis-client     助播端（Web模式）

> anchor-client    主播端（Web模式开播）

> audience-client  观看端（H5模式）

> ......           主播端 (客户端)


## 后端组件

> living             [主项目]直播
  ``` 
  .github/workflows         CI/CD
  deploy                    部署 Dockerfile、docker-compose文件 或 K8S Deployment 文件
  doc/sql                   SQL与MARKDOWN文档
  
  living-common             
  living-beans
  
  living-web-adapater       Web端适配层
  living-web-org-adapter    企业端Web适配层
  living-logging-adapter    日志适配层
  living-dubbo-adapter      Dubbo 配置适配层
  
  living-seq-api            序列 Dubbo Api包
  living-core-api           核心 Dubbo Api包
  living-core-provider      核心 Dubbo Provider 服务
  living-seq-provider       序列 Dubbo Provider 服务

  living-core-dao           核心 Dao 层
  
  living-boss               开通管理端API服务
  living-admin              运营管理端API服务
  living-console            助播端、主播端API服务
  living-sharing            观看端API服务
  living-short              短域名服务
  living-task               分布式任务服务调度服务

  ```     

> grab-push        [基础服务]伪直播推流服务

> fire-sio         [基础服务]IM服务

> draw-sio         [基础服务]白板服务

## 运维

> orca-deploy      项目部署与基建


# 项目技术栈

> Vue、React、TypeScript、Electorn

> Java、Python、SpringBoot、Dubbo、Netty、

> Redis、MongoDB、MySQL、Pulsar、Nacos、Zookeeper

> FFmpeg、Electorn、SocketIO

> K8S、Docker、Docker-Compose、Rancher

> AliyunCloud、AWS、TencentCloud

> ...


