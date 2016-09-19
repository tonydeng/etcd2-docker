# Alpine Linux Etcd2 Docker Container
[![Docker Stars](https://img.shields.io/docker/stars/wolfdeng/etcd2-docker.svg)](https://hub.docker.com/r/wolfdeng/etcd2-docker-docker/)
[![Docker Pulls](https://img.shields.io/docker/pulls/wolfdeng/etcd2-docker.svg)](https://hub.docker.com/r/wolfdeng/etcd2-docker/)
[![Image Size](https://img.shields.io/imagelayers/image-size/wolfdeng/etcd2-docker-docker/latest.svg)](https://imagelayers.io/?images=wolfdeng/etcd2-docker:latest)
[![Image Layers](https://img.shields.io/imagelayers/layers/wolfdeng/etcd2-docker/latest.svg)](https://imagelayers.io/?images=wolfdeng/etcd2-docker:latest)

利用Alpine Linux打造的小体积的ETCD Docker镜像。

### 使用方式：

获取docker镜像

```
docker pull wolfdeng/etcd2-docker
```


启动docker

```
 docker run --name etcd2 -d -p 2379:2379 -p 2380:2380 -p 4001:4001 -p 7001:7001 -v ~/temp/data0/etcd:/data wolfdeng/etcd2-docker
```
