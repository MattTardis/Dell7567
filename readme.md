 ## forked from Doapeat/Dell7567，感谢大佬
 *这只是一个简单维护的EFI

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
	
## 无法工作的部分

- 独立显卡，因为macOS不支持Optimus技术
- Intel无线网卡，请自行更换


## 闲扯


&emsp;&emsp;自带Intel无线网卡无法驱动，可尝试更换DW1560、DW1820A。
&emsp;&emsp;


## 更新日志

* 19.4.8
	* 更新Clover及Kext，已在实机安装使用测试过。

## 如果你认可我的努力，可以点一个Star，感谢


## 感谢浏览！！！
