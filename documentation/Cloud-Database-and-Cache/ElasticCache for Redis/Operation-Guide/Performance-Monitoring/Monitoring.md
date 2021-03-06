# 性能监控
目前提供内存使用量、内存使用率、内网进出流量、QPS、命中率、实例key个数这六种监控类型：

1. 登录 [Redis 控制台](https://redis-console.jdcloud.com/redis) ，定位目标实例

2. 点击实例名称进入实例详情页面

3. 在上方导航Tab页中，选择监控

4. 选择监控时间进行查看

5. 右上角可设置报警规则，可点击进入云监控报警规则页面


## 监控项

- 内存使用量(MByte)：云缓存已用内存；

- 内存使用率(%)：云缓存已用内存与总内存的比率；

- 内网进出流量(kbps)：每秒通过内网流入、流出云缓存的流量；

- QPS(次/s)：每秒访问次数；

- 命中率(%)：请求命中缓存的概率；

- 实例key个数(个)：云缓存实例key目前的个数。

## 监控图

目前提供折线图展示，采样数据最小周期为1分钟，展示时长有最近1小时、6小时、12小时、1天、3天、7天和14天，还可自己选择日期范围；

如果想查看更加详细的监控指标数据，请在云监控菜单进行查看

![监控图](https://github.com/jdcloudcom/cn/tree/edit/image/Redis/monitoring.png)
