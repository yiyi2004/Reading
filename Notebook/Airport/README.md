# Airport

- [Airport](#airport)
  - [调研](#调研)
    - [ExpressVPN](#expressvpn)
  - [UI 设计](#ui-设计)
  - [VPN 技术](#vpn-技术)
    - [References](#references)
  - [作为机场运营商，会遇到哪些问题](#作为机场运营商会遇到哪些问题)
    - [技术问题](#技术问题)
    - [非技术问题](#非技术问题)

all about airport and how to build an airport.

1. 先调研一下市面上发展比较好的VPN
2. 分析他们的优缺点，集各家之所长
3. 技术选型，选择目前最优的技术 grpc 0rtt
4. 分析搭建机场的技术文章
5. 总结相关技术

## 调研

### ExpressVPN

但与普通VPN有所不同的是，ExpressVPN采用的是自主研发的LightWay协议，该协议是专为中国用户而研发的，它在传统VPN协议的基础上增加了流量混淆功能，可以很好地伪装流量，能有效地突破GFW的封锁和限制，从而帮助中国网民实现科学上网的目的。此外，LightWay协议非常的轻巧，不仅速度很快，连接也很稳定。

如何自主研发一个协议呢？

优点：

- ExpressVPN一直能在中国使用
- 全球知名品牌，信誉好，安全性高，速度也是业内最快的
- 在全球94个国家部署了3000多台服务器
- 在中国周边地区也拥有大量服务器节点
- 能快速访问Google、Facebook、Youtube等网站
- 能流畅地观看Netflix、BBC iPlayer、Hulu等流媒体上1080P高清视频
- 支持P2P文件共享和种子下载
- 内置拆分隧道和Kill Switch等高级功能
- 兼容Windows、MacOS、Android、iOS、Linux、路由器、浏览器、智能电视、游戏机等
- 支持5台设备同时登录使用
- 提供7天24小时在线客服
- 提供30天退款保证（可免费使用30天）

缺点：

- 无中文官网和中文APP客户端
- 不支持支付宝付款（以前支持）
- 价格稍微偏高（一分钱一分货）

## UI 设计

可以参考优秀的 VPN 官网的 UI 设计和国内小众的 VPN 技术。

## VPN 技术

佛跳墙 God use VPN

### References

- [Clash](https://github.com/Dreamacro/clash):A rule-based tunnel in Go.
- [Project V](https://github.com/v2ray):A Vee Network Solution

## 作为机场运营商，会遇到哪些问题

### 技术问题

1. 红蓝对抗
2. IP 被封锁问题
3. 数据迁移问题
4. 如何拿到好的服务器资源
5. 如何管理服务器，现代化管理服务器的方法(Github)

问题会不断的出现，需要不断的记录和解决。写营销文章，例如：我们为什么需要读第一手和第二手的资料，外面的世界，chatgpt(如何实现和访问)，youtube，网飞，telegram，instgram 等等软件。游戏模式，与世界各地的人进行交流，学习先进的技术和文化。体验最新的技术，云函数。

解释加速器和VPN之间的区别

### 非技术问题

1. 活动如何办，什么时候办，在用户基数起来的时候。
