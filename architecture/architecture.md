### 关于架构
- 本项目的终极思想,高内聚,低耦合
- 项目应该是分布式,面向服务,不受编程语言的约束
- 使用同步或异步通讯方式
- 后端服务是无状态的,不涉及权限问题

### 技术选型
- 使用Python3作为主要开发语言
- kombu, zeromq, thrift通信

### 基础架构与服务
- 使用restful,thrift实现同步模型
- validators 使用定制的schema进行参数验证
- test 使用mock框架,进行单元测试
- 使用redis存储session数据

### 项目部署
- fabric