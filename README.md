# mackenzies01ssr
--------
SSR doub.io 1.0
一鍵
```
wget -N --no-check-certificate https://raw.githubusercontent.com/mackenzietsai/mackenzies01ssr/master/ssr-doub.io.sh && chmod +x ssr-doub.io.sh && bash ssr-doub.io.sh
```

分解動作
```
wget -N --no-check-certificate https://raw.githubusercontent.com/mackenzietsai/mackenzies01ssr/master/ssr-doub.io.sh
```

```
chmod +x ssr-doub.io.sh
```

```
bash ssr-doub.io.sh
```

---------
一鍵安裝腳本 (四合一)
```
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/mackenzietsai/mackenzies01ssr/master/shadowsocks-4in1.sh
```

```
chmod +x shadowsocks-4in1.sh
```

```
./shadowsocks-4in1.sh 2>&1 | tee shadowsocks-4in1.log
```
--------
Google BBR

```
wget --no-check-certificate https://raw.githubusercontent.com/mackenzietsai/mackenzies01ssr/master/bbr-google.sh
```

```
chmod +x bbr-google.sh
```

```
./bbr-google.sh
```

-----------

```
uname -r
```

```
sysctl net.ipv4.tcp_available_congestion_control
```

```
sysctl net.ipv4.tcp_congestion_control
```

```
sysctl net.core.default_qdisc
```

```
lsmod | grep bbr
```

-----------

魔改BBR

```
wget -N --no-check-certificate https://raw.githubusercontent.com/FunctionClub/YankeeBBR/master/bbr.sh && bash bbr.sh install
```

```
bash bbr.sh start
```

```
sysctl net.ipv4.tcp_available_congestion_control
```

















