# README
## 使用
1.将文件batch_create_prj.py和statments.py下载至能访问管理节点的机器上,置于同一目录下；<br>
2.执行命令`pyton batch_create_prj.py`
## 脚本中自定义变量
### 1.ZSTACK_MN
key|释义
--|:--:|
ip|管理节点IP
account|admin账号
passwd|dmin密码
### 2.project_retire_policy-项目回收策略
变量名|释义
--|:--:|
prj_retire_threshold|项目回收费用值
zone_name|项目所属区域
policy|回收策略

三种回收策略：

值|回收策略
---|:--:|
noLogin|禁止登录项目
stopRes|停止项目资源
deletePrj|删除项目
### 3.project_quota变量-UI配额 对照表
变量名|配额名
---|:--:|
vm.totalNum|云主机数量
vm.num|运行中云主机数量
vm.cpuNum|CPU数量
vm.memorySize|内存
gpu.num|GPU设备数量
affinitygroup.num|亲和组数量
snapshot.volume.num|云盘快照数量
volume.data.num|数据云盘数量
volume.capacity|可用存储容量
image.num|镜像数量
image.size|所有镜像容量
vxlan.num|VXLAN网络数量
l3.num|三层网络数量
securityGroup.num|安全组数量
vip.num|虚拟IP数量
eip.num|弹性IP数量
portForwarding.num|端口转发数量
loadBalancer.num|负载均衡器数量
listener.num|监听器数量
scheduler.num|定时任务数量
scheduler.trigger.num|定时器数量
zwatch.alarm.num|资源报警器
zwatch.event.num|事件报警器
sns.endpoint.num|接收端
tag2.tag.num|标签
