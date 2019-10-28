![Shadowsocks](https://github.com/BertonLan/shadowsocks_install/raw/master/shadowsocks.png)
# Shadowsocks install
### Description: Auto Install Shadowsocks Server (all version) for CentOS/Debian/Ubuntu
## Step1
```
yum -y install wget
wget -c --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/bertonlan/shadowsocks_install/master/shadowsocks.sh
```
## Step2
```
chmod +x shadowsocks.sh
```
## Step3
```
./shadowsocks.sh 2>&1 | tee shadowsocks.log
```
## Step4 Auto install Shadowsocks server
```
1. Select 1 shadowsocks-python
2. Enter password for shadowsocks-python
3. Enter a port for shadowsocks-python[1-65535]  
(Default port:11260):11260
4. Select aes-256-cfb
```
## Congratulations，Shadowsocks-Python server install completed!  

# shadowsocks-libev.sh
``` 
Description: Auto Install Shadowsocks(libev) Server for CentOS
```
# shadowsocks-libev-debian.sh
``` 
Description: Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
```
# shadowsocks-go.sh
``` 
Description: Auto Install Shadowsocks(Go) Server for CentOS/Debian/Ubuntu
```
# shadowsocks-crond.sh
``` 
Description: Check Shadowsocks(All version) Server is running or not, and start it if not running
Intro: https://shadowsocks.be/6.html
```
# shadowsocksR.sh
``` 
Description: Auto Install ShadowsocksR Server for CentOS/Debian/Ubuntu
Intro: https://shadowsocks.be/9.html
``` 
# shadowsocks-haproxy.sh
``` 
Description: Auto Install haproxy for Shadowsocks Server
Intro: https://shadowsocks.be/10.html
``` 
Copyright (C) 2018-2019 BertonLan
