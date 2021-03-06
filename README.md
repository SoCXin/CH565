﻿# [CH565](https://github.com/SoCXin/CH565)

[![sites](http://182.61.61.133/link/resources/SoC.png)](http://www.SoC.Xin)

#### [Vendor](https://github.com/SoCXin/Vendor)：[WCH](https://github.com/SoCXin/WCH)
#### [Core](https://github.com/SoCXin/RISC-V)：[RISC-V3A](https://github.com/SoCXin/RISC-V)
#### [Level](https://github.com/SoCXin/Level)：120MHz

### [CH565 简介](https://github.com/SoCXin/CH565/wiki)

[CH565](https://github.com/SoCXin/CH565) 使用120MHz主频RISC-V3A内核，单周期乘法和硬件除法、低功耗两级流水线，支持RISC-V指令的 IMAC子集。

448KB CodeFlash，32KB DataFlash，16KB的32位SRAM，32/64/96KB可配置的128位宽SRAM

片上集成超高速USB3.0主机和设备控制器（内置 PHY）、专用高速 SerDes 控制器（内置 PHY，可直接驱动光纤）、数字视频接口（DVP）、SD/EMMC 接口控制器、加解密模块 ， 片上 128 位宽 DMA设计可保障大数据量的高速传输， 可广泛应用于流媒体、即时存储、超高速USB3.0 FIFO、通讯延长、安防监控等应用场景。


[![sites](docs/CH565.png)](http://www.wch.cn/products/CH565.html?)

##### 关键特性

* 内置数字视频接口DVP，可配置8/10/12位数据宽度，支持YUV、RGB、JPEG压缩数据
* 超高速USB3.0控制及收发器（内置PHY），支持主机/设备模式、OTG功能，支持HUB
* 千兆以太网控制器（Ethernet），提供RGMII和RMII PHY接口（外部连接），支持1000Mbps传输速率
* 内置SerDes控制及收发器（内置PHY，可直接驱动光纤），支持网线（仅使用1组差分线）传输90米，支持1.25Gbps高速差分信号通讯
* EMMC控制器支持单线、4线、8线数据通讯模式，符合EMMC卡4.4和4.5.1规范，兼容5.0规范
* 支持AES/SM4算法，8种组合加解密模式，支持SRAM/EMMC/HSPI外设接口数据加解密
* SPI x 2 + UART x 4 (16C550/波特率6Mbps/多触发级FIFO)
* 封装(QFN68/QFN40)


### [选型建议](https://github.com/SoCXin)

[CH565](https://github.com/SoCXin/CH565) 和 [CH569](https://github.com/SoCXin/CH569)规格相当，差异在，前者有DVP接口，后者有HSPI接口。
###  [SoC芯平台](http://www.SoC.Xin)
