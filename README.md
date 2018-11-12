# mackenzies01ssr
--------
SSR 1.0

```
wget -N --no-check-certificate https://softs.fun/Bash/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh
```

---------
一鍵安裝腳本 (四合一)
```
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/mackenzietsai/mackenzies01ssr/master/shadowsocks-4in1.sh
```

```
chmod +x shadowsocks-all.sh
```

```
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```
--------
Google BBR

```
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
```

```
chmod +x bbr.sh
```

```
./bbr.sh
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

















