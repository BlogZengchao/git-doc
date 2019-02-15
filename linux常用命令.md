##### centos7防火墙命令

- 查看防火墙状态       ```firewall-cmd --state```
- 重启防火墙           ```firewall-cmd --reload```
- 停止防火墙           ```systeml stop firewalld.service```
- 开启端口              ```firewall-cmd --zone=public --add-port=80/tcp --permanent``` zone:作用域 add-port:端口 permanent:永久生效