## usage



docker-compose up -d       （需要 vblog.sql,vblog.conf,docker-compose.yml）





`docker file/Dockerfile-web` 和 `docker file/Dockerfile-api` 是分别放入 `vblog` 和 `vblog-web` 项目里的。

为了不用修改源代码，所以基于tomcat 镜像构建的。

你可以 使用 docker build 和 push 之后 替换掉 9rubi/....:0.0.1

默认启动会暴露 80 7080 5000 三个端口
