# University-Town-Food-Map-A-Meituan-Review
# 📍 UniEats - 大学城美食地图 (校友味蕾)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/Version-1.0.0-blue.svg)]()

> **“今天吃什么？”不再是难题。**  
> 专门为高校联盟（3-5所大学）学生定制的本地化美食决策工具。

---

## 🌟 项目背景 (Project Background)

在高校周边，虽然餐饮商户林立，但学生普遍面临以下困境：
- **信息分散**：好店藏在后街，大众点评或外卖平台的信息不够“学生化”。
- **决策困境**：选择太多导致“决策疲劳”，缺乏趣味性的推荐。
- **特定需求**：学生更关注“是否有插座自习”、“月底救急（便宜）”、“适合宿舍聚餐”等特定标签。

**UniEats** 通过地图可视化和趣味化交互，一站式解决这些问题。

## ✨ 核心功能 (Key Features)

- **📍 交互式地图视图**：基于 Leaflet.js 渲染，直观查看校门口的餐厅分布及步行距离。
- **🏷️ 学生定制化标签**：
    - `月底救急`：高性价比（人均 <￥20）。
    - `有插座`：适合带电脑自习/写论文。
    - `宿舍聚餐`：适合多人团建。
- **🎲 纠结症救星 (Random Pick)**：一键随机抽取，“盲盒”式决定今天的午餐。
- **📱 响应式设计**：完美适配手机浏览器，走在路上也能随时查看。

## 🛠️ 技术栈 (Tech Stack)

- **前端框架**: [Tailwind CSS](https://tailwindcss.com/) (快速响应式 UI 开发)
- **地图引擎**: [Leaflet.js](https://leafletjs.com/) (轻量级开源地图组件)
- **地图数据源**: [OpenStreetMap](https://www.openstreetmap.org/)
- **部署工具**: Vercel / GitHub Pages

## 🚀 快速开始 (Quick Start)

该项目目前是一个**单文件原型**版本，无需复杂的环境配置即可运行：

1. **克隆仓库**:
   ```bash
   git clone https://github.com/你的用户名/unieats-map.git
