这里为 **Debian** 及其衍生版本的`Docker`软件源配置文件  
你可以直接使用wget将其下载至`/etc/apt/sources.list.d/`中，然后执行`apt update`即可  
安装Docker仅需要执行`apt install docker-ce -y`即可

# 收录情况

目前收录了 Debian 7/8/9/10 ，软件源地址为**校园网联合镜像站**

具体列表如下

- [Debian 12 Docker CerNet](debian_12_cernet_docker.list)
- [Debian 11 Docker CerNet](debian_11_cernet_docker.list)
- [Debian 10 Docker CerNet](debian_10_cernet_docker.list)

# 安装

```bash
curl https://mirrors.cernet.edu.cn/docker-ce/linux/debian/gpg|apt-key add -
apt update
apt install docker-ce
```