# 日志下载
1、控制台--日志下载说明

登录 CDN控制台 ，选择左侧菜单栏的【日志下载】，选择要获取日志的时间及域名，单击【下载】，即可获取日志下载内容。

2、日志内容

01/Dec/2017:04:13:10 +0800 117.71.34.139 - 0.175 - GET HTTP/1.1 https://www.jcloud.com/index 200 242 1014 MISS Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.1.4322) -

3、字段含义


4、日志说明

文件命名：域名_日期_起始时间

保存时间：日志文件最多保存2周

日志延迟：日志文件延迟1小时，可以在日志管理模块查询到1小时之前的日志文件

文件间隔：小时颗粒度显示的日志列表，单个文件为1小时间隔；

天颗粒度显示的日志列表，单个文件为1天间隔（当天日志不满1天的，取当天最早开始的日志到最晚结束的日志时间段）。

查询范围：按小时查询只能查询当前时间开始往前3天内的日志,如:当前时间1月5日 10:35:35,按小时查询只能查询1月2日0点到1月5日10点的日志(小时日志是在半点之后能查询)；

按天则能查询除了当天往前30天内的日志.
