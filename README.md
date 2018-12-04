# 启动
1. 先调整主机`vm.max_map_count`：`sudo sysctl -w vm.max_map_count=262144`
2. 启动容器：`docker-compose up -d`
