# Arkdown

把想法写下来，让文档成为自己的知识库。

Arkdown 是面向 Windows 的本地 Markdown 写作与知识库工具，包含深浅主题、Arknote 桌面便签、AI 文档对话以及划词、截图和悬浮翻译。

## 下载 Arkdown 1.0.1

Windows x64。现在提供安装版与免安装版，每种均有 Full / Lite 两个版本。四种下载使用相同的 1.0.1 应用代码。

| 类型 | Full 完整版 | Lite 轻量版 | 使用方式 |
| --- | --- | --- | --- |
| **安装版 · EXE** | [下载 Full 安装版](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/Arkdown-1.0.1-Full-Windows-x64-Setup.exe) · 580.9 MB | [下载 Lite 安装版](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/Arkdown-1.0.1-Lite-Windows-x64-Setup.exe) · 194.2 MB | 运行安装向导，支持原目录覆盖升级 |
| **免安装版 · ZIP** | [下载 Full 免安装版](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/Arkdown-1.0.1-Full-Windows-x64.zip) · 775.9 MB | [下载 Lite 免安装版](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/Arkdown-1.0.1-Lite-Windows-x64.zip) · 266.0 MB | 完整解压后运行 Arkdown.exe |

安装版可以创建快捷方式，并在 Windows 中提供卸载入口；免安装版无需安装向导，独立便签运行 `Arknote.exe`。

- [安装版安装、升级与卸载说明](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/README-Installers-zh-CN.md) · [安装版 SHA-256](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/SHA256SUMS-Installers.txt)
- [免安装版使用与升级说明](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/README-zh-CN.md) · [免安装版 SHA-256](https://github.com/Lydiannnn/arkdown-releases/releases/download/v1.0.1/SHA256SUMS.txt)

[完整版本说明](https://github.com/Lydiannnn/arkdown-releases/releases/tag/v1.0.1)

Full / Lite 均包含字体、品牌资源、使用说明书与 11 篇初始工作区文章及插图。Full 应用文件约 1.91 GB，Lite 约 618 MB；Lite 下载可选组件后会增加本地占用。上表下载大小采用十进制单位。

## 从旧版升级

### 安装版升级

保存文档，退出 **Arkdown 和托盘中的 Arknote**，再运行新安装包。已使用安装版的用户会自动沿用原目录；**从免安装版首次转为安装版时，请选择原 `Arkdown.exe` 所在文件夹**，不要选其父目录或另建子目录。安装过程保留设置、便签、下载组件、草稿及文档。

支持同版本重装以及 Full / Lite 互相覆盖。Full 切换 Lite 会保留已有组件，不会主动删减磁盘内容；全新安装 Lite 才是最小占用。卸载保留用户数据。默认安装到当前用户可写目录，无需管理员权限。

### 免安装版升级

先退出 Arkdown 和托盘 Arknote，备份旧目录。新 ZIP 解压到另一处，再将其中的程序文件更新到原目录，`resources`、`locales` 等程序资源使用新包完整替换。

**原样保留 `portable-data`、`temp`、自己的文档、附件及自建目录**；`temp` 可能含未保存草稿，不能清空。修改过包内初始工作区时，也应先备份并保留个人内容。现有 Full 用户继续选择 Full 即可。

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
