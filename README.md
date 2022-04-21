# 编译 libheif 依赖的 centos7 镜像

## 编译

```shell
docker build . -f Dockerfile.build.centos -t heif-build-centos7
```

如果需要安装 golang，可以看看 Dockerfile.test.centos 中的配置。