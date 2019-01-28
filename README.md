## Getting started
```
helm install --name myzk incubator/zookeeper --set servers=1,heap="1G"
helm del --purge hbase;helm install . --name hbase
```
