## Changlog

安装调整都将被记录载这个文件中.

### [5.1.3] - 2019-04-11

- 调整安装步骤,将镜像push调整到最后一步,避免镜像推送失败导致数据中心初始化失败
- 调整组件日志级别info
- 优化rbd-monitor参数
- 支持外部数据库

### [5.1.1] - 2019-03-21

- 升级rainbond版本至5.1.1

### [5.1.0] - 2019-03-14

#### 组件

- 升级docker版本至18.06
- 升级kubernetes版本至1.10.13
- 升级rainbond版本至5.1.0

#### 安装调整

- 新增部分端口探测
- 优化系统资源检查(内存,CPU,硬盘)
- 优化初始化数据中心数据库方式
- 调整calico网络节点默认主机名为当前节点Uid
- 优化检测本地镜像是否存在方式
- 存储支持nas,gfs
- 优化nfs存储健康检查机制