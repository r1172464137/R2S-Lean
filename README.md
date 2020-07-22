抄大佬作业系列之：  
# 在线编译 [Chuck](https://github.com/fanck0605) 大佬的 [openwrt-nanopi-r2s](https://github.com/fanck0605/openwrt-nanopi-r2s)  
    clone Chuck 大佬项目的 openwrt-lean 分支，并做一定调整，提交 Actions 编译  

## 一、固件特性  
    在 Chuck 大佬项目的基础上做如下修改：  
        1. 插件仅包含： SSRP、京东签到  
        2. 主题包含： Argon(默认)、BootStrap  
        3. 提供 EXT4FS 和 SQUASHFS 两种类型固件  
        4. wan口 lan口 位置恢复默认(不互换)  
        5. 添加 IPv6 支持(默认关闭，可在 网络-DHCP/DNS-高级设置 处开启)
        6. 软件源更改为： 腾讯软件源  
        7. 默认LAN口IP：192.168.1.1  
        8. 默认用户、密码：root 无  

## 二、固件下载地址  
  → [戳这里哦](https://github.com/RikudouPatrickstar/R2S-Lean/releases) ←  

## 三、感谢  
   感谢所有提供了上游项目代码和给予了帮助的大佬们  
