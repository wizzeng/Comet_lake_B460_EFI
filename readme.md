# Comet Lake EFI Configuration

## 配置

|配置|型号|备注|
|---|---|---|
|CPU|I5 10500ES QSRK| 暂未发现明显 Bug |
|主板|昂达B460魔剑版|EFI可通用B460的丐版|
|内存|光威 DDR4 8G 2666 X2|-|
|声卡| Realtek ALC892 | - |
|显卡| Intel UHD 630| 暂时不是完美驱动，购置 RX 460 中|
|硬盘| 西部数据 SN730 256GB| - |
|网卡| Realtek 8111H | - |

## Issues

- 核显不能完美集成显示 + 计算，单核显大量应用显卡加速异常闪退，最好添加免驱显卡
- 黑苹果网卡 BCM94352Z 待添加

## 参考链接

- [AppleALC layout 列表](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs)
- [OpenCore 官方教程](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html)
- [司波图 - CometLake十代Intel平台台式机Opencore黑苹果通用配置教程](https://www.bilibili.com/video/BV1uf4y1X7MT)
