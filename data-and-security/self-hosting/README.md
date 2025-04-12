# 网络与备份

### Anytype 网络

默认情况下，当用户创建一个新的存储库（vault）时，他们都会加入 Anytype 网络。如果需要，之后可以切换到 [仅限本地模式](local-only.md "mention") 或 [自托管模式](self-hosted.md "mention")。

每位 Anytype 用户都可以访问由 Anytype 提供的远程备份节点。目前，该节点的容量限制为 **1 GB**。对象和其他内容不会影响此限制；只有文件受到限制。如果您超出限制，系统会发出警告，并且您可以申请更多存储空间。

我们的备份节点位于瑞士，并使用 AWS（Amazon Web Services）。

我们用于 Anytype 网络的域名包括：

* 用于同步：`*.anyclub.org`
* 用于分析：`*.anytype.io`

---

### 如何切换回 Anytype 网络

我们强烈建议为每个网络使用专用的身份（identity）。如果您从自托管网络切换，请先导出所有空间，并在网络模式切换后将它们导入到新的身份中。

请注意，您的所有设备都需要手动切换到 Anytype 网络模式。

#### 桌面端

1. 从当前身份注销。
2. 在初始设置屏幕上，点击右上角的齿轮图标。
3. 在“网络”字段中选择“Anytype”选项。
4. 点击“保存”按钮。
5. 创建一个新身份或使用现有身份登录。

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

#### 移动端

1. 从当前身份注销。
2. 在初始设置屏幕上，点击右上角的齿轮图标。
3. 在“网络”子菜单中点击“Anytype”选项。
4. 创建一个新身份或使用现有身份登录。

<figure><img src="../../.gitbook/assets/Screenshot_20240411-104810_Anytype2.png" alt="" width="375"><figcaption></figcaption></figure>

---

### 注意事项

- **数据迁移：** 如果您从其他网络（如自托管模式）切换回 Anytype 网络，请确保在切换之前导出所有数据，并在新身份中重新导入，以避免数据丢失。
- **设备同步：** 切换网络模式后，所有设备都需要手动调整到相同的网络模式才能继续同步。
- **存储限制：** 如果您接近或超过 1 GB 的存储限制，请及时管理文件，或者联系 Anytype 团队申请额外存储空间。
- **隐私与安全：** Anytype 备份节点位于瑞士，确保数据隐私和安全性。不过，如果您对数据隐私有更高要求，可以考虑使用 [仅限本地模式](local-only.md "mention") 或 [自托管模式](self-hosted.md "mention")。