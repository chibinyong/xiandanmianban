# xiandanmianban
开心版
下载xdpanel镜像：
wget http://tutu.ovh/iso/dockerimage/xdpanel/forwordpanel-1.0.7.tar
导入docker images：
docker load < /root/forwordpanel-1.0.7.tar
查看镜像ID：
docker images
启动docker容器：
docker run --restart=always -d -p 10203:8080 ef796f049164
启动完毕就可以开始享用啦~ 访问地址：

管理后台：http://IP:10203
默认账号：admin XIAOLIzz123
