# 获取应用

您可以在 [download.anytype.io](https://download.anytype.io) 下载适用于您设备的最新版本 Anytype。

目前没有 [浏览器版本](../miscellaneous/faqs.md#为什么-anytype-没有浏览器版本) 的应用。

### 最低配置要求

* 对于桌面端，Electron 遵循 Chrome 的支持策略，而 Chrome 遵循 [供应商支持政策](https://support.google.com/chrome/a/answer/7100626?hl=en)。\
  目前这意味着：
  * Windows 10 及以上
  * macOS Catalina 10.15 及以上
  * 64 位 Ubuntu 18.04+、Debian 10+、openSUSE 15.5+ 或 Fedora Linux 38+
* 对于 Android（如果通过 Google Play 安装），需要 Android 8.0 及以上，并且设备为 64 位，至少具备 4GB RAM。
* 对于 iOS，需要 iOS 16。

### 安装位置

Anytype 的安装位置如下：

* 在 Windows 10 或更高版本中，通常位于：\
  `C:\Users\<username>\Appdata\Local\Programs\anytype`\
  **username** 表示您的用户名或工作目录名称。
* 对于 MacOS，安装路径为：`HDD > Users >`_`Username`_`> Library > Application Support > anytype`
* 对于 Linux，您可以在 `~/.config/anytype` 找到工作目录。
* 对于 Android，通常位于默认路径：\_device/data/app\_​。\
  我们还存储了一些缓存文件：_device/data/data/io.anytype.app_\
  Anytype 目录存储在受保护的应用数据文件夹中，Android 设备用户无法直接访问。
* 对于 iOS，安装路径由 iOS 系统决定。

### 自定义存储位置

创建 Vault 时，现在可以选择存储位置在硬盘上的路径。如果您的 Vault 已经创建完成，您也可以更改存储位置并从网络中检索数据。为此，请先登出，然后点击黑色登录屏幕上的设置齿轮图标。

<figure><img src="../.gitbook/assets/Custome Storage Location.gif" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="danger" %}
请注意，在使用本地模式时要格外小心，因为您的数据只能通过点对点（P2P）连接传输到第二台设备。
{% endhint %}

#### 外部驱动器和云提供商

要将数据存储在外接驱动器上，您只需先挂载驱动器，然后按照 [#自定义存储位置](get-the-app.md#custom-storage-location "提及") 的步骤操作即可。

我们不建议使用 Google Drive 或 iCloud 等云服务提供商，因为可能会导致同步冲突或问题。
