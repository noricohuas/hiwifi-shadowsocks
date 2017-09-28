# 极路由1S（HC5661A）shadowsocks插件

[这个网页](https://app.hiwifi.com/dstore.php?m=download&a=info)上可以看到旧版本的固件，
我安装的是 1.3.5.18462s，

命令：
```bash
ssh 路由器
cd /tmp
wget http://ur.ikcd.net/HC5861-sysupgrade-20160901-0953a61e.bin
sysupgrade HC5861-sysupgrade-20160901-0953a61e.bin
```

更新后的shell命令
```bash
cd /tmp && curl -k -o shadow.sh https://raw.githubusercontent.com/cllu/hiwifi-ss/hiwifi-v1.2.5/shadow.sh && sh shadow.sh && rm shadow.sh
cd /tmp
