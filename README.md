
**iPerf 3是一个网络性能测试工具**

- 测试TCP和UDP带宽质量
- 测量最大TCP带宽，具有多种参数和UDP特性
- 报告带宽，延迟抖动和数据包丢失
- 测试一些网络设备如路由器，防火墙，交换机等的性能

**1.CentOS下一键安装 iPerf 3 脚本：**

wget -O /usr/lib/libiperf.so.0 https://iperf.fr/download/ubuntu/libiperf.so.0_3.1.3
wget -O /usr/bin/iperf3 https://iperf.fr/download/ubuntu/iperf3_3.1.3
chmod +x /usr/bin/iperf3

**2.在 VPS 上运行 iPerf 3 进程**

   iperf3 -s -p 5201

其中 -s 参数表示服务器端，-p 指定使用端口(默认端口 5201)。如果需要以守护进程后台运行，追加 -D 参数。

   iperf3 -s -D

**3.在Surge 4中进行 iPerf 测试**
![image](https://github.com/iJony/iPerf-3-Test/blob/master/IMG_485.JPEG)







