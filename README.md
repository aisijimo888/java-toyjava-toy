# xx-for-bbn

前面已经把玩具鸡的各种玩法讲了，对于nodejs与python平台，大家都很熟悉了，今天说说JAVA平台通用部署方法

以[bbn.one](https://bbn.one)为例，介绍java平台部署x-ra-y的方法，其他JAVA平台类同

第一步：修改参考c.yml中变量，建议设置哪吒和argo，其他不要动,不需要参数的直接删掉或加#注释掉

第二步：创建java服务器

![image](https://github.com/dsadsadsss/xx-for-bbn/blob/main/png/1.PNG)

第三步：选择这个创建

![image](https://github.com/dsadsadsss/xx-for-bbn/blob/main/png/2.PNG)

第四步: 点击右下角登陆旧面板，密码看下图红框位置

![image](https://github.com/dsadsadsss/xx-for-bbn/blob/main/png/3.PNG)
![image](https://github.com/dsadsadsss/xx-for-bbn/blob/main/png/5.PNG)

第五步: 把仓库文件上传即可启动，不需要设置权限，启动文件名改为sever.jar

完成，启动即可，本教程需要借助ARGO隧道

# 隧道设置：

vmess 端口  localhost:8001

vless 端口  localhost:8002

# XRAYN设置：

以vless 为例，复制粘贴后修改配置即可，vmess 路径改为/vms?ed=2048即可
```
vless://fd80f56e-93f3-4c85-b2a8-c77216c509a7@cdn.xn--b6gac.eu.org:443?host=argo%E5%9F%9F%E5%90%8D&path=%2Fvls%3Fed%3D2048&type=ws&encryption=none&fp=chrome&security=tls&sni=argo%E5%9F%9F%E5%90%8D#darknodes
```
# 其他玩具平台：
https://github.com/dsadsadsss/python-wanju.git

https://github.com/dsadsadsss/nodejs-wanju.git

https://github.com/dsadsadsss/bedrock-wanju.git

# 免责声明:

本仓库仅为自用备份，非开源项目，因为需要外链必须公开，但是任何人不得私自下载, 如果下载了，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权。 

如果你使用本仓库文件，造成的任何责任与本人无关, 本人不对使用者任何不当行为负责。
