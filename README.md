### 修改自 骷颅头R4S OpenWrt固件
https://github.com/DHDAXCW/NanoPi-R4S-R4SE
### 源代码地址
- lede https://github.com/DHDAXCW/lede-rockchip
- Luci https://github.com/DHDAXCW/luci
- packages https://github.com/DHDAXCW/packages


- docker版：全插件+docker
- 风扇链接 [点击进入](https://s.click.taobao.com/t?e=m%3D2%26s%3Dd8Ack0Lbx8McQipKwQzePOeEDrYVVa64LKpWJ%2Bin0XJRAdhuF14FMXpyNmcFd6mT8sviUM61dt2T0mcOGN1M6FAj1gqltKaEfKzCcEr0EW0YuhTK3FPxiHMT7yc3NZrQKSOkJV8harV3phaPbavinqGCwVfdcN0wcSpj5qSCmbA%3D)  建议用这种风扇

### 固件格式
- **ext4:** 固件文件名中带有 ext4 字样的文件为搭载 ext4 文件系统固件ext4 格式的固件更适合熟悉 Linux 系统的用户使用，在 Linux 下可以比较方便地调整 ext4 分区的大小;
- **squashfs:** 固件文件名中带有 squashfs 字样的文件为搭载 squashfs 文件系统固件而 squashfs 格式的固件适用于“不折腾” 的用户，其优点是可以比较方便地进行系统还原哪怕你一不小心玩坏固件，只要还能进入控制面板或 SSH就可以很方便地进行“系统还原操作”。

### 注：不要用恢复备份。。不保证某个插件是否正常运行。。。建议重新设置贼好！

### 默认编译  

- 用户名：root 密码：password  管理IP：192.168.11.1
- 关于r4se刷机方法请参考dn2刷机 https://github.com/DHDAXCW/DoorNet-1-2/blob/mere/emmc.md


# 插件展示
 
 ![image](https://user-images.githubusercontent.com/74764072/183227361-e8bdb023-5514-437d-97e8-e13ca4285035.png)
 
### AES跑分
 ![image](https://user-images.githubusercontent.com/74764072/183227382-7dd4c7e9-b2b4-4471-b867-3963bdd6c7a2.png)
### HTOP
 ![image](https://user-images.githubusercontent.com/74764072/183227388-8a51ed5f-282b-4154-9be2-3abe26387dd7.png)


## 鸣谢

特别感谢以下项目：

Openwrt 官方项目：

<https://github.com/openwrt/openwrt>

Lean 大的 Openwrt 项目：

<https://github.com/coolsnowwolf/lede>

immortalwrt 的 OpenWrt 项目：

<https://github.com/immortalwrt/immortalwrt>

P3TERX 大佬的 Actions-OpenWrt 项目：

<https://github.com/P3TERX/Actions-OpenWrt>

SuLingGG 大佬的 Actions 编译框架 项目：

https://github.com/SuLingGG/OpenWrt-Rpi
