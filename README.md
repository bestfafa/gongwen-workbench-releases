# 公文排版工作台

面向日常办公的 Windows 公文排版工具。本仓库用于发布可下载版本、使用说明和更新记录；项目源码单独维护。

## 当前状态

当前提供 **2.0.0-beta.3 公开测试版**，可自由下载试用。

[进入新版下载页](https://github.com/bestfafa/gongwen-workbench-releases/releases/tag/v2.0.0-beta.3)

普通用户只需下载 [GongwenWorkbench-2.0.0-beta.3-win-x64.zip](https://github.com/bestfafa/gongwen-workbench-releases/releases/download/v2.0.0-beta.3/GongwenWorkbench-2.0.0-beta.3-win-x64.zip)（约48.6MB），不要下载 GitHub 自动生成的 `Source code` 附件。完整解压到新目录后，双击 `Start.cmd`，无需安装 Python。目标测试系统为 Windows 10/11 x64；不支持 Windows 7、32 位系统或 ARM 设备。

新版统一了下拉菜单、输入框、复选框和焦点样式，改善暗色主题下的可读性；窄窗口可切换编辑与预览。导出状态明确，支持打开最近导出的文件或目录。

先点击“载入示例”→“导出 Word”，收到成功提示后，用 Word/WPS 打开导出文件核对。包内 `TEST_CHECKLIST.txt` 提供完整试用清单。

## 使用与更新

自动更新尚未实现。新版完整包解压到新目录，保留旧版目录；新版有问题时关闭新版并重新运行旧版。离线电脑也使用相同方式。不要覆盖正在运行的程序，也不要将个人文档存放在程序目录。

编辑内容仅在本次窗口内自动保留，关闭前必须导出。Word 表格、图片和复杂对象原样保留但只读；预览不是最终打印效果。请只用虚构内容或脱敏副本试用，不直接覆盖正式材料。

程序未做代码签名；若单位安全策略阻止运行，请联系本单位 IT，不要关闭安全防护。

## 反馈问题

请提供软件版本、Windows 版本、复现步骤、预期结果与实际提示。不要公开上传单位内部公文、个人信息、真实文件路径或未脱敏的截图。可用虚构内容制作最小复现样例。

## 字体

本包不附带商业字体。字体目录缺失不会中断导出，但实际显示取决于本机合法安装的字体，必须在 Word/WPS 核对最终版式。

## 第三方材料

程序包内附许可证和版权通知。下载页提供 `ThirdParty-Sources-Qt-6.11.1.zip`，含所用 Qt/PySide/shiboken 对应上游源码；普通使用无需下载这个源码附件。详情见包内 `SOURCE_ACCESS.txt`。`SHA256SUMS.txt` 用于检测下载损坏，不能代替对下载来源的确认。
