# 站群多ip ss5 sk5 ss ssr协议 安装 联系QQ 1853479098 
socks5  多ip 多出口

# 系统支持 Debian 9+/Ubuntu 20.04+/Centos 7+
sockes5 一键搭建脚本 
使用方法  2选1

wget -N --no-check-certificate https://my.sailulu.xyz/work/ss5.sh && bash ss5.sh

wget -N --no-check-certificate https://raw.githubusercontent.com/zz4279669/socks5/main/ss5.sh && bash ss5.sh

# 命令报错的话 请安装wget
yum -y install wget  或者  apt -y install wget

# 请我喝奶茶

![](https://github.com/zz4279669/Socks5/blob/main/WechatIMG144.png)



# 快速搭建
git clone -b master https://github.com/zz4279669/ss-fly.git<br>
ss-fly/ss-fly.sh -i  密码  端口

启动：/etc/init.d/ss-fly start

停止：/etc/init.d/ss-fly stop

重启：/etc/init.d/ss-fly restart

状态：/etc/init.d/ss-fly status

查看ss链接：ss-fly/ss-fly.sh -sslink

修改配置文件：vim /etc/shadowsocks.json

卸载 ss-fly/ss-fly.sh -uninstall
