## Automator 自动化工具运行方式

- 方式 1
  - 下载后用命令执行`automator path/xxx.workflow`
- 方式 2
  - 下载后双击打开，点击 Automator 的运行按钮
- 方式 3
  - 创建一个新的 Automator 应用程序，将 workflow 所有操作流程复制进去，保存后双击运行

## 自动化工具列表

### **上传 Github 图库** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/UploadImage.workflow-release/UploadImage.workflow.zip)

- 此工具会将选择的图片上传你的 Github，将链接转换为 jsDelivr CDN 链接，并返回 Markdown 格式的图片格式
- 工具会自动提示配置你的 GithubApiToken，仓库地址，分支名，目标文件夹路径 [创建 Token](https://github.com/settings/tokens)

### **自动上传截图** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/UploadScreenshot.workflow-release/UploadScreenshot.workflow.zip)

- 此工具会打开截图，将截图上传你的 Github，将链接转换为 jsDelivr CDN 链接，并返回 Markdown 格式的图片格式
- 工具会自动提示配置你的 GithubApiToken，仓库地址，分支名，目标文件夹路径 [创建 Token](https://github.com/settings/tokens)
  > 注意：使用前需要添加权限，系统设置->隐私与安全性->录屏->添加此工具

### **TinyPng 压缩图片** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/TinyImage.workflow-release/TinyImage.workflow.zip)

- 此工具会将选择的图片使用 TinyPng 压缩
- 工具会自动提示输入你的 TinyPngApiKey [查看 ApiKey](https://tinify.com/dashboard/api)

### **TinyPng 批量压缩图片** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/TinyImages.workflow-release/TinyImages.workflow.zip)

- 此工具会将你选择的文件夹中的图片批量使用 TinyPng 压缩
- 工具会自动提示输入你的 TinyPngApiKey [查看 ApiKey](https://tinify.com/dashboard/api)
  > 注意：免费 TinyPng 账户每月限制 500 张图片 [查看余量](https://tinify.com/dashboard/api)

### **Git 代码追踪功能** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/GitCodeTracker.workflow-release/GitCodeTracker.workflow.zip)

- 此工具会跟通过弹窗输入关键词，查找指定的 Git 提交记录
- 弹窗显示包含关键词的提交作者和日期

### **修改图片尺寸** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/ResizeImage.workflow-release/ResizeImage.workflow.zip)

- 此工具会将选择的图片进行尺寸修改，等比例放大或缩小

### **随机桌面壁纸** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/RandomWallpaper.workflow-release/RandomWallpaper.workflow.zip)

- 此工具会获取 Bing 每日图片，随机一张设置为桌面壁纸

### **收集项目图片** [download](https://github.com/wdzawdh/AutomatorRepo/releases/download/CollectImages.workflow-release/CollectImages.workflow.zip)

- 此工具会将选择的项目文件夹中的所有图片提取出来
