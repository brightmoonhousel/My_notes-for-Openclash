# My_notes-for-openclash

## 1.启用passwall 
 启用passwall挂外网节点
为了让openwrt临时获得访问外网的能力
## 2.用openwrt-docker自建sub订阅转换服务
#### 使用docker run命令拉去dockerhub镜像并且配置启用，命令如下
```shell title="shell"
docker run --name=SubConverter -d --restart=always -p 25500:25500 tindy2013/subconverter:latest
```
搭建成功后订阅转换地址为
```
http://127.0.0.1:25500/sub
```
