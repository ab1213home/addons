# Home Assistant 应用：NGINX Home Assistant SSL 代理

使用 NGINX 设置 SSL 代理，并将流量从端口 80 重定向到 443。

![支持 aarch64 架构][aarch64-shield] ![支持 amd64 架构][amd64-shield]

## 关于

使用 NGINX Web 服务器设置 SSL 代理。它通常用于转发 SSL 互联网流量，同时允许与 Home Assistant 实例之间的未加密本地流量。

确保在启动此应用之前已生成证书。[Duck DNS](https://github.com/home-assistant/hassio-addons/tree/master/duckdns) 应用可以生成可被此应用使用的 Let's Encrypt 证书。

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
