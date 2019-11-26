# 常用命令

## docker

1. 杀死所有正在运行的容器
```shell script
docker kill $(docker ps -a -q)
```

2. 删除所有已经停止的容器

```shell script
docker rm $(docker ps -a -q)
```

3. 删除所有未打 `dangling` 标签的镜像
```shell script
docker rmi $(docker images -q -f dangling=true)
```

4. 删除所有镜像
```shell script
docker rmi $(docker images -q)
```

5. 强制删除镜像名称中包含 `none` 的镜像
```shell script
docker rmi --force $(docker images | grep none | awk '{print $3}')
```

