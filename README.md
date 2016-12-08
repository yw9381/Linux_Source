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

软件源配置文件

- 对于基于 CentOS/RHEL 的  
	软件源的配置文件路径在  
	```
	/etc/yum.repos.d/CentOS-Base.repo
	```

- 对于基于 Debian 及其衍生版的  
	软件源的配置文件路径在  
	```
	/etc/apt/sources.list
	```
- 对于基于 Ubuntu 及其衍生版的  
	软件源的配置文件路径在  
	```
	/etc/apt/sources.list
	```


#收录情况
--------
目前收录

- [CentOS/Red Hat Enterprise Linux](CentOS/README.md)
- [Ubuntu](Ubuntu/README.md)
- [Debian](Debian/README.md)


#其他
-----
欢迎提出 issue 以便于我更好的去收集相关软件源配置信息