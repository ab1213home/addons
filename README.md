# Home Assistant 应用：官方仓库

应用（formerly known as add-ons）允许您扩展 Home Assistant 设置的功能。这些应用可以包含 Home Assistant 可以集成的应用程序（例如 [MQTT broker](/mosquitto/README.md) 或 [数据库服务器](/mariadb/README.md)），或者允许访问您的 Home Assistant 配置（例如通过 [Samba](/samba/README.md) 或使用 [文件编辑器](/configurator/README.md)）。

应用可以通过已安装 Home Assistant 的系统上的 Home Assistant 前端进行安装和配置。

[![Home Assistant - Open Home Foundation 项目](https://www.openhomefoundation.org/badges/home-assistant.png)](https://www.openhomefoundation.org/)

## 本仓库提供的应用

- **[CEC Scanner](/cec_scan/README.md)**

    扫描并发现 HDMI CEC 设备及其地址。

- **[deCONZ](/deconz/README.md)**

    使用 dresden elektronik 的 ConBee 或 RaspBee 硬件控制 Zigbee 网络。

- **[Dnsmasq](/dnsmasq/README.md)**

    一个简单的 DNS 服务器。

- **[Duck DNS](/duckdns/README.md)**

    通过 Let's Encrypt 自动更新您的 Duck DNS IP 地址并提供集成的 HTTPS 支持。

- **[文件编辑器](/configurator/README.md)**

    用于 Home Assistant 的简单基于浏览器的文件编辑器。

- **[Git pull](/git_pull/README.md)**

    从 Git 仓库加载和更新 Home Assistant 的配置文件。

- **[Let's Encrypt](/letsencrypt/README.md)**

    管理和创建 Let's Encrypt 证书。

- **[MariaDB](/mariadb/README.md)**

    Home Assistant 的 MariaDB 数据库。

- **[Mosquitto broker](/mosquitto/README.md)**

    一个开源 MQTT broker。

- **[NGINX Home Assistant SSL 代理](/nginx_proxy/README.md)**

    使用 NGINX 设置 SSL 代理，并将流量从端口 80 重定向到 443。

- **[RPC Shutdown](/rpc_shutdown/README.md)**

    远程关闭 Windows 机器。

- **[Samba 共享](/samba/README.md)**

    使用 Windows 文件共享通过网络共享您的配置。

- **[SSH 服务器](/ssh/README.md)**

    允许使用 SSH 或通过 Ingress 的 Web 终端远程登录 Home Assistant。

- **[Z-Wave JS](/zwave_js/README.md)**

    允许 Home Assistant 通过 USB 控制器与 Z-Wave 网络通信。

## 支持

有问题吗？

您有以下几个选项可以获得解答：

- [Home Assistant Discord 聊天服务器][discord]。
- Home Assistant [社区论坛][forum]。
- 加入 [Reddit 子版块][reddit]，网址为 [/r/homeassistant][reddit]。

如果您发现了 bug，请 [在我们的 GitHub 上提交 issue][issue]。

## 开发您自己的应用

如果您对开发自己的应用感兴趣，这个仓库可以是一个很好的灵感来源。有关开发应用的更多信息，请参阅我们的
[开发者文档][dev-docs]。

[discord]: https://www.home-assistant.io/join-chat
[forum]: https://community.home-assistant.io
[issue]: https://github.com/home-assistant/addons/issues
[reddit]: https://reddit.com/r/homeassistant
[dev-docs]: https://developers.home-assistant.io/docs/add-ons/
