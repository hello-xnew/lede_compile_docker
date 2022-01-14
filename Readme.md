# lede docker编译

## 使用方式

- 初始化docker 并进入docker

```shell
docker-compose up -d
lede chmod +x build.sh && ./build.sh
```

- 进入docker后

```shell
chmod 0777 /lede #添加权限
su - new #切换非root用户
bash #切换为bash
cd /lede #进入工作目录
```

- 同步代码并编译(参考具体项目)
