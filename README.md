# tl-wdr5800v1

添加机型：
tl-wdr5800v1
（for https://github.com/coolsnowwolf/lede）

grep -irl wdr6500 ./*

1.【修改文件】

/target/linux/ath79/image/generic-tp-link.mk

/target/linux/ath79/generic/base-files/etc/hotplug.d/firmware/11-ath10k-caldata

/target/linux/ath79/generic/base-files/etc/board.d/02_network

/target/linux/ath79/generic/base-files/etc/board.d/01_leds


2.【新增文件】

/target/linux/ath79/dts/qca9561_tplink_tl-wdr5800-v1.dts


tl-wdr5800 v1

出厂配置：

cpu：qca9561

内存：64MB（已硬改为128MB）

闪存：8MB（已硬改为16MB）

5GHz WiFi芯片：qca9887

网口（100Mbps）：W L L L L
