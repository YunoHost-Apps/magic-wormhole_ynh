<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Magic-Wormhole

[![集成程度](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![工作状态](https://apps.yunohost.org/badge/state/wormhole)
![维护状态](https://apps.yunohost.org/badge/maintained/wormhole)

[![使用 YunoHost 安装 Magic-Wormhole](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Magic-Wormhole。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**分发版本：** 0.4.0~ynh1

**演示：** <https://demo.example.com>
## 文档与资源

- 官方应用网站： <https://example.com>
- 上游应用代码库： <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- YunoHost 商店： <https://apps.yunohost.org/app/wormhole>
- 报告 bug： <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
或
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
