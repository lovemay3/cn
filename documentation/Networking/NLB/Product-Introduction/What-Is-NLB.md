# 产品概述


网络负载均衡NLB是京东云提供的专注四层业务服务、支持千万级并发连接的高性能负载均衡产品。NLB可自动弹性伸缩、免除用户业务规划与手动升级的繁琐；NLB支持跨多可用区创建、并且与高可用组AG紧密配合，满足业务高可用部署需求；NLB计费除了最小资源保有费之外，完全按照用户实际使用流量进行计费，按用付费为用户提供最经济实用的服务使用方式。


网络负载均衡NLB具备以下特性：

* 高性能：支持千万级并发连接、百万？级新建连接。
* 高可靠：支持多可用区创建，后端服务可紧密配合高可用组AG的自动跨AZ、跨机架的容错域分配，实现业务自动高可用部署。
* 自动弹性伸缩：服务实例可根据业务情况自动调整，满足业务需求的同时降低使用成本。
* 后端丰富性：支持虚机、原生容器作为后端服务实例，为用户业务部署提供灵活选择。
* 源地址透传：NLB可完整透传用户源IP地址，便于服务端感知或者统计真实源端信息。

## 常用操作

- 创建NLB实例
	- [创建实例](../Getting-Started/Create-Instance.md)
	- [设置白名单](../Getting-Started/Set-Whitelist.md)
	- [连接实例](../Getting-Started/Connect-Instance.md)
- 创建服务实例资源（AG/虚拟服务器组）
	- [变更实例规格](../Operation-Guide/Instance-Management/Modify-Instance-Spec.md)
- 配置侦听策略（包括listener、backend）
	- [将数据导入到云](../Getting-Started/Import-Data.md)
	- [从云导出数据](../Getting-Started/Export-Data.md)
- 查看服务实例健康状态
	- [设置自动备份策略](../Operation-Guide/Backup/Modify-Backup-Policy.md)
	- [手动创建备份](../Operation-Guide/Backup/Create-Backup.md)
	- [数据恢复](../Operation-Guide/Backup/Restore-Instance.md)
- 运维管理
	- [查看监控信息](../Operation-Guide/Monitoring/Monitoring.md)
	- [设置报警规则](../Operation-Guide/Monitoring/Alarm-Rules.md)

## 计费
网络负载均衡支持按流量计费类型。详细说明请参见“[计费规则](../Pricing/Billing-Rules.md)”。