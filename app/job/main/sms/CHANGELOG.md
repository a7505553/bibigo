# sms项目的Job，用于发送短信

### 1.8.3
1. waitgroup

### 1.8.2
1. waitGroup.Done 按照规范移到外部

### v1.8.1
1. fix 云线路URL配置

### v1.8.0
1. 云线路和本地网络同时使用
2. 去除阿里SDK

### v1.7.2
1. 支持黑名单

### v1.7.1
1. fix log

### v1.7.0
1. 去掉db

### v1.6.0
1. 梦网使用新账号

### v1.5.0
1. use grpc

### v1.4.2
1. 修复创蓝回执时间

### v1.4.1
1. 完善兴企短信报告

### v1.4.0
1. 接入创蓝短信状态报告

### v1.3.3
1. 修复重启时 negative WaitGroup counter

### v1.3.1
1. 修复 send on closed channel panic when service down

### v1.3.0
1. 接入创蓝短信服务
2. 代码优化

### v1.2.0
1. 梦网内容转码失败报错
2. 切换到bm

### v1.1.6
1. 临时去掉阿里云

### v1.1.5
1. 批量推送时空号码不发

### v1.1.4
1. 迁移至main目录下

### v1.1.3
1. 修复批量短信走国际接口的问题

### v1.1.2
1. 将兴企和梦网sdk写成package


### v1.1.1
1. 加日志

### v1.1.0
1. 接阿里云短信服务

### v1.0.1
1. 修复XingQi发送国际短信失败的问题
2. add prom

### v1.0.0
1. 版本初始化
