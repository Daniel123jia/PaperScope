# PaperScope

PaperScope 是一款本地运行、联网检索的论文检索软件。本仓库仅用于提供已经编译完成的 Windows 和 macOS 软件包，**不包含源代码**。

## 推荐版本

建议下载最新的 [PaperScope v1.4](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.4)。

| 版本 | 首次启动试用期 | Windows | Intel Mac | Apple 芯片 Mac |
| --- | ---: | :---: | :---: | :---: |
| [v1.4](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.4) | 7 天 | 支持 | 支持 | 支持 |
| [v1.3](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.3) | 20 天 | 支持 | 支持 | 支持 |
| [v1.2](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.2) | 7 天 | 支持 | 支持 | 支持 |
| [v1.1](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.1) | 7 天 | 支持 | 不支持 | 不支持 |

每个版本保留发布时内置的试用期限。同一版本再次打开不会重新计时，不同版本使用各自独立的试用记录。试用无需导入 `license.json`。

## Windows 下载

Windows 用户建议下载对应版本的便携版 ZIP：

- v1.4：[`ScholarHub_Portable_v1.4.zip`](https://github.com/Daniel123jia/PaperScope/releases/download/v1.4/ScholarHub_Portable_v1.4.zip)
- v1.3：[`ScholarHub_Portable_v1.3.zip`](https://github.com/Daniel123jia/PaperScope/releases/download/v1.3/ScholarHub_Portable_v1.3.zip)
- v1.2：[`ScholarHub_Portable_v1.2.zip`](https://github.com/Daniel123jia/PaperScope/releases/download/v1.2/ScholarHub_Portable_v1.2.zip)
- v1.1：[`ScholarHub_Portable_v1.1.zip`](https://github.com/Daniel123jia/PaperScope/releases/download/v1.1/ScholarHub_Portable_v1.1.zip)

下载后解压 ZIP，再双击其中的 `论文检索助手.exe`。每个 Release 也提供可以直接下载的单文件 EXE。

## macOS 下载

v1.2、v1.3 和 v1.4 分别提供 Intel 与 Apple 芯片版本。点击屏幕左上角苹果菜单，选择“关于本机”即可确认处理器类型：

- 显示“处理器：Intel”：下载文件名包含 `macOS_Intel` 的 ZIP。
- 显示“芯片：Apple M1/M2/M3/M4/M5”：下载文件名包含 `macOS_AppleSilicon` 的 ZIP。

下载后双击 ZIP 解压，再打开 `论文检索助手.app`。如果 macOS 阻止首次启动：

1. 关闭系统拦截提示。
2. 打开“系统设置 → 隐私与安全”。
3. 找到 `论文检索助手.app`，点击“仍要打开”。
4. 输入登录密码并确认。

Mac 软件包使用免费的 ad-hoc 签名，没有使用付费 Apple Developer 证书或 Apple 公证，因此首次打开时可能出现 Gatekeeper 提示。

## 版本说明

### v1.4

- 7 天试用。
- 新增“引用本文”功能，可查询、排序、复制和导出后续引用文献。
- 新增计算机领域中科院分区筛选，并优化 CCF 分类和英文界面。

### v1.3

- 20 天试用。
- 新增中英文界面、硕博论文检索、多数据源检索编排和多种界面背景。
- 改进 PDF 获取、检索容错以及学校、期刊和会议分类展示。

### v1.2

- 7 天试用。
- 首个同时提供 Windows、Intel Mac 和 Apple 芯片 Mac 软件包的版本。

### v1.1

- 7 天试用。
- 仅提供 Windows EXE 和便携版 ZIP。

## 使用说明

- 软件需要联网才能检索论文。
- 软件包不要求用户另外安装 Python 或 Node.js。
- 用户设置、缓存和试用状态保存在当前系统账户的数据目录中。
- 每个 Release 都提供 SHA-256 校验文件，可用于检查下载文件是否完整。
- 软件显示的论文信息、PDF 和引用文献覆盖范围取决于对应公开学术数据源。

## 交流与反馈

欢迎扫码添加微信，一起交流论文检索、科研工具使用、功能建议与问题反馈。添加好友时可以备注 `PaperScope`，方便确认来意。

<p align="center">
  <img src="assets/wechat-contact.jpg" alt="PaperScope 微信交流二维码" width="360">
</p>

## 下载入口

全部版本请前往 [GitHub Releases](https://github.com/Daniel123jia/PaperScope/releases)。
