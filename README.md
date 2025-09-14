# 🏃‍♀️ FastFit - 智能健康管理平台

<div align="center">

![FastFit Logo](https://img.shields.io/badge/FastFit-健康生活新方式-2ECC71?style=for-the-badge&logo=heart&logoColor=white)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://choosealicense.com/licenses/mit/)

*开启健康生活新方式 - 您的专属智能健身伙伴* 🌟

</div>

---

## 📖 项目概述

**FastFit** 是一个现代化的智能健康管理平台，专为想要科学减重和保持健康生活方式的用户设计。通过先进的算法和直观的用户界面，为每位用户提供个性化的健康管理方案。

### 🎯 核心理念
- **科学减重** - 基于哈里斯-本尼迪克特方程的精准热量计算
- **个性化定制** - 根据用户数据生成专属健身计划
- **进度跟踪** - 实时监控健康数据变化趋势
- **用户友好** - 现代化玻璃质感UI设计，操作简单直观

---

## ✨ 核心功能

### 🏠 用户登录系统
- **智能验证** - 支持用户名/邮箱双重登录方式
- **密码安全** - 可视化密码切换，安全性与便利性并重
- **记住登录** - 本地存储支持，便捷的登录状态管理
- **响应式设计** - 完美适配各种设备屏幕

### 📊 个人资料设置
- **基础信息收集** - 性别、年龄、身高、体重等核心数据
- **目标制定** - 可视化滑块设置减重目标和时间周期
- **活动水平评估** - 五级活动强度分类，精准计算基础代谢
- **特殊情况处理** - 孕期等特殊状况的安全保护机制

### 🏃‍♂️ 智能运动推荐
- **个性化推荐** - 基于BMI和活动水平的智能运动方案
- **运动分级** - 从温和到高强度的渐进式训练计划
- **详细指导** - 每项运动的具体操作说明和注意事项
- **时长建议** - 科学的运动时间和频次推荐

### 📈 运动记录追踪
- **实时记录** - 便捷的运动数据输入和保存
- **数据统计** - 运动时长、消耗热量的自动计算
- **历史回顾** - 完整的运动历史记录查询
- **成就激励** - 运动里程碑和成就展示

### 📉 体重历史管理
- **数据可视化** - 直观的体重变化趋势图表
- **进度监控** - 实时跟踪减重进度和目标达成情况
- **数据导出** - 支持健康数据的导出和分享
- **长期追踪** - 建立个人健康数据档案

---

## 🚀 技术特色

### 🎨 现代化UI设计
- **玻璃质感** - Glassmorphism风格的现代化界面
- **动态背景** - 渐变色背景和浮动装饰元素
- **流畅动画** - CSS3动画增强用户体验
- **深色适配** - 支持深色模式的护眼设计

### 💾 数据持久化
- **本地存储** - 使用localStorage进行数据持久化
- **会话管理** - sessionStorage支持临时数据存储
- **数据备份** - 重要数据的自动备份机制
- **跨页面共享** - 无缝的数据传递和状态管理

### 📱 响应式布局
- **移动优先** - Mobile-First的设计理念
- **断点适配** - 多种屏幕尺寸的完美适配
- **触控优化** - 针对触控设备的交互优化
- **性能优化** - 轻量级代码，快速加载

---

## 🛠️ 项目结构

```
FastFit/
├── 📄 index.html          # 个人资料设置页面
├── 🔐 login.html          # 用户登录界面
├── 🏃‍♂️ exercise.html       # 运动推荐系统
├── 📊 workout.html        # 运动记录追踪
├── 📈 history.html        # 体重历史管理
├── 📋 需求文档.txt         # 项目需求文档
└── 📖 README.md          # 项目说明文档
```

### 📄 页面功能说明

| 文件名 | 功能描述 | 核心特性 |
|--------|----------|----------|
| `login.html` | 用户登录入口 | 表单验证、记住登录、密码切换 |
| `index.html` | 个人资料设置 | BMR计算、目标制定、数据验证 |
| `exercise.html` | 运动推荐系统 | 智能推荐、分级训练、详细指导 |
| `workout.html` | 运动记录追踪 | 实时记录、数据统计、历史回顾 |
| `history.html` | 体重历史管理 | 数据可视化、进度监控、趋势分析 |

---

## 🚀 快速开始

### 环境要求
- 现代化浏览器（Chrome 80+、Firefox 75+、Safari 13+、Edge 80+）
- 支持ES6的JavaScript环境
- 本地或云端Web服务器（可选）

### 安装步骤

1. **克隆项目**
   ```bash
   git clone https://github.com/ifLabVibe/FastFit.git
   cd FastFit
   ```

2. **启动项目**
   ```bash
   # 方式一：直接打开HTML文件
   open login.html

   # 方式二：使用本地服务器
   python -m http.server 8000
   # 或者
   npx serve .
   ```

3. **访问应用**
   - 直接访问：双击 `login.html` 文件
   - 服务器访问：http://localhost:8000/login.html

### 使用流程

1. **🔐 用户登录** - 在 `login.html` 输入用户名和密码
2. **📊 设置资料** - 在 `index.html` 完善个人健康信息
3. **🏃‍♂️ 运动推荐** - 在 `exercise.html` 查看个性化运动方案
4. **📈 记录运动** - 在 `workout.html` 记录每次运动数据
5. **📉 查看进度** - 在 `history.html` 追踪体重变化趋势

---

## 🔧 核心算法

### 基础代谢率（BMR）计算
```javascript
// 男性：BMR = 88.362 + (13.397 × 体重kg) + (4.799 × 身高cm) - (5.677 × 年龄)
// 女性：BMR = 447.593 + (9.247 × 体重kg) + (3.098 × 身高cm) - (4.330 × 年龄)
```

### 总消耗热量（TDEE）计算
```javascript
const activityMultipliers = {
    'sedentary': 1.2,      // 久坐
    'light': 1.375,        // 轻度活动
    'moderate': 1.55,      // 中度活动
    'active': 1.725,       // 高度活动
    'very_active': 1.9     // 极高活动
};
```

### 减重速度计算
```javascript
// 1kg脂肪 ≈ 7700kcal
const dailyDeficit = (weightToLose * 7700) / (weeksToLose * 7);
const recommendedIntake = totalCalories - dailyDeficit;
```

---

## 📱 兼容性

### 浏览器支持
| 浏览器 | 版本要求 | 支持状态 |
|--------|----------|----------|
| Chrome | 80+ | ✅ 完全支持 |
| Firefox | 75+ | ✅ 完全支持 |
| Safari | 13+ | ✅ 完全支持 |
| Edge | 80+ | ✅ 完全支持 |
| IE | ❌ | ❌ 不支持 |

### 设备适配
- **💻 桌面端** - 完美支持各种分辨率
- **📱 移动端** - 响应式设计，触控优化
- **📱 平板端** - 中屏幕尺寸优化适配

---

## 🤝 贡献指南

我们欢迎所有形式的贡献！无论是新功能、错误修复还是文档改进。

### 贡献步骤

1. **Fork 项目**
2. **创建功能分支** (`git checkout -b feature/AmazingFeature`)
3. **提交更改** (`git commit -m 'Add some AmazingFeature'`)
4. **推送分支** (`git push origin feature/AmazingFeature`)
5. **创建 Pull Request**

### 开发规范

- **代码风格** - 遵循现有的代码风格和命名规范
- **提交信息** - 使用清晰、描述性的提交信息
- **测试** - 确保新功能有适当的测试覆盖
- **文档** - 更新相关文档和注释

---

## 🐛 问题反馈

遇到问题？我们来帮助您！

### 报告方式
- **GitHub Issues** - [提交Issue](https://github.com/ifLabVibe/FastFit/issues)
- **功能建议** - [Feature Request](https://github.com/ifLabVibe/FastFit/issues/new?template=feature_request.md)
- **错误报告** - [Bug Report](https://github.com/ifLabVibe/FastFit/issues/new?template=bug_report.md)

### 常见问题

<details>
<summary><b>Q: 数据会丢失吗？</b></summary>
A: 数据存储在浏览器本地存储中，清除浏览器数据时会丢失。建议定期导出数据备份。
</details>

<details>
<summary><b>Q: 支持多用户吗？</b></summary>
A: 当前版本为单用户设计，未来版本将支持多用户功能。
</details>

<details>
<summary><b>Q: 如何导出数据？</b></summary>
A: 在历史页面点击导出按钮，可导出JSON格式的健康数据。
</details>

---

## 📋 更新日志

### v1.0.0 (2024-01-15)
- 🎉 项目初始版本发布
- ✨ 完整的用户登录系统
- ✨ 个人资料设置功能
- ✨ 智能运动推荐系统
- ✨ 运动记录追踪功能
- ✨ 体重历史管理
- 🎨 玻璃质感UI设计
- 📱 响应式布局支持

---

## 🔮 未来规划

### 🚀 短期目标（v1.1）
- [ ] **数据备份恢复** - 云端数据同步功能
- [ ] **社交功能** - 好友系统和排行榜
- [ ] **运动视频** - 内置运动指导视频
- [ ] **营养建议** - 智能饮食推荐系统

### 🌟 长期目标（v2.0）
- [ ] **AI教练** - 基于机器学习的个性化指导
- [ ] **设备集成** - 智能穿戴设备数据同步
- [ ] **健康报告** - 专业的健康分析报告
- [ ] **多平台支持** - 移动端APP开发

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE) - 详细信息请查看 LICENSE 文件。

```
MIT License

Copyright (c) 2024 FastFit Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software")...
```

---

## 🙏 致谢

感谢所有为 FastFit 项目做出贡献的开发者和用户！

### 特别感谢
- **设计灵感** - 来自现代化健康应用的UI/UX设计
- **技术支持** - 现代Web技术栈的强大能力
- **社区支持** - 开源社区的无私帮助和反馈

### 技术栈致谢
- **HTML5** - 现代化标记语言
- **CSS3** - 强大的样式和动画支持
- **JavaScript ES6+** - 现代化的脚本语言特性
- **Font Awesome** - 美观的图标库（计划集成）

---

<div align="center">

### 🌟 如果这个项目对您有帮助，请给我们一个 ⭐ Star！

**让我们一起创造更健康的生活方式！** 💪

---

<sub>🤖 本README由 [Claude Code](https://claude.ai/code) 智能生成并优化</sub>

</div>