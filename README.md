# nb_docker
使用docker一键部署NoneBot，外部使用ssh连接简单方便，无污染

## 1、安装docker
```
过程请自行百度
```

## 2、拉取镜像
```
docker push shiran2488/nb_docker:1.0
```

## 3、运行镜像
```
docker run -id -p 2222:22 --name nb_docker shiran2488/nb_docker:1.0
```

## 4、使用ssh连接镜像
ip即为此服务器的ip，
账户：root
密码：nb_passwd
**注：第一次连接后请务必重新修改密码**

## 密码修改方法
```
passwd root
```
输入两次密码即可
