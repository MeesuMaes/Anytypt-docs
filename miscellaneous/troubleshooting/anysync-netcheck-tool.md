# AnySync Netcheck 工具

这是一个简单的工具，用于检查连接到 Anytype 节点的能力。它旨在测试网络和 TLS（同步）相关的问题。

_Netcheck_ 工具通过连接到协调节点（coordinator nodes），使用 **libp2p 协议** 和 **AnySync 握手** 建立通信，并尝试执行网络配置请求。

---

### 下载 <a href="#p-42130-download-2" id="p-42130-download-2"></a>

您可以根据您的操作系统在此处下载对应版本：

{% embed url="https://github.com/anyproto/any-sync-tools/releases" %}

.zip 文件中包含我们所有的工具，但同步检查过程仅需要 **“any-sync-netcheck”** 文件。  
（另一个文件是我们的 [自托管工具](https://github.com/anyproto/any-sync-tools/blob/main/any-sync-network/README.md)。）

---

### 安装 <a href="#p-42130-installation-3" id="p-42130-installation-3"></a>

**从源代码构建：**

```bash
go install github.com/anyproto/any-sync-tools/any-sync-netcheck@latest
```

---

#### 运行工具 <a href="#p-42130-runing-the-tool-5" id="p-42130-runing-the-tool-5"></a>

运行以下文件：

* `any-sync-netcheck`
* 或者使用 `any-sync-netcheck -v` 以获取详细输出（verbose 输出）。

---

#### 结果 <a href="#p-42130-result-6" id="p-42130-result-6"></a>

*   如果您的同步功能 **正常工作**，输出日志应类似于以下内容：

    <figure><img src="../../.gitbook/assets/Screenshot 2023-08-02 at 16.40.02.png" alt=""><figcaption></figcaption></figure>
* **如果工具检测到任何错误：** 请提供有关您网络设置的所有详细信息，包括 VPN、代理、防火墙和杀毒软件的配置。在这种情况下，我们可能会要求您运行路由跟踪（trace-route）或其他系统工具以进行进一步分析。

---

#### 发送给 Anyteam <a href="#p-42130-send-to-anyteam-7" id="p-42130-send-to-anyteam-7"></a>

将生成的日志和您的网络规格发送至 [support@anytype.io](mailto:support@anytype.io)。

--- 

此工具可以帮助诊断网络连接问题，确保 Anytype 的同步功能正常运行。如果您遇到问题，请按照上述步骤操作并将相关信息发送给支持团队以获得帮助。