<p align="center">
    <a href="https://doc.anytype.io">
        <img src=".gitbook/assets/anytype-logo-360px.png" alt="文档标志" width="100px" height="100px">
    </a>
</p>

## 目录

- [**简介**](#简介)
- [**贡献流程**](#贡献流程)
- [**文件结构**](#文件结构)
- [**规范**](#规范)
  - [**文本格式**](#文本格式)
  - [**列表**](#列表)
  - [**区块**](#区块)
  - [**媒体**](#媒体)

## 简介

ℹ️ 请所有贡献者在参与文档建设前阅读我们的[行为准则](https://github.com/anytypeio/community/blob/main/README.md#code-of-conduct)和[Gitbook规范](#规范)。
欢迎通过PR提交修改建议，并参与[文档改进讨论](https://community.anytype.io/t/improvements-for-doc-anytype-io/2862)。请按以下步骤进行贡献。若您不熟悉_git_或_GitHub_，建议先学习[GitHub指南](https://guides.github.com/introduction/flow/)。

## 贡献流程

1. Fork本仓库
2. (可选)克隆fork的仓库
   - 使用SSH
     ```shell
     git clone --filter=tree:0 git@github.com:anytypeio/community.git
     ```
   - 使用HTTPS
     ```shell
     git clone --filter=tree:0 https://github.com/anytypeio/community.git
     ```
   - 使用GitHub CLI
     ```shell
     gh repo clone anytypeio/community -- --filter=tree:0
     ```
3. 从最新的`main`分支创建新分支
4. 在新分支上修改
5. 提交并推送到新分支
6. 创建Pull Request
7. 指定[Vladimir](https://github.com/d1eselboy)、[Divyanshu](https://github.com/div3xi)或[Enda](https://github.com/endac)作为PR审核者

## 文件结构

* 所有新增或移除的页面都需在[SUMMARY.md](https://github.com/anytypeio/docs/blob/main/SUMMARY.md)文件中更新**目录**
  * 使用缩进表示页面层级关系
  * 使用Markdown链接格式，例如：
    ```
    [导航功能](https://github.com/anytypeio/docs/blob/main/features/navigation.md)
    ```
* 所有文件保存为**Markdown .md**格式
* 如需嵌套页面，请放入对应分类文件夹。若文件夹不存在可新建
* 使用图片时，必须全部存放在[.gitbook/assets](https://github.com/anytypeio/docs/tree/main/.gitbook/assets)文件夹并从此引用
    > 所有媒体素材应使用浅色模式

## 规范

> 以下是Gitbook从Markdown生成文档时遵循的规则。请在进行任何修改时遵守这些规范。

### 文本格式

- # 一级标题
  ```
  # 一级标题
  ```
  
- ## 二级标题
  ```
  ## 二级标题
  ```
  
- ### 三级标题
  ```
  ### 三级标题
  ```
  
- **加粗**
  ```
  **加粗文本**
  ```
  
- *斜体*
  ```
  _斜体文本_
  ```
  
- ~~删除线~~
  ```
  ~删除线文本~
  ```
  
- 水平分割线
  ```
  ---
  ```
  
- [超链接](#)
  ```
  [链接名称](https://example.com)
  ```

- ![图片](#)
  ```
  ![图片](http://url/a.png)
  ```

- `行内代码`
  ```
  `行内代码`
  ```

### 列表

- **无序列表**
  ```
  * 项目1
  * 项目2
  * 项目3
      或
  - 项目1
  - 项目2
  - 项目3
  ```

- **有序列表**
  ```
  1. 项目1
  2. 项目2
  3. 项目3
  ```

- **任务列表**
  ```
  * [ ] 未完成任务
  * [x] 已完成任务
  ```
  
### 区块

- **代码块**
```
``` 创建新代码块
```py 创建带Python语法高亮的代码块
```

- **引用**
  ```
  使用 > 开始引用区块
  ```

- **信息提示块**
  ```
  {% hint style="info" %} 信息提示内容 {% endhint %}
  ```
  <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/info-hints-block.png" alt="信息提示">
    </a>
  </p>
  
- **警告提示块**
  ```
  {% hint style="warning" %} 警告提示内容 {% endhint %}
  ```
    <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/warning-hints-block.png" alt="警告提示">
    </a>
  </p>
  
- **成功提示块**
  ```
  {% hint style="success" %} 成功提示内容 {% endhint %}
  ```
    <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/success-hints-block.png" alt="成功提示">
    </a>
  </p>
  
- **危险提示块**
  ```
  {% hint style="danger" %} 危险提示内容 {% endhint %}
  ```
    <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/danger-hint-block.png" alt="危险提示">
    </a>
  </p>

### 媒体

- **媒体区块：** 需遵循以下格式
  ```
  ![媒体说明](<.gitbook/assets/文件名>)
  
  例如：
  
  ![首页截图](<.gitbook/assets/Screenshot 2021-11-05 at 18.45.31.png>)
  ```
  添加媒体区块时，若所在页面为嵌套结构，需使用`../`正确跳转目录层级

- **文件存储：** 所有媒体必须先上传至[.gitbook/assets/](https://github.com/anytypeio/docs/tree/main/.gitbook/assets)文件夹。现有页面中可能看到GitBook专有格式`{% embed url="`，无需使用该格式

- **文件格式：** 文档仅接受以下媒体格式
    - **视频：**
    
      > ✔️ 仅限**MP4**格式
      > ❌ 不接受**gif**等其他格式
      
    - **图片：**
      
      > ✔️ 仅限**PNG**和**JPG**格式
      > ❌ 不接受其他格式

- **大小限制：** 每个媒体文件不得超过**5MB**。1000px宽度的图片和视频仍能保持清晰度，可将4K文件大小缩减约75%

- **命名规范：** 请使用人类可读的命名方式
  ```
  <图片描述>-<页面名称>.<文件格式>
  
  例如：
  ✔️ 加载界面-介绍页.png
  ❌ 屏幕截图 2021-11-05 18.45.31.png
  ```