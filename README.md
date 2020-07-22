# charts-k8s
charts of k8s

helm 

1.grafana

通过docker 在k8s上创建grafana服务，包含deployment、service等组件，
可通过dashboard-config.yaml 直接在服务生成时将dashboard json 文件放入/etc/grafana/provisioning/dashboards目录下，
grafana服务启动后自动扫描导入dashboard，
数据源同理 也可提前配置。

2.prometheus

创建prometheus服务 时序数据库，作为grafana图表的数据源
