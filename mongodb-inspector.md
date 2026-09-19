# MongoDB Inspector — End-User License Agreement (EULA)

Copyright (c) 2026 Hongtao Ren

## 1. License / 授权

The free features of this plugin (connecting to a MongoDB server, browsing databases and
collections, running a JSON filter, and viewing documents) may be used free of charge.

Features marked "Pro" (currently: exporting documents to JSON, and inspecting collection
indexes) require a valid paid license.

本插件的免费功能（连接 MongoDB 服务器、浏览数据库与集合、执行 JSON 过滤查询、查看文档）可免费使用。
标注 "Pro" 的功能（当前为：导出文档为 JSON、查看集合索引）需要购买有效许可后方可使用。

## 2. Restrictions / 限制

You may not reverse engineer, redistribute, or resell this plugin without written
permission from the author.

未经作者书面许可，不得对本插件进行反向工程、二次分发或出售。

## 3. Read-only by design / 只读设计

The free tier never writes to your database: it issues read commands only. Data modification is
not offered in any tier. You remain responsible for the credentials you enter —
connection strings are stored per project in your IDE settings.

免费版不会对数据库执行任何写操作，仅发送读取命令。本插件任何版本均不提供数据修改功能。
您对输入的连接凭据自行负责——连接串按项目存放在您的 IDE 设置中。

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

## 6. Third-party components / 第三方组件

This plugin bundles the official MongoDB Java driver (mongodb-driver-sync, bson,
mongodb-driver-core), licensed under the Apache License 2.0.

本插件打包了 MongoDB 官方 Java 驱动（mongodb-driver-sync、bson、mongodb-driver-core），
其许可为 Apache License 2.0。
