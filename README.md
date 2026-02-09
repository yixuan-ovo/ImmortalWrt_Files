## Aron Wallpaper
luci-app-argon主题替换壁纸

## 需求版本
~~Xiaomi Redmi Router AX6000 (stock layout)~~

GL.iNet GL-MT6000

## 官方镜像版本、系统配置文件备份

## 增加不死uboot更新

- https://github.com/hanwckf/bl-mt798x

- https://cmi.hanwckf.top/p/mt798x-uboot-usage/

如果要使用webui更新uboot，可以访问http://192.168.31.1/uboot.html,选择FIP格式的uboot二进制并上传刷入即可

**文件名:mt7986_redmi_ax6000-fip-fixed-parts-multi-layout.bin**

## 参考教程链接:

https://blog.zwbcc.cn/archives/1698143124429

https://help.mirrors.cernet.edu.cn/immortalwrt/

https://cmi.hanwckf.top/p/mt798x-uboot-usage/

https://docs.gl-inet.cn/router/4/faq/upgrade_uboot_version/

## 常用软件包名

| 包名 | 备注 |
|------|------|
| luci-theme-argon | **Argon 主题** |
| luci-app-adguardhome | **最新版 CN 语言包 bug 解决见 adhome_config** |
| luci-app-openclash | |
| luci-app-upnp | 安装 zh-cn 语言包，其余自动安装 |
| luci-app-tailscale | 参考[这个教程安装](https://gunanovo.github.io/openwrt-tailscale/) |