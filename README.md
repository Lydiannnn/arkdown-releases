# Arkdown

把想法写下来，让文档成为自己的知识库。

Arkdown 是面向 Windows 的本地 Markdown 写作与知识库工具，包含深浅主题、Arknote 桌面便签、AI 文档对话以及划词、截图和悬浮翻译。

## 下载 Arkdown 1.0.0

Arkdown 1.0.0 已发布，提供 Full 完整版与 Lite 轻量版。

Windows x64，解压后运行 `Arkdown.exe`；独立便签使用 `Arknote.exe`。

| 版本 | 下载大小 | 适合 |
| --- | --- | --- |
| [Full 完整版](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.0/Arkdown-1.0.0-Full-Windows-x64.zip) | 759.8 MB | 一次下载，内置全部可选组件 |
| [Lite 轻量版](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.0/Arkdown-1.0.0-Lite-Windows-x64.zip) | 259.4 MB | 内置编辑器与便签，其他组件按需下载 |

[版本说明与 SHA-256 校验文件](https://github.com/Lydiannnn/arkdown-releases/releases/tag/v1.0.0)

[中文使用说明](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.0/README-zh-CN.md)

两版均包含字体、品牌资源、使用说明书与 11 篇初始工作区文章及插图。Full 解压后约 1.91 GB，Lite 约 618 MB；Lite 安装可选组件后会增加本地占用。以上大小采用十进制单位。

## Full 与 Lite

Full 内置 OCR Small / Medium、悬浮翻译引擎、MarkItDown 文档转换、Pandoc 文档导入导出和 Codex CLI 0.154.0。

Lite 首次明确使用相应功能时，会在 Arkdown 内下载安装所需组件，并在完整性校验后继续操作。安装支持取消和重试，已安装组件会复用。打开设置页不会自动下载所有组件。

AI 与在线翻译服务仍需要用户自己的连接或账号。Codex CLI 在「偏好设置 → 管理大模型 → 添加大模型」中添加：检测连接后，已有登录可复用；未登录时点击「登录 ChatGPT」，在官方浏览器页面完成登录。Full 使用内置 CLI；Lite 优先复用可用 CLI，否则下载安装。软件包不包含用户账号或登录信息。

## 独立组件

组件通常由 Arkdown 自动下载和校验，无需手动解压到程序目录。各发布页提供对应版本、校验信息与许可材料。

- [OCR 基础组件 / Small](https://github.com/Lydiannnn/arkdown-releases/releases/tag/ocr-base-1.0.0-win-x64)
- [OCR Medium](https://github.com/Lydiannnn/arkdown-releases/releases/tag/ocr-medium-6.0.0-win-x64)
- [悬浮翻译引擎](https://github.com/Lydiannnn/arkdown-releases/releases/tag/screen-translation-engine-1.0.0)
- [MarkItDown 文档转换](https://github.com/Lydiannnn/arkdown-releases/releases/tag/markitdown-0.1.7-py3.12.10)
- [Pandoc 文档导入导出](https://github.com/Lydiannnn/arkdown-releases/releases/tag/pandoc-3.10.1-win-x64)
- [Codex CLI](https://github.com/Lydiannnn/arkdown-releases/releases/tag/codex-cli-0.154.0-win-x64)

## 关于本仓库

本仓库用于发布 Arkdown 应用包及可选组件，不公开 Arkdown 产品源码。GitHub 自动生成的「Source code」附件仅包含本下载仓库的文件。第三方组件沿用各自许可证，相关材料随软件及对应组件发布提供。

ArkVibe，Inc. · powered by Miterh
