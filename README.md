# ss-panel-and-ss-py-mu
## ss-panel mod魔改版一键脚本
取消了默认的定时自动测速，取消了后端安装完成后的自动重启以便检查确保没有意外，检查完后请自行手动重启

安装完需要注意的一点是`/etc/rc.local`中的`exit 0`一定要放在文件最后，否则请自行修改

由于个人习惯原因取消了防火墙规则设置的相关代码，如有需要请自行根据自己需求开放端口，一般的机器默认全开的就不用管了

```
wget -N --no-check-certificate https://raw.githubusercontent.com/YKilin/ss-panel-and-ss-py-mu/master/ss-panel-v3-mod.sh && chmod +x ss-panel-v3-mod.sh && bash ss-panel-v3-mod.sh
```
## ss-panel v3一键脚本
没动过
```
wget -N --no-check-certificate https://raw.githubusercontent.com/YKilin/ss-panel-and-ss-py-mu/master/ss-panel_node.sh && chmod +x ss-panel_node.sh && bash ss-panel_node.sh
```

默认账号：91vps

默认密码：91vps
