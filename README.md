# 极路由1S（HC5661A）shadowsocks插件

[这个网页](https://app.hiwifi.com/dstore.php?m=download&a=info)上可以看到旧版本的固件，
我安装的是 1.3.5.18462s，

命令：
```bash
ssh 路由器
cd /tmp
wget https://raw.githubusercontent.com/noricohuas/hiwifi-shadowsocks/master/rom/1.3.5.18462s/HC5661A.bin
sysupgrade HC5661A.bin
```

hiwifi 1.2.5.15805s
```bash
cd /tmp && curl -k -o shadow.sh https://raw.githubusercontent.com/noricohuas/hiwifi-shadowsocks/master/shell/hiwifi-v1.2.5/shadow.sh && sh shadow.sh 12515805s && rm shadow.sh
```

特别感谢
[qiwihui/hiwifi-ss](https://github.com/qiwihui/hiwifi-ss/blob/master/README.md)
