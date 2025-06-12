# Android-Position

## 📱 项目简介

Android Position 是一个基于位置服务的Android应用程序，集成了高德地图API和LeanCloud后端服务，提供完整的位置相关功能解决方案。

## 🔧 技术栈

- **地图服务**: 高德地图 API
- **后端服务**: LeanCloud API
- **开发平台**: Android
- **开发语言**: Java/Kotlin

## ✨ 主要功能

- 🎯 **实时定位** - 获取当前精确位置信息
- 🔍 **周边搜索** - 搜索附近的兴趣点和服务
- 🗺️ **导航服务** - 提供路线规划和导航功能
- 📸 **拍照定位** - 拍照时自动记录位置信息
- ☁️ **云端存储** - 将位置数据上传至云端
- 📍 **位置分享** - 与他人分享位置信息
- 🤝 **位置共享** - 实时位置共享功能

## 🚀 快速开始

### 环境要求

- Android Studio
- Android SDK (API 21+)
- 高德开发者账号
- LeanCloud开发者账号

### 配置步骤

1. **注册开发者账号**
   - [高德开放平台](https://lbs.amap.com/) - 获取地图API Key
   - [LeanCloud](https://www.leancloud.cn/) - 获取应用Key

2. **配置API密钥**
   
   在项目中找到相关配置文件，替换以下Key：
   ```java
   // 高德地图API Key
   private static final String AMAP_KEY = "your_amap_key_here";
   
   // LeanCloud配置
   private static final String LEANCLOUD_APP_ID = "your_app_id_here";
   private static final String LEANCLOUD_APP_KEY = "your_app_key_here";
   ```

4. **编译运行**
   ```bash
   ./gradlew assembleDebug
   ```

## 📚 文档说明

项目包含以下文档：
- 📄 **开发文档** - 详细的技术实现说明
- 📋 **软件说明** - 功能使用指南
- 🎯 **作业讲解** - 项目演示PPT

## ⚠️ 重要提醒

- ⚡ **API Key替换**: 必须将项目中的所有API Key替换为您自己申请的密钥
- 🔒 **数据安全**: 未替换Key会将数据发送到我的后台
- 🎓 **学习用途**: 本项目仅供学习参考


## 🛠️ 项目结构

```
Android-Position/
├── app/                    # 主应用模块
├── docs/                   # 项目文档
├── gradle/                 # Gradle配置
├── README.md              # 项目说明
└── .gitignore             # Git忽略文件
```


## 📧 联系方式

如需帮助或有任何问题，请联系：

📮 **邮箱**: iyy021150@163.com

---

## 📄 许可证

本项目仅供学习使用，请遵守相关API服务商的使用条款。

---

⭐ **如果这个项目对您有帮助，请给个Star支持一下！**
