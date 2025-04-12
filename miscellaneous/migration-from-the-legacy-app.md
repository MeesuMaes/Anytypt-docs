---
description: 针对 Alpha 测试者的迁移指南
---

# 从旧版应用（Legacy App）迁移

#### **如何迁移？**

如果您在 Alpha/旧版（0.31.* 及更早版本）中创建了想要保留的内容，则需要将其迁移到新版本。迁移过程相对简单，以下是具体步骤：

1.  更新您的桌面版旧版应用到最新版本（0.31.9）。您可以通过 `Anytype > 检查更新` 或[通过此链接](https://download.anytype.io/?ref=migration&platform=desktop)完成更新。

    <div align="left">

    <figure><img src="../.gitbook/assets/Check updates.png" alt="" width="331"><figcaption></figcaption></figure>

    </div>
2.  在更新后的旧版应用中导出数据：`文件 > 导出 > Protobuf`。

    <div align="left">

    <figure><img src="../.gitbook/assets/Anytype Export.gif" alt="" width="336"><figcaption></figcaption></figure>

    </div>
3. [下载](https://download.anytype.io/)、安装并打开 Beta 版应用。
4. 将备份文件导入到 Beta 版应用中。

如需更多详细信息，请查看我们的[迁移指南](https://community.anytype.io/t/anytype-legacy-to-beta-migration-trail-guide/9274)。

---

#### **如何下载最新的 Alpha（旧版）应用**

如果您在导出数据之前已经删除了 Alpha 应用，可能需要重新下载它以完成导出。您可以通过[以下链接](https://download.anytype.io/?ref=migration&platform=desktop)下载适用于 Mac、Windows 和 Linux 的 0.31.9 桌面版应用。

---

#### **如何跳过备份导入步骤？**

如果您不想迁移，可以选择以下替代方案：

*   创建一个新的存储库（Vault）。启动应用时，选择“加入（Join）”而不是“登录（Login）”。

    <div align="left">

    <figure><img src="../.gitbook/assets/Join Anytype.png" alt="" width="354"><figcaption></figcaption></figure>

    </div>
* 手动将选定的对象从旧版逐个导入到 Beta 版。如果您的旧版存储库/账户变得杂乱无章，但您希望将一些项目转移到 Beta 版，可以选择此方法。

对于这些选项，您需要创建一个新的存储库，这将生成一个新的密钥（Key）。

---

#### **故障排除**

* 错误提示：“open profile: file does not exist”
  * 原因：这是由于使用了较旧的旧版应用（例如 0.31.0）。
  * 解决方案：按照上述说明更新旧版应用。
* 错误提示：“can't run service 'client.clientspace': EOF”
  * 原因：可能是旧版应用未正确更新或数据损坏。
  * 解决方案：确保旧版应用已更新到最新版本，并重新尝试导出和导入操作。

---

如果您遇到其他问题或需要进一步帮助，请访问我们的社区论坛或联系支持团队。