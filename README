概述
===========

本工具基于www.thc.org IPv6工具包规范开发。用以模拟发起各种ipv6网络包，以便进行一些研究性实验。
特别感谢：https://github.com/hackerschoice 及其源基础代码


安装
============

## Ubuntu环境
1. 安装以下依赖包：

```
$ sudo apt-get install libpcap-dev libssl-dev
```

2. 可选项 obscure 攻击， 安装以下依赖包:
```
$ sudo apt-get install libnetfilter-queue-dev
```

3. 编译：
```
$ make
```

4. 安装所有工具：
```
$ sudo make install
```

## CentOS环境
1. 安装以下依赖包：
```
$ sudo yum install -y libpcap-devel libssl-devel
```

2. 可选项 obscure 攻击， 安装以下依赖包:
```
$ sudo yum install -y libnetfilter_queue-devel
```

3. 编译：
```
$ make
```

4. 安装所有工具：
```
$ sudo make install
```

## 环境限制
 - 内核要求：Linux 2.6.x或更新
 - 网络网卡设备


包含工具
=========
tools:
 - fake_mipv6: steal a mobile IP to yours if IPSEC is not needed for authentication
 - fake_mld6: announce yourself in a multicast group of your choice on the net
 - fake_mld26: same but for MLDv2
 - fake_mldrouter6: fake MLD router messages
 - fake_advertiser6: announce yourself on the network
 - parasite6: ICMPv6 neighbor solitication/advertisement spoofer, puts you
   as man-in-the-middle, same as ARP mitm (and parasite)
 - alive6: an effective alive scanng, which will detect all systems
   listening to this address
 - dnsdict6: parallized DNS IPv6 dictionary bruteforcer
 - fake_router6: announce yourself as a router on the network, with the
   highest priority
 - redir6: redirect traffic to you intelligently (man-in-the-middle) with
   a clever ICMPv6 redirect spoofer
 - toobig6: mtu decreaser with the same intelligence as redir6
 - detect-new-ip6: detect new IPv6 devices which join the network, you can
   run a script to automatically scan these systems etc.
 - dos-new-ip6: detect new IPv6 devices and tell them that their chosen IP
   collides on the network (DOS).
 - trace6: very fast traceroute6 with supports ICMP6 echo request and TCP-SYN
 - flood_router6: flood a target with random router advertisements
 - flood_advertise6: flood a target with random neighbor advertisements
 - fuzz_ip6: fuzzer for IPv6 
 - implementation6: performs various implementation checks on IPv6 
 - implementation6d: listen daemon for implementation6 to check behind a FW
 - smurf6: local smurfer
 - rsmurf6: remote smurfer, known to work only against linux at the moment
 - exploit6: known IPv6 vulnerabilities to test against a target
 - denial6: a collection of denial-of-service tests againsts a target
 - thcping6: sends a hand crafted ping6 packet
 - sendpees6: a tool by willdamn@gmail.com, which generates a neighbor
   solicitation requests with a lot of CGAs (crypto stuff ;-) to keep the
   CPU busy. nice.
and about 25 more tools for you to discover :-)
