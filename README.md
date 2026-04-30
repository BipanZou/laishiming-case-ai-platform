# 数据驱动注塑排产优化 · AI 教学平台

**Data-Driven Injection Molding Scheduling: An AI-Empowered Teaching Platform**

[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status: Active](https://img.shields.io/badge/status-active-brightgreen)]()
[![Apps: 7](https://img.shields.io/badge/AI%20Apps-7-blue)]()
[![Offline: Yes](https://img.shields.io/badge/offline-supported-success)]()

---

## 📖 项目简介 / Project Overview

本仓库是教学案例**「数据驱动注塑排产优化：莱势明汽车饰件的智能制造实践」**的配套教学支持材料，包含 **7 个真实可运行的 AI Web 应用工具**，覆盖案例从"问题诊断"到"价值评估"的完整教学链条。

This repository hosts the supplementary teaching materials for the case **"Data-Driven Injection Molding Scheduling: The AI-Empowered Smart Manufacturing Practice at Laishiming"**, featuring **7 fully functional AI Web applications** that span the entire teaching chain from "problem diagnosis" to "value evaluation".

### 🎯 核心特色 / Key Features

- ✅ **7 个真实可运行的 AI Web App**，无需安装、双击即开
- ✅ **完全离线可用**（Chart.js 已本地化）
- ✅ **完整教学链条**：诊断 → 数据 → 建模 → 学习 → 算法 → 决策 → 评估
- ✅ **AI 赋能教学**：LLM、机器学习、可解释 AI、AI 智能体全栈应用
- ✅ **MBA / 本科生双层教学**适配
- ✅ **中文界面**，专为中国管理学课堂优化

---

## 🚀 快速开始 / Quick Start

### 在线体验（推荐）/ Try Online

访问 **GitHub Pages**：[https://bipanzou.github.io/laishiming-case-ai-platform/](https://bipanzou.github.io/laishiming-case-ai-platform/)

直接在浏览器中打开 7 个 AI App 的总览页，点击任一卡片即可体验。

### 本地运行 / Run Locally

**方法 1：克隆仓库**
```bash
git clone https://github.com/BipanZou/laishiming-case-ai-platform.git
cd laishiming-case-ai-platform
# 双击 index.html
```

**方法 2：直接下载 ZIP**

点击 GitHub 页面右上角 `Code` → `Download ZIP` → 解压后双击 `index.html`

---

## 🛠️ 七个 AI Web 应用 / Seven AI Web Apps

| 序 | 阶段 | 应用 | 中文名 | 核心功能 |
|---|---|---|---|---|
| 1 | 🩺 诊断 | **DiagnosePilot** | 排产健康度AI诊断仪表板 | 5 维健康度评分 · 行业对标 · ROI 排序 |
| 2 | 📊 数据治理 | **DataPilot** | 排产数据治理AI助手 | 孤立森林异常检测 · KNN/GAN 补全 · LLM 特征工程 |
| 3 | 📐 数学建模 | **ModelTutor** | AI 运筹建模助教 | 自然语言→MIP 模型 · 对话式学习 · 无需写代码 |
| 4 | 🧠 参数学习 | **ParamLab** | AI 参数学习实验台 | 三方法估计对比 · SHAP 可解释性 · 全企业回测 |
| 5 | ⚡ 算法求解 | **AlgoLab** | 智能优化算法实验台 | 实时演化 · 超参数调优 · 4 种算法对比 |
| 6 | 📅 人机决策 | **SchedulePilot** | AI 排产决策智能助手 | 自然语言报告 · What-If 模拟 · 对话答疑 |
| 7 | 💰 价值评估 | **ROILab** | 数据驱动排产 ROI 仿真器 | 6 维 ROI 滑块 · 三方案 NPV · 敏感性分析 |

> 此外还包含一张 **AI 教学框架全景图**（`00_FrameworkOverview.html`），呈现 7 个工具的完整逻辑链与理论基础。

---

## 📁 仓库结构 / Repository Structure

```
laishiming-case-ai-platform/
├── README.md                    本文件
├── LICENSE                      CC BY-NC-SA 4.0
├── 0_使用说明_必读.txt          中文使用说明
├── index.html                   ⭐ 总览入口页（双击启动）
├── apps/                        7 个 AI Web 应用
│   ├── 00_FrameworkOverview.html
│   ├── 01_DataPilot.html
│   ├── 02_ModelTutor.html
│   ├── 03_SchedulePilot.html
│   ├── 04_ParamLab.html
│   ├── 05_AlgoLab.html
│   ├── 06_DiagnosePilot.html
│   └── 07_ROILab.html
├── lib/
│   └── chart.min.js             Chart.js 离线版（可视化依赖）
└── screenshots/                 各 App 静态截图
```

---

## 🎓 教学场景设计 / Teaching Scenarios

### MBA / EMBA 课堂建议（90 分钟）

| 时段 | 环节 | 推荐 App |
|---|---|---|
| 0~10 min | 案例导入与痛点分析 | **DiagnosePilot** |
| 10~25 min | 数据治理与特征工程 | **DataPilot** |
| 25~45 min | 数学建模与对话式学习 | **ModelTutor** |
| 45~65 min | 参数学习与算法求解 | **ParamLab + AlgoLab** |
| 65~80 min | 人机协同决策 | **SchedulePilot** |
| 80~90 min | 商业价值评估 | **ROILab** |

### 本科生重点

聚焦 **DataPilot / ModelTutor / ParamLab / AlgoLab**，培养"数据 + 建模 + 算法"硬核能力。

### MBA 学员重点

聚焦 **DiagnosePilot / SchedulePilot / ROILab**，培养"诊断 + 决策 + 评估"管理能力。

---

## 🔬 理论基础 / Theoretical Foundation

每个 AI Web App 均建立在经典理论之上：

| App | 核心理论 | 代表文献 |
|---|---|---|
| DiagnosePilot | 约束理论 TOC + 平衡计分卡 BSC | Goldratt 1984 / Kaplan & Norton 1992 |
| DataPilot | 数据驱动决策 + 数据治理 | Bertsimas & Kallus 2020 / DAMA-DMBOK |
| ModelTutor | 整数规划 + α\|β\|γ 调度分类 | Wolsey 2020 / Pinedo 2016 |
| ParamLab | 统计学习 + SHAP 可解释性 | Hastie et al. 2009 / Lundberg & Lee 2017 |
| AlgoLab | 进化计算 + 模拟退火 | Holland 1975 / Kirkpatrick 1983 / Glover 1986 |
| SchedulePilot | 技术接受 TAM + 可解释 AI | Davis 1989 / Kotter 1996 / Doshi-Velez 2017 |
| ROILab | NPV + 实物期权 + AHP | Brealey 2020 / Trigeorgis 1996 / Saaty 1980 |

---

## 📚 课程对接 / Course Alignment

本平台对接中国管理案例共享中心《**第十七届"全国百篇优秀管理案例"评选案例采编指南**》中：

- **运营管理 13-1**：数智时代的运营管理战略与创新
- **运营管理 13-2**：数智运营
- **管理信息系统与数智化转型 8-3**：大数据驱动的管理决策
- **供应链管理 10-4**：AI 赋能供应链创新

适用于以下课程：

- 《数智时代下的智能决策优化》（MBA）
- 《运营管理》《供应链管理》（本科）
- 《运筹学》《管理科学》（本科）
- 《数据科学与商业决策》（MBA / 本科）

---

## 💻 技术栈 / Tech Stack

- **前端**：Pure HTML5 + CSS3 + Vanilla JavaScript（无框架依赖）
- **可视化**：[Chart.js v4.4.7](https://www.chartjs.org/)（已本地化）
- **设计**：响应式布局，支持桌面/平板/手机访问
- **离线**：所有依赖本地化，断网完全可用

---

## 📜 引用 / Citation

如果您在教学或研究中使用了本平台，请引用：

**APA 格式：**
> 邹碧攀, 曹丽莉, 赵雁. (2026). 数据驱动注塑排产优化：莱势明汽车饰件的智能制造实践 [教学案例]. 中南财经政法大学工商管理学院 管理案例研究中心.
>
> Zou, B., Cao, L., & Zhao, Y. (2026). *Data-Driven Injection Molding Scheduling: The AI-Empowered Smart Manufacturing Practice at Laishiming* [Teaching case & companion AI platform]. School of Business Administration, Zhongnan University of Economics and Law.

**BibTeX：**
```bibtex
@misc{zou2026laishiming,
  author       = {Zou, Bipan and Cao, Lili and Zhao, Yan},
  title        = {Data-Driven Injection Molding Scheduling:
                  An AI-Empowered Teaching Platform},
  year         = {2026},
  institution  = {Zhongnan University of Economics and Law},
  url          = {https://github.com/BipanZou/laishiming-case-ai-platform}
}
```

---

## 📄 版权许可 / License

本项目采用 **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** 协议（署名 - 非商业 - 相同方式共享）。

- ✅ 教学使用：完全免费
- ✅ 学术研究：完全免费（请引用）
- ✅ 二次开发：允许（需相同协议共享）
- ⚠️ 商业用途：需联系作者授权

---

## 🤝 致谢 / Acknowledgements

- 本平台是 **2026 年中南财经政法大学工商管理学院管理案例研究中心立项项目** 成果
- 感谢 **武汉莱势明汽车饰件有限公司** 对案例研究的全面支持
- 感谢中国管理案例共享中心提供的案例采编规范指引
- 感谢所有参与案例开发与平台建设的师生

---

## 📮 联系方式 / Contact

| 项目负责人 | 邮箱 | 单位 |
|---|---|---|
| **邹碧攀**（Bipan Zou）| bipanzou@zuel.edu.cn | 中南财经政法大学工商管理学院 |

如在使用中遇到问题、有改进建议或希望合作开发，欢迎邮件联系。

---

<div align="center">

**🌟 如果本平台对您的教学/研究有帮助，欢迎给一个 Star 支持！**

Made with ❤️ for AI-Empowered Management Education

© 2026 邹碧攀 等 · 中南财经政法大学工商管理学院

</div>
