# Clash-for-Linux

# Install Clash

Download: https://github.com/Dreamacro/clash/releases/

API-Reference: https://github.com/Dreamacro/clash/wiki/External-controller-API-Reference

## Setup
```
gzip -d clash-linux-amd64-v1.11.8.gz
```

```
chmod +x clash-linux-amd64-v1.11.8
```

```
sudo mv clash-linux-amd64-v1.11.8 /usr/local/bin/clash
```

## Setting
查看版本
```
clash -v
```

配置全局变量
```
xhost +local: && sudo gedit /etc/environment
```
添加`ALL_PROXY=socks5://127.0.0.1:7891`


## Reference
https://juejin.cn/post/7149509056846102541

https://konosuba.xyz/blog/clash_linux_tutorial/



# How to use GUI in Linux


Clash 运行需要依赖相应的 YAML 配置文件，默认读取 `$HOME/.config/clash/config.yaml`

访问客户端 `http://clash.razord.top/#/proxies`

## 本地客户端
```
git clone [这个库]
```

本地运行, 浏览器访问
```
python3 -m http.server
```




## Reference
