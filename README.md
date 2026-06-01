# LinuxSec

#### 一 、介绍
Linux Security 是一款服务器安全系统,用于监控进程流量、违规外联IP、数据泄露、AI Agent命令操作、eBPF捕获并审计加密流量（HTTPS和SSH),支持云服务器部署/内网离线部署/虚拟机部署等，是Linux系统最有效的安全防御系统。

#### 二、承诺
承诺：为了保证服务器安全，任何时候绝不联网。

#### 三 主要功能
    1、 流量可视化。 全程记录个进程违规外联 IP、外联 DNS 流量一目了然。
    2 、命令运行可视化。全程记录各AI Agent的原始联网报文、命令调用等，方便溯源分析。
    3、 加密流量可视化。可以对OpenSSl/GoTls等库做uprobe hook得到明文数据并审计。
    4 、系统管理可视化。全程记录SSH各项操作，对系统管理员零信任，发现非法入侵。
    5、 安全报警可视化。危险攻击行为及时报警，保障服务器的安全。


#### 四、安装步骤
要求内核版本大于3.10：

Debian 8+

RHEL(CentOS） 7.0+

ubuntu 18.04+

Fedora 32+

...

以root权限运行下面命令：

    1、 wget http://39.106.251.213/linuxsec 
    2、 chmod +x ./linuxsec
    3、 ./linuxsec

首次安装下载大约半分钟，出现System is running.....代表安装成功，可以WEB管理口9998（防火墙允许）登录进去。

#### 五、运行停止卸载
启动运行:  ./linuxsec         后台模式运行:   ./linuxsec daemon

停止运行:  ./linuxsec stop    卸载 :   rm  /linuxsec/ -rf

默认没加开机启动，linuxsec 加入开机启动程序。

#### 六、演示地址
请用大屏电脑观看，首次加载大屏组件需要10秒：
实战地址 [http://39.106.251.213:9998/](http://39.106.251.213:9998/)

#### 七、源码解压密码请加微信号httpwaf
pdf技术白皮书内有源码下载地址 [http://39.106.251.213:9998/firewall.pdf](http://39.106.251.213:9998/firewall.pdf)

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/wechat.png)

#### 八、来一张首页图片

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/home.png)
