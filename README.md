### 基于gost的局域网共享代理一键脚本，支持Socks5+Http双代理，Google VPN用户推荐使用

### 功能与Every Proxy应用一样，但在传输性能上，gost更加优秀

### Google Pixel手机先安装[Termux](https://github.com/termux/termux-app/releases)运行一键脚本

#### 一键脚本如下，快捷运行方式 ```bash gv.sh```

```
pkg upgrade -y && bash <(curl -Ls https://gh-proxy.com/https://raw.githubusercontent.com/Knowitall-wiki/google_vpn_proxy/main/gv.sh)
```

#### 可在Termux输入命令 ```ifconfig``` 查看内网IP地址，并填写在支持Socks5或者Http的客户端上

#### 使用注意：

1、安装完毕后，每当进入Termux，共享代理会自动启用

2、退出Termux后，共享代理会自动保持在后台运行

3、输入命令 ```exit``` 才可退出共享代理

--------------------------------------------------
