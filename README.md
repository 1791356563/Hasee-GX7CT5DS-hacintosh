# Hasee-GX7CT5DS-hacintosh

- 神舟GX7-CT5DS黑苹果EFI
- 无需修改BIOS
- 屏蔽独显

 - 神舟GX8-CT5DT测试可用，但未优化,不保证正常使用
 - oc 0.79
 - 第三方主题
 - 理论上神舟GX7和GX8系列核显为UHD630的机器通用，可以拿去按自己的无线网卡修改，定制一下USB即可

## 配置信息

 - CPU i5 9400
 - GPU UHD630
 - SSD sumsang980
 - Wi-Fi intel ac9462/intel ax210

## 正常功能（monterey系统）

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
 - intel ax200以下蓝牙（由于monterey系统砍了蓝牙5.2，导致ax210等支持蓝牙5.2的蓝牙在monterey下可以驱动但不能使用）
 - handoff接力
 - iMessage
 - FaceTime

 ## 已知问题

 - 睡眠唤醒蓝牙有概率失效，必须重新开关才能使用，解决办法-脚本或手动开关
 - intel ax210等蓝牙5.2，解决办法-回Big Sur养老或更换蓝牙5.0网卡或博通免驱无线网卡
 - 隔空投送，解决办法-更换博通免驱无线网卡

