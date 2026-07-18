# GWFox - Firefox 新界面主题

为 Firefox 浏览器带来清新、现代的全新外观

## 项目简介

GWFox 是一个 Firefox 浏览器主题项目，旨在为用户提供更加美观、现代化的浏览器界面体验。

## 功能特性

- 🎨 **现代设计** - 清新简洁的界面风格
- 🌓 **深色/浅色模式** - 自动跟随系统主题
- 🖱️ **流畅动画** - 平滑的过渡效果
- 📐 **优化布局** - 更合理的空间利用
- 🎯 **个性化定制** - 可自定义的元素样式
- 🔧 **易于安装** - 一键应用主题

## 主题预览

### 浅色模式
- 清新明亮的配色方案
- 柔和的阴影效果
- 清晰的层次结构

### 深色模式
- 护眼的深色配色
- 高对比度设计
- 减少视觉疲劳

## 安装方法

### 方法一：Firefox 主题商店
1. 访问 Firefox 主题商店
2. 搜索 "GWFox"
3. 点击 "安装" 按钮

### 方法二：手动安装
`ash
# 克隆项目
git clone https://github.com/wucald25641/zzzhyooo8456.git

# 进入项目目录
cd zzzhyooo8456

# 按照说明文档进行安装
`

## 自定义配置

### 修改颜色方案

`css
/* 自定义主色调 */
:root {
  --primary-color: #4A90E2;
  --background-color: #F5F5F5;
  --text-color: #333333;
}
`

### 调整布局

`css
/* 自定义工具栏高度 */
#nav-bar {
  height: 40px;
}

/* 调整标签栏样式 */
.tabbrowser-tab {
  border-radius: 8px;
}
`

## 兼容性

### 支持的 Firefox 版本
- Firefox 89+
- Firefox ESR 91+
- Firefox Developer Edition
- Firefox Nightly

### 支持的操作系统
- Windows 10/11
- macOS 10.15+
- Linux (主流发行版)

## 常见问题

### Q: 如何恢复默认主题？
A: 在 Firefox 设置中选择 "默认主题" 即可恢复。

### Q: 主题会影响浏览器性能吗？
A: 不会。GWFox 主题经过优化，对性能影响微乎其微。

### Q: 如何报告问题？
A: 请在 GitHub Issues 中提交问题报告。

### Q: 支持自定义吗？
A: 支持。您可以修改 CSS 文件来自定义主题样式。

## 开发指南

### 项目结构

`
zzzhyooo8456/
├── chrome/              # 主题文件
│   ├── userChrome.css   # 界面样式
│   └── userContent.css  # 内容样式
├── icons/               # 图标资源
├── themes/              # 主题变体
├── docs/                # 文档
└── README.md            # 项目说明
`

### 开发环境

1. 安装 Firefox Developer Edition
2. 启用 	oolkit.legacyUserProfileCustomizations.stylesheets
3. 创建 chrome 文件夹
4. 添加自定义 CSS 文件

### 调试技巧

`javascript
// 启用浏览器控制台
// about:config -> devtools.chrome.enabled = true

// 重新加载主题
// about:config -> toolkit.legacyUserProfileCustomizations.stylesheets
`

## 贡献指南

欢迎贡献代码和设计！

1. Fork 项目
2. 创建功能分支 (git checkout -b feature/new-theme)
3. 提交更改 (git commit -m '添加新主题变体')
4. 推送到分支 (git push origin feature/new-theme)
5. 创建 Pull Request

## 许可证

MIT License

## 致谢

感谢所有贡献者和 Firefox 社区的支持！

## 更新日志

- 2026-07-17: 添加中文README文档
- 2026-07-16: 更新README文档
## 主题更新
- 优化了深色模式配色
- 添加了自定义快捷键支持
