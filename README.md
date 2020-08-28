# 网络一键重装系统

作者链接：https://www.815494.com/html/734.html

**重装系统前环境需求**

1. 当前已安装任意由GRUB or GRUB2引导Linux系统(RedHat/CentOS/Debian/Ubuntu/Etc.)
2. 安装重装系统的前提组件

Centos：

> yum install -y xz openssl gawk file wget

Debian/Ubuntu:

> apt-get install -y xz-utils openssl gawk file wget

#### 自动安装脚本

> wget -N --no-check-certificate https://raw.githubusercontent.com/yesbest/reinstall/master/dd.sh  && chmod +x dd.sh && ./dd.sh

#### 下载手动安装脚本（通过root用户运行）

> wget -N --no-check-certificate https://raw.githubusercontent.com/yesbest/reinstall/master/Network-Reinstall-System-Modify.sh && chmod a+x Network-Reinstall-System-Modify.sh

#### 安装系统（任选其一）

【安装Linux系统】

一键网络重装纯净 CentOS 8

> bash Network-Reinstall-System-Modify.sh -CentOS_8

一键网络重装纯净CentOS 7

> bash Network-Reinstall-System-Modify.sh -CentOS_7

一键网络重装纯净CentOS 6

> bash Network-Reinstall-System-Modify.sh -CentOS_6

一键网络重装纯净Debian 9

> bash Network-Reinstall-System-Modify.sh -Debian_9

一键网络重装纯净Debian 8

> bash Network-Reinstall-System-Modify.sh -Debian_8

一键网络重装纯净Debian 7

> bash Network-Reinstall-System-Modify.sh -Debian_7

一键网络重装纯净Ubuntu 18.04

> bash Network-Reinstall-System-Modify.sh -Ubuntu_18.04

一键网络重装纯净Ubuntu 16.04

> bash Network-Reinstall-System-Modify.sh -Ubuntu_16.04

一键网络重装纯净Ubuntu 14.04

> bash Network-Reinstall-System-Modify.sh -Ubuntu_14.04

【安装Windows系统】

*警告：你需要购买来自Microsoft或其合作伙伴正版系统授权并激活系统使用。继续安装即代表您知悉并已经购买正版授权。

一键网络重装纯净Windows Server 2019

> bash Network-Reinstall-System-Modify.sh -Windows_Server_2019

一键网络重装纯净Windows Server 2016

> bash Network-Reinstall-System-Modify.sh -Windows_Server_2016

一键网络重装纯净Windows Server 2012 R2

> bash Network-Reinstall-System-Modify.sh -Windows_Server_2012R2

一键网络重装纯净Windows Server 2008 R2

> bash Network-Reinstall-System-Modify.sh -Windows_Server_2008R2

一键网络重装纯净Windows 7

> bash Network-Reinstall-System-Modify.sh -Windows_7_Vienna

一键网络重装纯净Windows Server 2003

> bash Network-Reinstall-System-Modify.sh -Windows_Server_2003

一键网络重装纯净Windows10(Password: www.nat.ee)

> bash Network-Reinstall-System-Modify.sh -Windows_10

【安装DD系统】

*如果您不了解这意味着什么，请不要进行操作。%ULR%应该替换为您自己的映像地址。

> bash Network-Reinstall-System-Modify.sh -DD "%URL%"

### 恭喜，你已经完成了系统重装，享受当下的美好

当您执行完上面的2行命令，你的服务器将开始网络重装纯净系统。在完成安装前，您将无法进行连接管理。

因硬件配置和网络环境不同，安装全程需要15-60分钟，请耐心等待。安装完成即可通过IP:22(Linux SSH)/IP:3389(Windows RDP)进行连接。
