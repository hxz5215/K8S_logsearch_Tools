# K8S_logsearch_Tools
K8S日志查询工具
基于python TK 编写的GUI工具，免费无毒。
360好像会误报，可以关闭360再使用

**使用上要注意：**
服务名称这里：输入的是POD名称，如果你的K8S集群上的POD是多副本形式，就无法使用该工具了，目前只支持单副本形式的POD进行日志查询！

起始日期：日期筛选条件，是根据你日志里面的时间戳来进行日志截取的，所以如果你日志内容中没有时间戳的话，也用不了该筛选条件！

------
本来是写给公司开发用的，试着做个通用版看看？
2020-04-29
