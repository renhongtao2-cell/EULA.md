# Keystore Inspector — End-User License Agreement (EULA)

Copyright (c) 2026 Hongtao Ren

## 1. License / 授权

The free features of this plugin — opening `.jks`, `.pkcs12`, `.p12` and `.pfx` files in the
IDE, browsing entries, expiry highlighting, and full certificate details (subject, issuer,
validity, SAN, key algorithm, SHA-256 fingerprint) — may be used free of charge.

Features marked "Pro" require a valid paid subscription: exporting any certificate or private
key to PEM, and migrating an entire keystore from JKS to PKCS12.

本插件的免费功能——在 IDE 中打开 `.jks`/`.pkcs12`/`.p12`/`.pfx` 文件、浏览条目、
到期高亮、查看完整证书信息（主体、颁发者、有效期、SAN、密钥算法、SHA-256 指纹）——可免费使用。

标注 "Pro" 的功能需要购买有效订阅：将任意证书或私钥导出为 PEM，以及将整个密钥库从 JKS 迁移为 PKCS12。

## 2. Subscription terms / 订阅条款

Pro is sold as an annual subscription through JetBrains Marketplace, with a 30-day free trial.
Payment, invoicing, refunds and license delivery are handled by JetBrains Marketplace under its
own terms. The license is verified through the JetBrains Marketplace licensing service; the
plugin does not receive or store your payment details.

Pro 通过 JetBrains Marketplace 按年订阅销售，含 30 天免费试用。付款、开票、退款与许可发放
均由 JetBrains Marketplace 按其条款处理。许可通过 JetBrains Marketplace 许可服务校验，
本插件不接触也不存储您的支付信息。

## 3. Restrictions / 限制

You may not reverse engineer, redistribute, or resell this plugin without written
permission from the author.

未经作者书面许可，不得对本插件进行反向工程、二次分发或出售。

## 4. Read-only by design / 只读设计

Inspection never modifies your keystore: files are opened read-only. The only operations that
write anything are the Pro actions you explicitly invoke, and they never overwrite the original
file in place without your confirmation.

查看过程不会修改您的密钥库：文件以只读方式打开。仅当您主动触发 Pro 操作时才会产生写入，
且不会在未经确认的情况下覆盖原文件。

## 5. Disclaimer / 免责声明

This plugin is provided "as is" without warranty of any kind. The author shall not be
liable for any damages arising from its use. Always back up important data first.

本插件按“现状”提供，不含任何明示或暗示的担保。作者对使用本插件造成的任何直接或间接损失不承担责任。
使用前请自行备份重要数据。

## 6. Privacy / 隐私

The plugin runs entirely on your machine. No file content, credential or query is sent
to any third-party server, except the plugin's own license verification performed by
JetBrains Marketplace.

本插件完全在您的机器上运行。除 JetBrains Marketplace 执行的插件自身许可校验外，
任何文件内容、凭据或查询都不会发送给第三方服务器。
