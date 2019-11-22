# Grafana_tutorial
Grafana_tutorial

http://grafanatutorials.seanwasere.com/install-prometheus-node-exporter/

### After Install 
```
service grafana-server start
```


```yml
# Global Agent Configuration[agent]hostname="127.0.0.1"flush_interval="15s"interval="15s"# Input Plugins[[inputs.cpu]]percpu=truetotalcpu=truecollect_cpu_time=falsereport_active=false[[inputs.disk]]ignore_fs=["tmpfs","devtmpfs","devfs"][[inputs.io]][[inputs.mem]]
```