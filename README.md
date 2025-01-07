# My_notes-for-openclash

### 1.启用passwall 
#### 启用passwall挂外网节点
为了让openwrt临时获得访问外网的能力
### 2.docker自建sub订阅转换命令
```shell title="shell"
docker run --name=SubConverter -d --restart=always -p 25500:25500 tindy2013/subconverter:latest
```