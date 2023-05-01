> ### 1. Linux主机配置gua环境

[(23条消息) linux 快速安装 guacamole (源码安装)_linux 安装guacamole_qq_38781075的博客-CSDN博客](https://blog.csdn.net/qq_38781075/article/details/106459458?ydreferer=aHR0cHM6Ly93d3cuc28uY29tL2xpbms%2FbT1ld1hvQlZSZkNNa2ZZdzdaSGVhMUpKbUZ5JTJGMkJuNHFvaURnSmd0d0RMMUh1VkhEJTJCWFdYY05kSEVtVkZndnNJQ21Lc01Ha0Fucm5sc3h1MnlCYWx3RG5xJTJGWjRYUXdPMFJUdExWMkp1VWhycENZQURTakglMkZOWjVmT2U0MEdDQ01obVd2UHdPc0trQlVJZ2lpRjNVNWZEM0J5JTJGRmRSMlZFTDVyeFBMeFQ2RzdqYjc0TEJlVXBodHFqaHNrRmNMc2MyJTJGZ2RoNjFBJTNEJTNE)

> ### 2. 同一台Linux主机部署jar包，并将conf.properties放在同级目录

## conf.properties详解

### ip-ue=12.12.12.209 //原15节点内网ip

### ue-port=6400 //原15节点远程连接rdp端口
### ip-dy=12.12.12.210 //原16节点内网ip
### dy-port=6400 //原16节点远程连接rdp端口
### username=huangxiaojie //原15.16节点账号（两个节点账号密码须一致）
### password=Aa123456 //原15.16节点密码

### //每次配置修改后jar包都要重新挂载

> ### 3. 端口涉及

### Linux主机：4822 （gua server默认端口），9632（java端口），6400（rdp端口）

### 原15.16节点：6400（rdp端口）

