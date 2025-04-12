# 常见问题解答 (FAQs)

<details>

<summary>在使用仅限本地模式（local-only mode）时，是否会有网络请求？</summary>

我们可以保证不会向 Anytype 网络发送任何网络请求，但我们的遥测功能仍会发送请求（未来您可以选择退出）。此外，客户端为了某些功能（如嵌入块、获取书签等）正常运行，仍然需要发送网络请求。

</details>

<details>

<summary>为什么每次在 Linux 上登录时都被要求输入密钥/恢复短语？</summary>

Linux 用户可能会在每次登录时被要求输入密钥。为解决此问题，请安装一个密钥环工具。最常用的是 [GNOME Keyring](https://wiki.gnome.org/action/show/Projects/GnomeKeyring?action=show&redirect=GnomeKeyring)。此外，请确保您已满足所有[依赖项](https://github.com/anyproto/anytype-ts#dependencies)。

</details>

<details>

<summary>为什么没有 Anytype 的浏览器版本？</summary>

Anytype 没有浏览器版本。它是一个独立的软件，可在桌面或移动设备上运行。浏览器应用存在许多漏洞点，这会危及我们对数据安全和加密的承诺。

</details>

<details>

<summary>旧版主页发生了什么？</summary>

<img src="../.gitbook/assets/w=3840,quality=80 (1).webp" alt="" data-size="original">

Alpha 应用中的旧版主页已被移除，并替换为新的侧边栏和小部件。如果您非常喜欢原来的布局，可以尝试使用带有画廊视图的集合重新创建它。

</details>

<details>

<summary>我可以同时使用两个独立的存储库（Vaults）吗？</summary>

以下方法仅适用于桌面端：您需要为另一个存储库创建一个单独的快捷方式，并在启动命令中添加 `--user-data-dir="$path"` 参数（例如 `--user-data-dir="D:\Anytype"`）。

</details>

<details>

<summary>在哪里可以找到键盘快捷键/热键？</summary>

您可以通过点击应用程序右下角的 `? > 键盘快捷键` 查看所有键盘快捷键。

</details>

<details>

<summary>我可以在 Chromebook 上安装 Anytype 吗？</summary>

有几种方法可以在 Chromebook 上安装 Anytype，但最简单的方法可能是使用 [AppImage](https://download.anytype.io)。有关社区成员提供的完整指南，请点击[这里](https://community.anytype.io/t/guide-to-use-anytype-on-a-chromebook/12181)。

</details>

<details>

<summary>Anytype 是否有漏洞赏金计划？</summary>

作为一个尚未实现可持续收入的非营利组织，我们目前没有任何保证的漏洞赏金计划。如果您能证明自己发现了我们应用程序中的严重漏洞但不想公开披露，我们可以讨论潜在的奖励。请查看 GitHub 上的此[页面](https://github.com/anyproto/.github/blob/main/docs/SECURITY.md)以获取更多信息。

</details>

<details>

<summary>如果无法通过浏览器打开 Anytype 链接怎么办？</summary>

您仍然可以通过将 Anytype 链接粘贴到 Anytype 内的全局搜索菜单中并按回车键来打开任何链接。

</details>

<details>

<summary>如果遇到 GLIBCXX 错误怎么办？</summary>

如果您遇到 GLIBCXX 问题，可以安装[最新预发布版本](https://github.com/anyproto/anytype-ts/releases/tag/v0.45.10-beta)，或者尝试按照[此](https://community.anytype.io/t/update-45-1-unable-to-launch/26723/4?u=filip)线程解决问题，也可以尝试使用（非官方的）[flatpak](https://flathub.org/apps/io.anytype.anytype) 版本。

</details>