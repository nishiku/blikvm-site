# **端口转发**

如果您的ISP为路由器提供了外部IP地址，您可以配置端口转发以访问PiKVM。

* Web界面为http协议，占用的是80端口；
* 如果您的硬件是V1 V2 V3，使用的是是web-rtc传输，端口是8188；
* 如果您的硬件是V4，使用的是mjepg传输，端口是8008；
* 注意端口不支持被修改，只能配置转发；

如果您没有外部IP地址，我们建议尝试使用[Tailscale VPN](./tailscale.md)。