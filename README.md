# LiteSnap

**好内容，一截就留下。**

LiteSnap 是一款轻量 Chrome 网页截图扩展，支持正文长截图、整页捕获、标注遮挡与多格式导出。无需账号，截图、编辑和历史记录在本机处理。

[官方网站](https://litesnap.app/) · [下载与安装](https://litesnap.app/#download) · [隐私说明](https://litesnap.app/privacy.html) · [反馈问题](https://github.com/gentpan/LiteSnap/issues/new/choose)

遇到问题或有新的想法？欢迎[提交问题反馈或功能建议](https://github.com/gentpan/LiteSnap/issues/new/choose)，帮助 LiteSnap 变得更好用。

## 主要功能

- **网页截图**：正文长截图、整页截图、可视区域、选区与可视元素截图。
- **正文范围**：自动建议正文区域，可调整左右边界，排除侧栏及滚动条。
- **编辑与标注**：裁剪、箭头、矩形、文字、编号、实心遮挡，支持撤销与重做。
- **长图导出**：默认导出完整长图，预览滚动位置不影响导出范围；也可选择原尺寸连续分块。
- **多格式输出**：PNG、JPEG、WebP 与分页 PDF，支持复制图片和导入图片后编辑、转换格式。
- **本地历史**：最多 20 条或 200 MiB，可删除记录或关闭保存。

## 安装与使用

当前官网提供 **0.1.7 开发版**，Chrome Web Store 版本已提交，尚待审核。

1. 在[官网安装页面](https://litesnap.app/#download)下载开发版并解压至固定位置。
2. 在 Chrome 地址栏打开 `chrome://extensions`，开启「开发者模式」。
3. 点击「加载已解压的扩展程序」，选择解压后的文件夹。
4. 将 LiteSnap 固定到工具栏，在普通网页点击图标选择截图方式。

默认快捷键为 `Alt + Shift + S`，macOS 为 `Option + Shift + S`，用于截取当前可视区域。可以在 Chrome 的扩展快捷键设置中修改。

截图后可进行裁剪、标注和遮挡，再导出图片或 PDF。「取消裁剪」恢复完整截图并保留标注；长图导出设置可选择裁剪区域或完整截图。

## 支持范围与限制

- 当前支持 Chrome 116+ 的普通 HTTP / HTTPS 网页，其他浏览器暂不在支持范围内。
- 浏览器设置页、Chrome 扩展商店与 `file://` 页面无法截图。
- 长截图捕获主文档纵向内容，不展开内部滚动容器或 iframe 的滚动内容。
- 无限列表、虚拟列表、实时视频及其他动态内容可能无法完整捕获。截图过程中请保持目标页面和浏览器窗口在前台。
- 超过画布或格式尺寸上限的单张长图会等比例缩小，需保留原始分辨率时可选择分块导出。

## 数据与隐私

0.1.7 扩展无需账号，也没有图床上传入口。截图、编辑与历史记录保存在本机。导出和复制会将遮挡合并到最终像素中，不包含可撤销编辑图层；本地编辑项目仍保留原始截图，可通过删除对应历史清理。

完整说明见[隐私页面](https://litesnap.app/privacy.html)。

## 问题反馈与功能建议

欢迎通过 [Issues](https://github.com/gentpan/LiteSnap/issues) 报告问题或提出建议。提交前可先搜索已有反馈。

问题反馈请提供扩展版本、Chrome 版本、操作系统、重现步骤，以及预期与实际结果。截图问题可附上可公开访问的示例网页；分享截图前请遮挡个人信息。

## English

LiteSnap is a lightweight Chrome extension for full-page and article screenshots, annotations, redaction, and PNG / JPEG / WebP / PDF export. Version 0.1.7 processes screenshots locally without an account or upload feature. Chrome 116+ is currently supported.

Visit the [official website](https://litesnap.app/) to download LiteSnap and view the installation guide. Have a question, found a bug, or have an idea for a new feature? [Open an issue](https://github.com/gentpan/LiteSnap/issues/new/choose) to share your feedback.
