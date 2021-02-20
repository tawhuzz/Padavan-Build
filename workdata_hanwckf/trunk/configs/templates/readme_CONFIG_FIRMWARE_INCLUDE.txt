使用gorden5566的汉化字典
aria2前端更换为AriaNg
curl可选编译可执行程序 CONFIG_FIRMWARE_INCLUDE_CURL
使用了PROMETHEUS提供的部分补丁
使用了Linaro1985/padavan-ng的部分软件包
可选以下插件：

scutclient CONFIG_FIRMWARE_INCLUDE_SCUTCLIENT
#用C编写的SCUT Dr.com（X）客户端。
#Dr.COM广泛用于各大高校的宽带认证，常见有三个版本P、D、X版。
#P版就是在普通的PPPOE拨号的基础上添加了一个客户端与服务器通信认证的过程。#D版直接通过客户端的接口与服务器建立连接。#X版复杂许多，一般会先有802.1x认证再进行端口通讯认证。

gdut-drcom CONFIG_FIRMWARE_INCLUDE_GDUT_DRCOM
#第三方drcom客户端提供一个心跳服务。
#包括一个命令行工具（gdut-drcom），以及一个动态库（gdut-drcom.dll，gdut-drcom.so）供上层程序调用，支持Linux与Windows（mingw64）平台。

dogcom CONFIG_FIRMWARE_INCLUDE_DOGCOM
#Drcom通用C语言实现

minieap CONFIG_FIRMWARE_INCLUDE_MINIEAP
#这是一个实现了标准 EAP-MD5-Challenge 算法的 EAP 客户端，支持通过插件来修改标准数据包以通过特殊服务端的认证。
#目前带有一个实现锐捷 v3 (v4) 算法的插件。本插件的认证算法来自 Hu Yunrui 的 MentoHUST 项目，在此表示感谢！

njit-client CONFIG_FIRMWARE_INCLUDE_NJIT_CLIENT
#校园网的拨号软件njit-client,安装在路由器，可实现拨号上网。

napt66 CONFIG_FIRMWARE_INCLUDE_NAPT66
#IPv6-IPv6网络地址端口转换（NAPT66）是有状态的IPv6 NAT机制。
#像IPv4 NAT一样，NAPT66技术使多个主机共享一个公共IPv6地址。#结果，NAPT66有助于隐藏专用网络拓扑并提高网络安全性。
#基于GNU / Linux的NAPT66在内核空间中实现，可提供令人满意的性能和可移植性。
#它已移植到多个开源路由器固件（例如OpenWrt），因此可以在低端的商用硬件（例如BCM63xx平台）上运行。
#NAPT66应该安装在两个IPv6网络之间的边界路由器上。它在内部IPv6主机和外部IPv6主机之间执行有状态的数据包转换。
#NAPT66使用应用程序级别网关（ALG）和DNS代理来处理复杂的应用程序（例如活动的FTP和DNS）。将来会有更多的应用程序使用NAPT66。

ssr/ss CONFIG_FIRMWARE_INCLUDE_SHADOWSOCKS
ss-server CONFIG_FIRMWARE_INCLUDE_SSSERVER
#Shadowsocks-libev是用于嵌入式设备和低端盒的轻型安全SOCKS5代理。
#它是@clowwindy 创建的Shadowsocks的端口，并由@madeye和@linusyang维护 。
#Shadowsocks-libev用纯C编写，并依赖于libev。它被设计为Shadowsocks协议的轻量级实现，以使资源使用率尽可能低。
#Shadowsocks-libev用纯C语言编写，仅取决于 libev和 OpenSSL或mbedTLS或PolarSSL。

softether-vpnserver CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_SERVER
softether-vpnclient CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_CLIENT
softether-vpncmd CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_CMD
#SoftEther VPN（稳定版存储库）
#-开源跨平台多协议VPN程序
#https://www.softether.org/
#MITOH项目为SoftEther VPN的开发提供了支持，日本政府的研发项目，由经济产业省（日本经济产业省）补贴，由IPA（日本信息促进局）管理。

dns-forwarder CONFIG_FIRMWARE_INCLUDE_DNSFORWARDER
#https://github.com/aa65535/hev-dns-forwarder
#hev-dns-转发器

vlmcsd CONFIG_FIRMWARE_INCLUDE_VLMCSD
#win激活工具

ttyd CONFIG_FIRMWARE_INCLUDE_TTYD
#ttyd是用于在Web上共享终端的简单命令行工具。

lrzsz CONFIG_FIRMWARE_INCLUDE_LRZSZ
#lrzsz：免费的x / y / zmodem实现
#lrzsz是提供 XMODEM，YMODEM ZMODEM文件传输协议的Unix通信包 。
#lrzsz是Omen Technologies rzsz 软件包的上一个公共领域版本的重制版本， 现已成为 免费软件 ，并根据 GNU通用公共许可证发行。

htop CONFIG_FIRMWARE_INCLUDE_HTOP
#htop，一个跨平台的交互式过程查看器。它是一个文本模式应用程序（用于控制台或X终端），需要ncurses

nano CONFIG_FIRMWARE_INCLUDE_NANO
#nano 易于使用且友好的Pico文本编辑器。

iperf3 CONFIG_FIRMWARE_INCLUDE_IPERF3
#iperf是用于主动测量IP网络上可达到的最大带宽的工具。
#它支持调整与时序，协议和缓冲区有关的各种参数。对于每个测试，它都会报告测得的吞吐量/比特率，损耗和其他参数。

dump1090 CONFIG_FIRMWARE_INCLUDE_DUMP1090
#dump1090是专门为RTLSDR设备设计的S模式解码器。
#要直接从RTL设备捕获流量并在标准输出上显示捕获的流量，只需运行不带任何选项的程序：./dump1090

rtl-sdr CONFIG_FIRMWARE_INCLUDE_RTL_SDR
#基于Realtek RTL2832U的DVB-T软件狗可以用作便宜的SDR，因为该芯片允许将原始I / Q样本传输到主机，该主机正式用于DAB / DAB + / FM解调。

samba3.6 CONFIG_FIRMWARE_INCLUDE_SMBD36
#这是Samba的发行版本，Samba是用于UNIX和其他操作系统的免费SMB和CIFS客户端和服务器。
#Samba由Samba团队维护，该团队支持原始作者Andrew Tridgell。

mtr CONFIG_FIRMWARE_INCLUDE_MTR
#mtr在单个网络诊断工具中结合了“ traceroute”和“ ping”程序的功能。
#在启动mtr时，它将调查运行mtr的主机与用户指定的目标主机之间的网络连接。
#确定机器之间每个网络跃点的地址后，它将向每个发送ICMP ECHO请求序列，以确定到每个机器的链路质量。这样，它将打印有关每台计算机的运行统计信息。

socat CONFIG_FIRMWARE_INCLUDE_SOCAT
#socat是用于在两个独立数据之间进行双向数据传输的中继渠道。
#这些数据通道中的每一个都可以是文件，管道，设备（串行行等或伪终端），套接字（UNIX，IP4，IP6-原始，UDP，TCP），
# SSL套接字，代理CONNECT连接，文件描述符（stdin等），GNU行编辑器（readline），程序或两者的组合。 这些模式包括生成“侦听”套接字，命名管道和伪终端。
#socat可以用作TCP端口转发器（单发或守护程序），也可以用作外部socksifier，用于攻击弱防火墙，作为UNIX的外壳接口套接字，IP6中继，
# 用于将面向TCP的程序重定向到串行线，以逻辑上连接不同计算机上的串行线，或建立一个运行客户端或服务器的相对安全的环境（su和chroot）具有网络连接的Shell脚本。 

srelay CONFIG_FIRMWARE_INCLUDE_SRELAY
#Srelay是socks 4/5协议代理服务器。
#在协议v4，v4a和v5中支持袜子连接/绑定请求。#支持与v4和v5服务器的socks服务器链接。#在v5中支持用户名/密码身份验证（不推荐）。
#在Linux-x86_64，macos 10.7-10.12，FreeBSD 10.1-11.1上进行测试
#支持IPv6和IPv4。

3proxy CONFIG_FIRMWARE_INCLUDE_3PROXY
＃3APA3A 3proxy小代理服务器

mentohust CONFIG_FIRMWARE_INCLUDE_MENTOHUST
#锐捷校园网连接工具，支持OpenWRT/Ubuntu/Fedora.

frpc CONFIG_FIRMWARE_INCLUDE_FRPC
frps CONFIG_FIRMWARE_INCLUDE_FRPS
#frp是一个专注于内网穿透的高性能的反向代理应用，支持 TCP、UDP、HTTP、HTTPS 等多种协议。可以将内网服务以安全、便捷的方式通过具有公网 IP 节点的中转暴露到公网。
#frp是一种快速反向代理，可帮助您将NAT或防火墙后面的本地服务器公开到Internet。
#到目前为止，它支持TCP和UDP以及HTTP和HTTPS协议，在这些协议中，请求可以通过域名转发到内部服务。frp还具有P2P连接模式。

tunsafe CONFIG_FIRMWARE_INCLUDE_TUNSAFE
#一键免费实现vpn链接的安全wireguard工具,可让您连接到WireGuard兼容的VPN服务器

wireguard-go CONFIG_FIRMWARE_INCLUDE_WIREGUARD
#这是Go中WireGuard的实现。
#WireGuard 是一个易于配置、快速且安全的开源 VPN，它利用了最新的加密技术。目的是提供一种更快、更简单、更精简的通用 VPN，它可以轻松地在树莓派这类低端设备到高端服务器上部署。
