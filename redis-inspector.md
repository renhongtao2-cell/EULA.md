# Redis Inspector — End-User License Agreement (EULA)

Copyright (c) 2026 Hongtao Ren

## 1. License / 授权

This plugin is free of charge. You may use it, including in commercial work, at no cost.
It is a read-only inspection tool for Redis servers: connecting, browsing keys, and inspecting
values and TTLs.

本插件免费提供，包括商业用途在内均可无偿使用。它是 Redis 服务器的只读查看工具：
连接、浏览键、查看值与过期时间。

## 2. Restrictions / 限制

You may not reverse engineer, redistribute, or resell this plugin without written
permission from the author.

未经作者书面许可，不得对本插件进行反向工程、二次分发或出售。

## 3. Read-only by design / 只读设计

The plugin issues read commands only and never writes to your Redis server. You remain
responsible for the credentials you enter — connection settings are stored per project in your
IDE settings.

本插件仅发送读取命令，不会对您的 Redis 服务器执行写入。您对输入的凭据自行负责——
连接配置按项目存放在您的 IDE 设置中。

## 4. Disclaimer / 免责声明

This plugin is provided "as is" without warranty of any kind. The author shall not be
liable for any damages arising from its use. Always back up important data first.

本插件按“现状”提供，不含任何明示或暗示的担保。作者对使用本插件造成的任何直接或间接损失不承担责任。
使用前请自行备份重要数据。

## 5. Privacy / 隐私

The plugin runs entirely on your machine. No file content, credential or query is sent
to any third-party server, except the plugin's own license verification performed by
JetBrains Marketplace.

本插件完全在您的机器上运行。除 JetBrains Marketplace 执行的插件自身许可校验外，
任何文件内容、凭据或查询都不会发送给第三方服务器。
