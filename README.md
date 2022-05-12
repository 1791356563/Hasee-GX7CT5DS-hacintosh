# Hasee-GX7CT5DS-hacintosh

 - 神舟GX7-CT5DS黑苹果EFI
 - 更新于20220512
 - 无需修改BIOS
 - 屏蔽独显
 - 神舟GX8-CT5DT测试可用，但未优化,不保证正常使用
 - ~~oc 0.79~~ oc 0.8.0
 - 第三方主题
 - 理论上神舟GX7和GX8系列核显为UHD630的机器通用，可以拿去按自己的无线网卡修改，定制一下USB即可

## 配置信息

 - CPU i5 9400
 - GPU UHD630
 - SSD sumsang980
 - Wi-Fi intel ax210 ~~/intel ac9462~~

## 正常功能

 - 核显硬解
 - 触摸板
 - 声卡
 - 麦克风
 - 摄像头
 - 有线网卡
 - USB端口定制
 - 电池电源管理
 - 睡眠唤醒
 - 屏幕镜像
 - 屏幕亮度调节
 - intel Wi-Fi
 - intel蓝牙（由于monterey系统砍了蓝牙5.2，导致ax210等支持蓝牙5.2的蓝牙在monterey下可以驱动但不能使用）
 - handoff接力
 - iMessage
 - FaceTime

## 性能

 - cpu单核跑分比windows略低但差距不大，多核性能比win更高
 - GPU比windows下低10-15%（打游戏基本上别指望了，装双系统切换Windows下游玩吧）

## 已知问题

 - 睡眠唤醒蓝牙有概率失效，必须重新开关才能使用，解决办法-脚本或手动开关
 - intel ax210等蓝牙5.2，解决办法-回Big Sur养老或更换蓝牙5.0网卡或博通免驱无线网卡
 - 隔空投送，解决办法-更换博通免驱无线网卡

# 其他说明

- 默认config.plist为Big Sur版本，如需使用其他版本（例如Monterey），可将config-monterey改名为config.plist使用，catalina和Big Sur和Monterey三个版本的config配置都不一样，主要是intel网卡和蓝牙的缘故
- 默认你的机器开启了CFG-lock，如果你和我一样刷了bios，解锁了高级菜单并且关闭了CFG-lock，可以去`config>kernel>quirks`里取消勾选 `AppleCpuPmCfgLock` 和 `AppleXcpmCfgLock`
- 触摸板如需体验妙控板（伪妙控板，我觉得很不好用），请将`config>kernel`里的`VoodooPS2Controller.kext/Contents/PlugIns/VoodooPS2Trackpad.kext驱`动打勾

# 已测试

- 大版本更新（从catalina直接更新big sur，或从big sur直接更新到monterey）

# 暂未测试

 - 时间机器

# 随缘更新，出问题请自行上网查询

# 资源均来源于互联网，如有侵权请联系删除



   

