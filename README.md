# Golang Docker Environment

## Q&A

### docker-compose.yml

`docker-compose.yml` 文件是一个定义服务、 网络和卷的 `YAML` 文件。

> 服务定义包含应用于为该服务启动的每个容器的配置，就像传递命令行参数一样 `docker container create`。同样，网络和卷的定义类似于 `docker network create` 和 `docker volume create`。

> 正如 `docker container create` 在 `Dockerfile` 指定选项，如 `CMD、 EXPOSE、VOLUME、ENV`，在默认情况下，你不需要再次指定它们 `docker-compose.yml`。

> 可以使用 `Bash` 类 `${VARIABLE}` 语法在配置值中使用环境变量。

