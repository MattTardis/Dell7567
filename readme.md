

| 配置 / Hardware | 详情 / Detail|
| ------ | ------ | 
| 型号 / Model | Dell Inspiron 15 7000 Gaming (7567) |
| 操作系统 / OS | macOS Mojave 18A389 |
| 处理器 / CPU | Intel Core i7-7700HQ @ 2.80GHz |
| 内存 / Memory|  8 GB ( Hynix DDR4 2400MHz )|
| 硬盘 / HardDrive| WDC WDS250G2B0B  TOSHIBA MQ01ABD100|
| 显卡 / Graphics Card| Intel HD Graphics 630 (platform-id:0x591B0000) |
| 声卡 / Sound Card | Realtek ALC256 ( layout-id:2/56 )|
| 网卡 / Network Card | 未经测试 |

## 需要注意的事情
* 1.适配系统：macOS 10.14.4 已安装并测试

* 2.本人并没有7567，感谢一位朋友的测试支持  

* 3.初次安装:
	* (1).为了使Clover正常启动，请在开机时使用F2进入BIOS并关闭安全启动(Security Boot)。

	* (2).为了使macOS正常读取内置硬盘及防止禁行，请在BIOS中将硬盘模式改为AHCI。

	* (3).请确保ESP分区总空间大于200M。

## 图片欣赏

![01Pic05](./Pictures/ScreenShot/Pic05.png)

![02WIFI](./Pictures/ScreenShot/WIFI.png)

![07 Graphics](./Pictures/ScreenShot/Graphics.png)

![08 Power](./Pictures/ScreenShot/Power.png)

![04 Audio](./Pictures/ScreenShot/AUDIO.png)

![05 VOL](./Pictures/ScreenShot/Vol.png)

![06 BT](./Pictures/ScreenShot/BT.png)

![03 5G](./Pictures/ScreenShot/5G.png)
>5Ghz和2.4Ghz的蓝牙不冲突


![09 CPU-S](./Pictures/ScreenShot/CPU-S.png)
>变频24档足够了吧


## 闲扯


&emsp;&emsp;自带Intel无线网卡无法驱动，可尝试更换DW1560、DW1820A。
&emsp;&emsp;


## 更新日志

* 2018.10.13
	* 首次发布，所有使用的驱动都是当前最新。
* 2018.11.24
	* 路由器使用了5Ghz，蓝牙正常！宿舍8M内都正常！听了20min不存在断开连接！
	* USBInjectAll.kext 更新到2018-11-08 (0.7.1)，FakePCIID_Broadcom_WiFi.kext 和 FakePCIID.kext更新到2018-1027，来自RehubMan大神，感谢！！！
	* 更新几张图片（有的是上次截的，忘了放在这里面）。
* 2018.12.3
	* 添加了ALCPlugFix，这个补丁是用来修复耳机破音，源自网络 ，里面有用法说明，感谢制作此补丁的大婶！！！
* 2018.12.11
	* Clover更新到Clover_v2.4k_r4701.RM-4963.ca6cca7c，来自RehubMan，感谢！
	* 去掉了FakePCIID_Broadcom_WiFi.kext，没换网卡的有这个也没用！
	* 修复了Clover引导界面卡的问题，大家说的Clover界面卡的问题我试了5次，没复现卡的情况，经一个好友反馈，卡顿的情况也不再出现，初步判断是因为用了太花哨的主题，占用资源过多导致。

## 如果你认可我的努力，可以点一个Star，感谢


## 感谢浏览！！！
