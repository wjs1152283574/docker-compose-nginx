# docker-compose-nginx
* 部署nginx时使用

###### 目录
1. `conf` 各项配置文件，对应`docker-compose.yaml` 里面的 `- ./conf/proxy.conf:/etc/nginx/proxy.conf`

2. `html` 静态文件，这里分为后台（admin）前端（dist）的静态文件, 具体配置看`./conf/nginx.conf`

3. `logs` 日志文件

* 运行 `docker-compose up -d` 