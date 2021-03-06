### 如何使用 NAT 网关和弹性公网 IP？
- NAT 网关是一种将私有网络中内网 IP 地址和公网 IP 地址进行转换的网关，是 VPC 内的一个公网流量的出入口。有关腾讯云 NAT 网关的使用说明，详情请参见 [NAT 网关](https://cloud.tencent.com/document/product/215/4975) 。
- NAT 网关和弹性公网 IP 是云服务器访问 Internet 的两种方式，可以选择其中一种或两种用于用户的公网访问架构设计，详情请参见 [方案](https://cloud.tencent.com/document/product/215/4975#nat-.E7.BD.91.E5.85.B3.E5.92.8C.E5.BC.B9.E6.80.A7.E5.85.AC.E7.BD.91-ip-.E7.9A.84.E4.BD.BF.E7.94.A8)。



### 如何创建 NAT 网关？
用户可以进入  [腾讯云控制台](https://console.cloud.tencent.com/) 创建 NAT 网关。详情请参见  [创建 NAT 网关](https://cloud.tencent.com/document/product/552/18186#.E6.AD.A5.E9.AA.A41.EF.BC.9A.E5.88.9B.E5.BB.BA-nat-.E7.BD.91.E5.85.B3)。


### 如何修改 NAT 网关配置？
用户进入 [腾讯云控制台](https://console.cloud.tencent.com/)，可以对其属性进行修改。详情请参见 [修改 NAT 网关配置](https://cloud.tencent.com/document/product/552/18179)。


### 如何管理 NAT 网关的弹性 IP？
用户可以进入  [腾讯云控制台](https://console.cloud.tencent.com/) 管理 NAT 网关的弹性 IP。详情请参见 [管理 NAT 网关的弹性 IP](https://cloud.tencent.com/document/product/552/18180)。


### 如何查看 NAT 网关监控信息？
用户进入 [腾讯云控制台](https://console.cloud.tencent.com/) 后，可以通过控制台查看监控信息并导出数据，查看 NAT 网关监控信息。详情请参见 [查看 NAT 网关监控信息](https://cloud.tencent.com/document/product/552/18181)。

### 如何设置告警？
用户可以进入  [腾讯云控制台](https://console.cloud.tencent.com/) 为 NAT 网关设置告警来监控 NAT 网关的状态。详情请参见 [设置告警](https://cloud.tencent.com/document/product/552/18182)。

### 如何删除 NAT 网关？
用户进入 [腾讯云控制台](https://console.cloud.tencent.com/)，在确定无需使用 NAT 网关后，可以随时将其删除。详情请参见 [删除 NAT 网关](https://cloud.tencent.com/document/product/552/18183)。

### 如何开启网关流控明细？
用户进入  [腾讯云控制台](https://console.cloud.tencent.com/)，开启网关流控明细后，可以查看过去 7 天内经过某网关的 IP 流量指标，也可设置某个 IP 流向指定 NAT 网关的出带宽。详情请参见 [开启网关流控明细](https://cloud.tencent.com/document/product/552/18184)。

### 如何设置网关流控明细？
用户进入  [腾讯云控制台](https://console.cloud.tencent.com/)，可设置某个 IP 流向某 NAT 网关的出带宽。详情请参见 [设置网关流控明细](https://cloud.tencent.com/document/product/552/18242)。


### 如何查看网关流控明细？
用户进入  [腾讯云控制台](https://console.cloud.tencent.com/)，可以查看已限制 IP 的流控明细。详情请参见 [查看网关流控明细](https://cloud.tencent.com/document/product/552/18239)。

### 如何绑定高防包？
用户可以进入  [腾讯云控制台](https://console.cloud.tencent.com/) 为 NAT 网关绑定 BGP 高防包以抵御 DDoS 攻击。详情请参见 [绑定步骤操作](https://cloud.tencent.com/document/product/552/18185)。

### 如何在 VPC 的 NAT 网关上配置端口映射？

目前使用网络内部使用的是动态 NAT 随机对应端口，现在还不支持写静态 NAT。


### 在何处可以找到有关安全性的更多信息？
腾讯云提供安全组、加密登录、弹性 IP 等各种网络与安全性服务保障您的实例安全、高效、自由地对内对外提供服务。 如需有关云服务器的安全性等更多信息，详情请参见 [ 网络与安全性概述](/document/product/213/5220)。

### 如何防止他人查看我的系统？
用户可以完全掌控您的系统的可见性，云服务器允许用户将运行的实例放入用户所选择的任意安全组中。借助 [控制台-安全组 ](https://console.cloud.tencent.com/cvm/securitygroup)的界面，用户可以指定组间通信，以及网络上哪些 IP 子网可以与云服务器通信。

### 出现安全问题如何排查？
如怀疑出现安全隐患或出现不良事件，详情请参见 [安全帮助指引](/document/product/301/9610) 进行排查，同时可参考[ 主机安全](/document/product/296) 解决出现的安全问题。 
