# Railux Android

<div align="center">

![Railux Logo](https://img.shields.io/badge/Railux-AI%20Player-blue?style=for-the-badge)

**AI驱动的 Android 媒体播放器**

[![版本](https://img.shields.io/badge/版本-0.8.0-green.svg)](https://github.com/Railux-AI-Player/Railux-Android/releases)
[![许可证](https://img.shields.io/badge/许可证-GPL--3.0-blue.svg)](LICENSE)
[![平台](https://img.shields.io/badge/平台-Android-orange.svg)](https://www.android.com)

[功能特性](#功能特性) • [下载安装](#下载安装) • [截图展示](#截图展示) • [文档](#文档) • [参与贡献](#参与贡献)

</div>

---

## 项目简介

Railux Android 是一款现代化、功能丰富的 Android 媒体播放器应用。结合 AI 智能技术，为您提供卓越的观影体验，包括智能推荐、无缝播放等功能。

## 功能特性

### 🎬 **核心播放**
- 支持多种媒体格式
- 硬件加速视频解码
- 画中画 (PiP) 模式支持
- 后台播放功能
- 字幕支持 (SRT, VTT, ASS/SSA)

### 🤖 **AI 集成**
- 智能内容推荐
- 智能字幕匹配
- 自动元数据获取
- AI增强播放优化

### 📱 **用户体验**
- Material Design 界面设计
- 深色/浅色主题
- 手势控制 (滑动调整进度、音量、亮度)
- 继续观看功能
- 多服务器支持 (Jellyfin, Emby, WebDAV, SMB)

### 🌐 **多源支持**
- Jellyfin 媒体服务器集成
- Emby 服务器支持
- WebDAV 流媒体播放
- SMB/CIFS 网络共享
- 本地文件播放

### 🔧 **高级功能**
- 投屏支持
- 睡眠定时器
- 播放速度控制
- 音轨选择
- 章节导航
- Trakt 同步支持

## 下载安装

### 最新版本
从 [Releases](https://github.com/Railux-AI-Player/Railux-Android/releases) 页面下载最新 APK。

### 系统要求
- **Android 版本**: 5.0 (Lollipop) 或更高版本
- **处理器架构**: ARM64-v8a, ARMv7, x86, x86_64
- **存储空间**: 约 50MB 安装空间

### 安装步骤

1. 从 [Releases](https://github.com/Railux-AI-Player/Railux-Android/releases) 页面下载 APK 文件
2. 在 Android 设置中启用"允许安装未知来源应用"
3. 打开下载的 APK 文件
4. 按照安装提示完成安装

## 截图展示

<div align="center">

| 主页 | 详情页 | 播放器 |
|:----:|:------:|:------:|
| *即将推出* | *即将推出* | *即将推出* |

</div>

## 文档

- [用户指南](docs/USER_GUIDE_CN.md) (即将推出)
- [常见问题](docs/FAQ_CN.md) (即将推出)
- [更新日志](CHANGELOG.md)
- [贡献指南](CONTRIBUTING_CN.md) (即将推出)

## 支持的媒体服务器

| 服务器 | 状态 | 功能 |
|--------|------|------|
| Jellyfin | ✅ 完全支持 | 直播、转码、电视直播 |
| Emby | ✅ 完全支持 | 直播、转码 |
| WebDAV | ✅ 完全支持 | WebDAV服务器流媒体播放 |
| SMB/CIFS | ✅ 完全支持 | 网络共享浏览 |
| 本地 | ✅ 完全支持 | 本地文件播放 |

## 技术栈

- **开发语言**: Kotlin
- **架构模式**: MVVM + Clean Architecture
- **UI框架**: Jetpack Compose
- **媒体播放器**: Media3 ExoPlayer
- **依赖注入**: Koin
- **网络库**: OkHttp + Retrofit
- **数据库**: Room
- **图片加载**: Coil

## 从源码构建

本仓库仅包含发布版 APK 文件。源代码目前不对外公开。

## 参与贡献

我们欢迎各种形式的贡献！详情请查看 [贡献指南](CONTRIBUTING_CN.md)。

### 贡献方式
- 报告 Bug 和问题
- 提出新功能建议
- 改进文档
- 翻译应用

## 许可证

本项目基于 GNU General Public License v3.0 许可证 - 详情请查看 [LICENSE](LICENSE) 文件。

## 致谢

- [Jellyfin](https://jellyfin.org/) - 免费软件媒体系统
- [ExoPlayer](https://exoplayer.dev/) - Android Media3 库
- [Material Design](https://material.io/) - 设计规范

## 支持

- **问题反馈**: [GitHub Issues](https://github.com/Railux-AI-Player/Railux-Android/issues)
- **讨论交流**: [GitHub Discussions](https://github.com/Railux-AI-Player/Railux-Android/discussions)

## 项目状态

🟢 **活跃开发中** - 我们正在积极开发新功能和改进。

---

<div align="center">

由 Railux AI Player 团队用 ❤️ 打造

**[⬆ 返回顶部](#railux-android)**

</div>
