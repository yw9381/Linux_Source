Docker Hub 源使用帮助
-----

在配置文件 ``/etc/docker/daemon.json`` 中加入：


- [163 mirrors](daemon_163.json) 
```
    {
      "registry-mirrors": ["https://hub-mirror.c.163.com"]
    }
```

- [ustc mirrors](daemon_ustc.json) 
```
    {
      "registry-mirrors": ["https://docker.mirrors.ustc.edu.cn/"]
    }
```


以root权限重新启动docker即可
```
service docker restart
```
