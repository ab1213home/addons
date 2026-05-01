# Home Assistant 应用：Silicon Labs Flasher

Silicon Labs Flasher 应用（formerly known as add-on），用于刷写基于 Silicon Labs 的无线电设备。

默认情况下，此应用刷写用于 Zigbee（Silicon Labs EmberZNet Zigbee 协议栈）的固件。

**注意：** 确保没有其他应用或集成正在使用该无线电设备。特别要禁用 Zigbee Home Automation 集成和 Silicon Labs Multiprotocol 应用。

![支持 aarch64 架构][aarch64-shield]
![支持 amd64 架构][amd64-shield]

## 关于

此应用允许您使用 Gecko Bootloader 文件格式（gbl）刷写固件。默认情况下，它包含用于 Home Assistant SkyConnect/ZBT-1 和 Home Assistant Yellow 刷写 Zigbee 的固件。

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
