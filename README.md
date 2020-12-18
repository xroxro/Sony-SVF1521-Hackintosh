# Sony-SVF1521-Hackintosh

## 电脑配置
|配置|型号|
|----|----|
|系统|macOS 10.14|
|CPU|Intel Core i5-3337u 2核4线程|
|主板|Sony SVF1521|
|显卡|Intel HD Graphics 4000 （屏蔽Geforce GT 740）|
|内存|DDR3 1600MHz 6GB(2+4)|
|硬盘|三星860Pro SSD 128GB SSD|
|声卡|Realtek |
|SMBIOS|MacBookPro9,2|
|引导|Clover5127|

## 正常工作

- [x] APFS
- [x] CPU 变频
- [x] 休眠唤醒
- [x] HD4000 GPU 加速 (禁用 eGPU GT740)
- [x] Video encoder/decoder hardware (H.264)
- [x] 屏幕亮度调节
- [x] All USB ports at their max speed (manually mapped)
- [x] Gigabit Ethernet
- [x] WIFI 替换为BCM93422
- [x] 触摸板（双指手势，部分三指手势）
- [x] Onboard Audio + Integrated Speaker
- [x] All iCloud Services
- [x] App Store
- [x] Sensors (Temperature)
- [x] Built in HDMI
- [x] TRIM enabled for SATA SSD
- [x] Time Machine
- [x] Seamless software updates

## 不工作
-  Fn 快捷键亮度控制
-  原装无线网卡不工作需要替换
-  原装蓝牙不工作需要替换
-  读卡器不工作
-  盒盖开盖无反应
-  macOS Catalina 10.15 安装程序引导过程中内核崩溃，原因未知，请不要尝试。
