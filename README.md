# Linux-NetSpeed

预先准备

```bash
centos：yum install ca-certificates wget -y && update-ca-trust force-enable
```
```bash
debian/ubuntu：apt-get install ca-certificates wget -y && update-ca-certificates
```
国外可用 内核版本 5.13.13-1
卸载内核版本
```bash
wget -O tcp.sh "https://raw.githubusercontent.com/hhkaa/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```

不卸载内核版本
```bash
wget -O tcpx.sh "https://raw.githubusercontent.com/hhkaa/Linux-NetSpeed/master/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh
```

国内可用 内核版本 5.10
```bash
wget -O tcpx.sh "https://raw.githubusercontent.com/hhkaa/Linux-NetSpeed/master/cntcp.sh" && chmod +x tcpx.sh && ./cntcp.sh
```
