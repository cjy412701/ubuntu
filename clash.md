# clash
## 1、下载-解压-重命名-启动

```sh
su root
cd /opt
yum install -y wget vim
wget https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.18.8/Clash.for.Windows-0.18.8-x64-linux.tar.gz
tar -xvf Clash.for.Windows-0.18.8-x64-linux.tar.gz
mv 'Clash for Windows-0.18.8-x64-linux'  clash 
exit;   #使用普通账号
/opt/clash/cfw   
```
## 设置https/http 代表为本地的7890端口
![Alt text](img/clash_allow%20lan.png)
## 然后设置本地代理
![Alt text](img/clash_%E8%AE%BE%E7%BD%AE%E4%BB%A3%E7%90%86.png)
