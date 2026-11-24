# EasyDash Studio 主题编辑器

在电脑上制作汽车仪表主题。你可以为车速、转速和温度选择数字、指针或进度条，调整通道绑定，用模拟数据预览动效和音效，再把主题导入手机 EasyDash。

## 下载

| 平台 | 版本 | 下载 |
| --- | --- | --- |
| macOS · Apple Silicon 和 Intel | 0.2.7（构建 13） | [下载 Mac 通用版 ZIP](downloads/EasyDash-Studio-0.2.7-build13-macOS.zip?raw=true) |
| Windows x64 | 0.2.7（构建 13） | [下载 Windows x64 便携版 ZIP](downloads/EasyDash-Studio-0.2.7-build13-windows-x64.zip?raw=true) |

Mac 版为 Universal 应用，构建目标为 Intel 版 macOS 10.15 起、Apple 芯片版 macOS 11 起。本次已在 Apple 芯片 Mac 的 macOS 26.5.1 上验证解压后启动。应用未经 Apple 公证，首次打开时 macOS 可能会提示无法验证开发者。下载后可用 `shasum -a 256 下载文件名` 核对校验值。[SHA-256 校验值](SHA256SUMS.txt)

Windows 版适用于 Intel、AMD 的 64 位电脑。下载后右键 ZIP，选「全部解压」，保留同目录的 DLL 和 `data` 文件夹，双击 `easydash_studio.exe` 启动。如需核对下载文件，可在 PowerShell 运行 `Get-FileHash 文件名.zip -Algorithm SHA256`，与仓库中的校验值比对。

## 打开和导出主题

1. 在 Windows 上打开解压后的 `easydash_studio.exe`。在 Mac 上将 ZIP 里的 `EasyDash Studio.app` 拖到「应用程序」，双击启动。
2. 点击「打开工程」，选择已有的 `.easydash.json`。也可以用「从模板新建」开始设计。
3. 调整布局和数据通道后，播放模拟数据查看效果。点击「导出到 EasyDash」生成主题文件。
4. 将文件传到手机，在 EasyDash 的「主题中心 → 导入主题」中选择它。

如果想用中文描述仪表并生成首稿，可使用主题生成 Skill，支持豆包、DeepSeek、WorkBuddy 和 Codex。[EasyDash 主题生成 Skill](https://github.com/mbwscn-design/easydash-theme-skill)
