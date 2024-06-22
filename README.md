# ChatGPT Cookie 管理器

## 简介
ChatGPT Cookie 管理器是一个为 Chrome 浏览器设计的扩展程序，允许用户管理 ChatGPT 相关网站的 Cookies，包括清除、设置 Cookies，并提供一键跳转到 ChatGPT 的功能。

## 版本
当前版本：v1.7

## 功能
- **导航到 ChatGPT**：允许用户一键打开 ChatGPT 在新的浏览器标签页中。
- **清除 Cookies**：一键清除 ChatGPT 网站的所有 Cookies。
- **设置 Cookies**：根据预设的配置自动设置 Cookies。
- **刷新页面**：刷新当前 ChatGPT 页面。
- **通知显示**：从远程 Markdown 文件加载并显示通知。

## 安装
1. 下载此仓库的 ZIP 文件并解压，或克隆仓库到本地。
2. 打开 Chrome 浏览器，并进入 `chrome://extensions/` 页面。
3. 启用开发者模式（页面右上角的开关）。
4. 点击「加载已解压的扩展程序」，选择扩展程序的目录。

## 使用说明
安装扩展后，点击浏览器工具栏中的 ChatGPT Cookie 管理器图标，即可使用上述功能。

## 开发者指南
要为此扩展贡献代码或了解更多开发细节，可查阅以下文件：
- `manifest.json`：扩展的配置文件。
- `popup.html` 和 `popup.js`：构成扩展用户界面的主要文件。
- `background.js`：扩展的后台脚本，用于处理 Cookie 和标签操作。

## 许可
此项目采用 MIT 许可证。更多详情请查阅 LICENSE 文件。

## 联系方式
如果有任何问题或建议，请通过 Issues 提交您的反馈。

