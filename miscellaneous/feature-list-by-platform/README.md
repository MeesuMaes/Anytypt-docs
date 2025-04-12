---
description: Anytype 可在 Mac、Windows、Linux、iOS 和 Android 上使用。
---

# 功能

### 应用对比

如果您想了解 Anytype 与 Notion 的对比，请查看我们的文章：

{% embed url="https://blog.anytype.io/notion-alternative/" %}

或者，如果您想知道 Evernote 和 Anytype 之间的区别，请查看我们博客的另一篇文章：

{% embed url="https://blog.anytype.io/evernote-alternative/" %}

---

### 高需求功能

{% hint style="info" %}
您可以在此处查看完整的路线图：[公共路线图](https://github.com/orgs/anyproto/projects/1/views/1)。
{% endhint %}

* API 和插件
* 公式
* 提醒和通知
* AI 助手
* 转录（Transclusion）
* 白板 / 画布
* 网页应用
* 标签作为对象

---

#### 已实现功能

* 日历 - [0.36.0](https://community.anytype.io/t/anytype-desktop-0-36-0-released/12198)
* 网页剪藏工具 - 0.39.0 ([Chrome](https://chromewebstore.google.com/detail/anytype-web-clipper/jbnammhjiplhpjfncnlejjjejghimdkf?hl=en))
* [协作功能](../../basics/space/collaboration.md) - [0.40.0](https://community.anytype.io/t/anytype-desktop-0-40-0-multiplayer-released/20219)
* [内联 LaTeX](../../basics/object-editor/blocks.md#inline-latex) - [0.42.0](https://community.anytype.io/t/anytype-desktop-0-42-0-released/22993#p-83725-inline-latex-scientist-5)
* [简单公式计算](../../basics/sets-and-collections/#simple-formulas-calculations) - [0.44.0](https://community.anytype.io/t/anytype-desktop-0-44-0-released/25865)
* [日期作为对象](../../basics/types/dates.md) - [0.44.0](https://community.anytype.io/t/anytype-desktop-0-44-0-released/25865)
* RTL 支持 - [0.45.0](https://community.anytype.io/t/anytype-desktop-0-45-0-released/26702)
* [网页发布](../../basics/space/web-publishing.md) - [0.45.0](https://community.anytype.io/t/anytype-desktop-0-45-0-released/26702)

---

### 移动端功能

以下是一个按平台列出的功能及其实施状态列表。所有列出的功能均已在桌面端 0.40.* 版本中实现，而用于比较的移动端版本均为 0.29.*。

{% tabs %}
{% tab title="存储库（Vault） %}
| 功能/操作                 | iOS | Android |
| ------------------------------ | --- | ------- |
| 拼写检查                     | 否  | 否      |
| 浅色模式/深色模式           | 是  | 是      |
| 壁纸                        | 是  | 是      |
| 默认对象类型                | 是  | 是      |
| PIN 码                      | 否  | 否      |
| 删除存储库                  | 是  | 是      |
| Notion 导入                 | 否  | 否      |
| Markdown 支持               | 否  | 否      |
| 引导工具提示               | 否  | 否      |
| 应用内反馈问卷             | 否  | 否      |
| 帮助菜单                   | 否  | 否      |
| 对象版本历史               | 否  | 否      |
| 对象同步状态               | 是  | 是      |
{% endtab %}

{% tab title="导航" %}
| 功能/操作             | iOS | Android |
| -------------------------- | --- | ------- |
| 快捷键支持               | 否  | 否      |
| 导航（反向链接）菜单     | 否  | 否      |
| 小部件                   | 是  | 是      |
| 关系图                   | 否  | 否      |
| 全局搜索                 | 是  | 是      |
| 对象内搜索 (Ctrl + F)    | 否  | 是      |
| 侧边栏                   | 否  | 否      |
{% endtab %}

{% tab title="编辑器" %}
| 功能/操作                          | iOS | Android |
| ----------------------------------- | --- | ------- |
| Markdown 支持                      | 否  | 否      |
| 导出为 PDF、Markdown、HTML、Protobuf | 否  | 否      |
| 版本历史                           | 否  | 否      |
| 文本颜色                           | 是  | 是      |
| 文本背景颜色                       | 是  | 是      |
| 标题颜色                           | 是  | 是      |
| 标题背景颜色                       | 是  | 是      |
| 块拖放（Block DnD）                | 是  | 是      |
| 安装类型                           | 是  | 是      |
| 创建自定义类型                     | 否  | 否      |
| 安装关系                           | 是  | 是      |
| 创建自定义关系                     | 是  | 是      |
| 更改对象类型                       | 是  | 是      |
| 文本块转换为对象                   | 否  | 否      |
{% endtab %}

{% tab title="块（Blocks）" %}
| 功能/操作         | iOS       | Android   |
| ------------------ | --------- | --------- |
| 文本             | 是        | 是        |
| 标题             | 是        | 是        |
| 标题级别         | 是        | 是        |
| 子标题           | 是        | 是        |
| 高亮             | 是        | 是        |
| 提示框           | 是        | 是        |
| 复选框           | 是        | 是        |
| 项目符号列表     | 是        | 是        |
| 编号列表         | 是        | 是        |
| 切换块           | 是        | 是        |
| 文件             | 是        | 是        |
| 图片             | 是        | 是        |
| 视频             | 是        | 是        |
| 音频             | 是        | 是        |
| PDF              | 是        | 是        |
| 书签             | 是        | 是        |
| 代码块           | 是        | 是        |
| LaTeX            | 否        | 否        |
| 分隔线           | 是        | 是        |
| 点状分隔符       | 是        | 是        |
| 简单表格         | 是        | 是        |
| 内联集合         | 支持      | 支持      |
| 链接到对象       | 是        | 是        |
| 关系             | 是        | 是        |
| 嵌入             | 否        | 否        |
{% endtab %}

{% tab title="类型和关系" %}
<table data-full-width="false"><thead><tr><th>功能/操作</th><th>iOS</th><th>Android</th></tr></thead><tbody><tr><td>编辑和删除类型（名称、模板）</td><td>否</td><td>仅类型</td></tr><tr><td>编辑和删除关系</td><td>否</td><td>是</td></tr><tr><td>创建、删除模板</td><td>否</td><td>否</td></tr><tr><td>编辑模板</td><td>是</td><td>是</td></tr><tr><td>应用默认模板</td><td>是</td><td>是</td></tr><tr><td>创建标签</td><td>是</td><td>是</td></tr></tbody></table>
{% endtab %}

{% tab title="集合（Sets）" %}
<table data-full-width="false"><thead><tr><th>功能/操作</th><th>iOS</th><th>Android</th></tr></thead><tbody><tr><td>网格视图</td><td>是</td><td>是</td></tr><tr><td>列表视图</td><td>是</td><td>是</td></tr><tr><td>画廊视图</td><td>是</td><td>是</td></tr><tr><td>Kanban 视图</td><td>否</td><td>否</td></tr><tr><td>日历视图</td><td>否</td><td>否</td></tr><tr><td>添加新视图</td><td>是</td><td>是</td></tr><tr><td>添加新对象</td><td>是</td><td>是</td></tr><tr><td>排序和筛选</td><td>是</td><td>是</td></tr><tr><td>在集合中查找</td><td>否</td><td>否</td></tr><tr><td>批量选择</td><td>否</td><td>否</td></tr><tr><td>通过关系设置集合</td><td>是</td><td>是</td></tr></tbody></table>
{% endtab %}
{% endtabs %}