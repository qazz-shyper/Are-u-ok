## iStore软件包 iStore .run Packages

* 本页面所下载的软件包插件适用于aarch64_cortex-a53平台的机器(EasePi ARS2、小米AX3600、AX9000、红米AX6等)。

* 也兼容aarch64_generic平台，例如R2S、R4S、R5S、R68S等。

* 适用于KoolCenter iStoreOS 22.03.X的软件包

#### 常用代理软件包 Commonly Used Proxy Packages
|插件名|功能|下载|编译日期|
| :----: | :----: | :----: | :----: |
| [PassWall](https://github.com/xiaorouji/openwrt-passwall) | 科学工具 | [PassWall_4.78-4](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/PassWall_4.78-4_aarch64_a53_all_sdk_22.03.7.run) |2024-11-01|
| [PassWall](https://github.com/xiaorouji/openwrt-passwall) | 科学工具 | [给小储存硬路由的PassWall](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/PassWall_4.78-4_aarch64_a53_small_sdk_22.03.7.run) |2024-11-01|
| [PassWall2](https://github.com/xiaorouji/openwrt-passwall2) | 科学工具 | [PassWall2_1.31-1](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/PassWall2_1.31-1_aarch64_a53_all_sdk_22.03.7.run) |2024-11-01|
| [SSR-Plus](https://github.com/fw876/helloworld) | 科学工具 | [SSR-Plus_188](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/SSR-Plus_188_aarch64_a53_all_sdk_22.03.7.run) |2024-10-06|
| [OpenClash](https://github.com/vernesong/OpenClash) | 科学工具 | [OpenClash_0.46.033](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/OpenClash_0.46.033+aarch_64_core.run) |2024-09-24|
* passwall、passwall2、ssr-plus均使用 22.03.X sdk编译，依旧使用libopenssl1.1，无需libopenssl3依赖，安装后在服务里。
* 不推荐passwall系列和ssr-plus一同安装，因为部分软件包可能存在冲突影响使用
* 如果你在安装此包前通过第三方软件源安装，可能导致意外的错误，例如本不需要libopenssl3，变得需要，此情况可能需要重置你的路由器。
* 自带clash核心的openclash，版本为0.46.014。如果安装完出现路由器断网，重启一次路由器。
* **注意，上述软件包安装，部分依赖依然要通过opkg软件源在线安装。如果安装失败，检查路由器自身的网络情况，特别是旁路由模式下最容易出现网络问题。**
* **再三注意需要路由器自身联网正常**

#### 其它软件包 Other Packages
|插件名|功能|下载|编译日期|
| :----: | :----: | :----: | :----: |
| [AdGuardHome](https://github.com/sirpdboy/sirpdboy-package) | DNS/拦截 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/adguardhome.run) |2024-06-30|
| [MosDNS](https://github.com/sbwml/luci-app-mosdns) | DNS 转发/分流器 | [mosdns_5.3.3-2](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/mosdns_5.3.3-2_aarch64_a53_all.run) |2024-10-03|
| [UnblockNeteaseMusic](https://github.com/UnblockNeteaseMusic/luci-app-unblockneteasemusic) | 解锁网易云灰色歌曲 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/unblockneteasemusic.run) |2024-09-15|
| ByPass | ByPass 科学工具 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/ByPass_a53.run) |N/A|
| VSSR | HelloWorld 科学工具 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/VSSR_a53.run) |N/A|
| ikoolproxy | koolproxy去广告(不适合高于5.4内核的固件) | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/ikoolproxy_a53.run) |N/A|
| Adblock | Adblock 去广告 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/adblock.run) |N/A|
| Adbyby | 广告屏蔽大师 Plus+ | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/adbyby_a53.run) |N/A|
| OpenVPN | OpenVPN客户端 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/OpenVPN_20211018.run) |N/A|
| OpenVPN-Server | OpenVPN服务端 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/OpenVPN-Server_a53.run) |N/A|
| JD-dailybonus | 某东签到(扫码早就gg，手动填cookie) | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/JD-dailybonus_20211105.run) |N/A|
| KMS | KMS服务器 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/KMS_a53.run) |N/A|
| NPS | Nps内网穿透 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/NPS_a53.run) |N/A|

#### 如何安装
* 下载后，来到iStore应用商店页面，点击手动安装，点击选择上传或者直接拖放文件
![png](https://cdn.jsdelivr.net/gh/AUK9527/Are-u-ok@master/apps/install.png)

* 对于没有iStore应用商店的OpenWrt也可以使用以下方法。

将 .run 文件上传到路由器上，然后在终端环境执行
```console
sh 包名.run
```
例
```console
sh PassWall_4.75-8_aarch64_a53_all_sdk_22.03.6.run
```
如果文件不在当前路径记得填写路径，下例
```console
sh /tmp/upload/PassWall_4.75-8_aarch64_a53_all_sdk_22.03.6.run
```
