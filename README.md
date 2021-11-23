# shell
transmission安装
## 下载
```shell    
wget https://raw.githubusercontent.com/zyhibook/shell/master/transmissionbt.sh
```
## 安装 
```shell
chmod 777 transmissionbt.sh
./transmissionbt.sh
```
浏览器访问`http://ip:9091`，默认账号密码都是`4dant.com`

## termux换源(清华源)
```shell
apt update && apt install wget
wget https://raw.githubusercontent.com/ibook86/Shell/master/termux.sh && chmod +x termux.sh && ./termux.sh
```
