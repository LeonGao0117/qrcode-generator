# 🎨 QR Code Card Generator | 二维码卡片生成器

一个精美的在线二维码卡片生成工具，支持自定义样式和中英文双语切换。

[English](#english) | [中文](#chinese)

---

<a name="chinese"></a>
## 📋 简介

二维码卡片生成器是一个简单易用的 Web 工具，可以帮助你快速生成带有二维码的精美卡片。支持自定义颜色、图标、文字等，适用于个人名片、活动推广、产品展示等多种场景。

## ✨ 主要功能

- 🎨 **自定义设计**
  - 10+ 预设配色方案
  - 多种 Emoji 图标选择
  - 自定义卡片标题和描述
  
- 🌐 **双语支持**
  - 中文/英文界面一键切换
  - 所有文本和提示完全本地化
  
- 📱 **响应式设计**
  - 完美支持移动端和桌面端
  - 自适应屏幕尺寸
  - 触摸优化
  
- 💾 **便捷保存**
  - 右键保存生成的卡片
  - 自动使用卡片标题作为文件名
  - 高清画质输出 (800x1200px)
  
- 🎯 **智能提示**
  - 空字段自动填充默认值
  - 美观的确认提示框
  - 友好的用户引导

## 🚀 快速开始

### 在线使用

1. 访问 [Demo 页面](#)（替换为你的 GitHub Pages 链接）
2. 输入链接地址、卡片标题和描述
3. 选择喜欢的颜色和图标
4. 点击"生成卡片"按钮
5. 右键保存生成的卡片图片

### 本地部署

```bash
# 克隆仓库
git clone https://github.com/你的用户名/qrcode-generator.git

# 进入项目目录
cd qrcode-generator

# 直接用浏览器打开 index.html 即可使用
# 或使用本地服务器
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 📸 截图预览

### 主界面
![主界面](screenshot-main.png)

### 生成的卡片示例
![卡片示例](screenshot-card.png)

### 移动端界面
![移动端](screenshot-mobile.png)

## 🎨 配色方案

内置 10 种精心设计的配色方案：

- 🔵 经典蓝 - #4A90E2
- 🟢 清新绿 - #7CB342
- 🟣 优雅紫 - #9C27B0
- 🔴 活力红 - #E53935
- 🟠 温暖橙 - #FF9800
- 🟡 明亮黄 - #FDD835
- 🩷 浪漫粉 - #EC407A
- 🟤 沉稳棕 - #8D6E63
- ⚫ 经典黑 - #424242
- 🩵 天空蓝 - #26C6DA

## 🛠️ 技术栈

- **前端框架**: 纯原生 HTML5 + CSS3 + JavaScript
- **二维码生成**: [QRCode.js](https://davidshimjs.github.io/qrcodejs/)
- **字体**: Google Fonts (Inter + Noto Sans SC)
- **设计**: 现代玻璃态风格 + 渐变背景

## 📦 项目结构

```
qrcode-generator/
├── index.html          # 主页面文件（包含所有代码）
├── README.md           # 项目说明文档
└── screenshots/        # 截图文件夹（可选）
    ├── screenshot-main.png
    ├── screenshot-card.png
    └── screenshot-mobile.png
```

## 🌟 特色亮点

1. **单文件设计** - 所有代码集成在一个 HTML 文件中，无需额外依赖
2. **离线可用** - CDN 资源加载失败时自动降级
3. **用户友好** - 智能默认值和美观的提示系统
4. **现代 UI** - 采用最新的设计趋势和动画效果
5. **无障碍** - 良好的键盘导航和屏幕阅读器支持

## 📝 使用示例

### 基础用法

1. **个人名片**: 输入个人主页或社交媒体链接，生成个性化名片
2. **活动宣传**: 创建活动报名链接的宣传卡片
3. **产品推广**: 制作产品详情页的推广物料
4. **WiFi 分享**: 生成 WiFi 连接信息的二维码卡片

### 默认值说明

如果某些字段留空，系统会自动使用以下默认值：

- **链接地址**: `https://example.com`
- **卡片标题**: `扫码访问` / `Scan to Visit`
- **卡片描述**: `扫描二维码即可访问` / `Scan QR code to visit`

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

## 👤 作者

**GaoLiang**

- GitHub: (https://github.com/LeonGao0117)

## 🙏 致谢

- [QRCode.js](https://github.com/davidshimjs/qrcodejs) - 二维码生成库
- [Google Fonts](https://fonts.google.com/) - 提供优质字体
- 所有为本项目提供建议和反馈的用户

## 📊 更新日志

### v1.0.0 (2025-11-27)

- ✨ 初始版本发布
- 🎨 支持自定义配色和图标
- 🌐 中英文双语支持
- 📱 完美的移动端适配
- 💾 智能文件命名
- 🎯 友好的用户提示系统

---

<a name="english"></a>
## 📋 Introduction

QR Code Card Generator is an easy-to-use web tool that helps you quickly generate beautiful cards with QR codes. It supports custom colors, icons, and text, suitable for various scenarios such as business cards, event promotion, and product display.

## ✨ Features

- 🎨 **Customizable Design**
  - 10+ preset color schemes
  - Multiple emoji icon options
  - Custom card title and description
  
- 🌐 **Bilingual Support**
  - One-click switch between Chinese/English
  - Fully localized text and prompts
  
- 📱 **Responsive Design**
  - Perfect support for mobile and desktop
  - Adaptive screen size
  - Touch optimized
  
- 💾 **Easy to Save**
  - Right-click to save generated cards
  - Auto filename from card title
  - High-quality output (800x1200px)
  
- 🎯 **Smart Prompts**
  - Auto-fill empty fields with defaults
  - Beautiful confirmation dialogs
  - User-friendly guidance

## 🚀 Quick Start

### Online Use

1. Visit the [Demo Page](#) (replace with your GitHub Pages link)
2. Enter link URL, card title and description
3. Choose your favorite color and icon
4. Click "Generate Card" button
5. Right-click to save the generated card image

### Local Deployment

```bash
# Clone the repository
git clone https://github.com/yourusername/qrcode-generator.git

# Enter project directory
cd qrcode-generator

# Open index.html directly in your browser
# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5 + CSS3 + JavaScript
- **QR Code**: [QRCode.js](https://davidshimjs.github.io/qrcodejs/)
- **Fonts**: Google Fonts (Inter + Noto Sans SC)
- **Design**: Modern glassmorphism + gradient background

## 📝 Use Cases

1. **Business Cards**: Generate personalized cards with personal homepage or social media links
2. **Event Promotion**: Create promotional cards for event registration links
3. **Product Marketing**: Make promotional materials for product detail pages
4. **WiFi Sharing**: Generate QR code cards for WiFi connection info

## 🤝 Contributing

Issues and Pull Requests are welcome!

1. Fork this repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Submit Pull Request

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**GaoLiang**

- GitHub: (https://github.com/yourusername)

## 🙏 Acknowledgments

- [QRCode.js](https://github.com/davidshimjs/qrcodejs) - QR code generation library
- [Google Fonts](https://fonts.google.com/) - Quality fonts provider
- All users who provided suggestions and feedback

---

⭐ If you find this project helpful, please give it a star!

Made with ❤️ by GaoLiang
