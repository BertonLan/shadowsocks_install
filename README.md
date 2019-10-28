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
- Select 1 shadowsocks-python
- Enter password for shadowsocks-python
- Enter a port for shadowsocks-python[1-65535]  
(Default port:11260):11260
- Select aes-256-cfb
## Congratulations，Shadowsocks-Python server install completed! 
