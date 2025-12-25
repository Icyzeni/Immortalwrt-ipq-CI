# ImmortalWRT-CI
云编译ImmortalWRT固件

官方版：
https://github.com/immortalwrt/immortalwrt.git

高通版：
https://github.com/VIKINGYFY/immortalwrt.git

# U-BOOT

高通版：

https://github.com/chenxin527/uboot-ipq60xx-emmc-build

https://github.com/chenxin527/uboot-ipq60xx-nor-build

联发科版：

https://drive.wrt.moe/uboot/mediatek

# 固件简要说明

固件每周五早上6点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

MEDIATEK系列、QUALCOMMAX系列、ROCKCHIP系列、X86系列。

QUALCOMMAX系列：
 - 仅编译ipq60xx的固件（不支持WIFI），使用VIKINGYFY的源码，版本是SNAPSHOT的，安装包使用apk；

MEDIATEK系列、ROCKCHIP系列、X86系列：
 - 使用immortalwrt 24.10的源码，安装包使用ipk；

插件列表：
 - luci-theme-aurora
 - luci-app-aurora-config 
 - luci-app-autoreboot 
 - luci-app-bandix 
 - luci-app-easytier 
 - luci-app-firewall 
 - luci-app-frpc 
 - luci-app-gecoosac 
 - luci-app-homeproxy 
 - luci-app-openclash 
 - luci-app-package-manager 
 - luci-app-partexp 
 - luci-app-samba4 
 - luci-app-ttyd 
 - luci-app-upnp 
 - luci-app-wolplus 

# 目录简要说明

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置

#
