# 使用Graph面板

Graph面板是最常用的一种可视化面板，其通过折线图或者柱状图的形式显示监控样本随时间而变化的趋势。Graph面板天生适用于Prometheus中Gauge和Counter类型监控指标的监控数据可视化。例如，当需要查看主机CPU、内存使用率的随时间变化的情况时，可以使用Graph面板。同时，Graph还可以非常方便的支持多个数据之间的对比。

![Graph面板](http://p2n2em8ut.bkt.clouddn.com/grafana_graph_panel.png)

## 认识Graph Panel

通过Dashboard的“Add Panel”用户可以选择并添加一个类型为Graph的可视化面板。

对于Graph类型的面板来说，除了在上一小节中介绍过的General和Metric配置选项以外，还包含一些列的样式控制选项。

Graph:

* General:
* Metrics:
* Axes
* Legend
* Display
* Alert
* Time range

Singlestat:

* General
* Metrics
* Options
* Value Mappings
* Time range

Heatmap:

* General
* Metrics
* Axes
* Display
* Time range