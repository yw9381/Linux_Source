这里记录的是一些国内常用的 Linux 软件镜像源的配置文件，方便直接进行软件源的更换

#如何使用
--------
使用 wget 或是 curl 直接进行下载

**SOURCE_URL** 为相应的配置文件的下载地址  
**CONFIGURATION_PATH** 为配置文件的路径

- 基于wget
	```
	wget SOURCE_URL -O CONFIGURATION_PATH
	```
- 基于curl
	```
	curl SOURCE_URL > CONFIGURATION_PATH
	```

##举例
以 Debian 8 阿里云的配置举例  
SOURCE_URL = ```https://raw.githubusercontent.com/yw9381/linux-source/master/Debian/debian_8_aliyun.list```  
CONFIGURATION_PATH = ```/etc/apt/sources.list```  

- 基于wget
	```
	wget https://raw.githubusercontent.com/yw9381/linux-source/master/Debian/debian_8_aliyun.list -O /etc/apt/sources.list
	```
- 基于curl
	```
	curl https://raw.githubusercontent.com/yw9381/linux-source/master/Debian/debian_8_aliyun.list > /etc/apt/sources.list
	```

#配置文件
--------
- 对于基于 CentOS/RHEL 的软件源的配置文件路径在    
	```
	/etc/yum.repos.d/CentOS-Base.repo
	```

- 对于基于 Debian 及其衍生版的软件源的配置文件路径在  
	```
	/etc/apt/sources.list
	```
- 对于基于 Ubuntu 及其衍生版的软件源的配置文件路径在  
	```
	/etc/apt/sources.list
	```


#收录情况
--------

- [x] [CentOS/Red Hat Enterprise Linux](CentOS/)
- [x] [CentOS/Red Hat Enterprise Linux Extra Packages for Enterprise Linux](CentOS_EPEL/)
- [x] [Ubuntu](Ubuntu/)
- [x] [Debian](Debian/)
- [ ] [Arch Linux](#)
- [ ] [Kali Linux](#)
- [ ] [Fedora](#)
- [ ] [FreeBSD](#)
- [ ] [OpenWrt](#)
- [ ] [Homebrew](#)
- [ ] [Docker](#)
- [ ] [PyPI/pip](#)

#其他
-----
欢迎提出 issue 以便于我更好的去收集相关软件源配置信息
