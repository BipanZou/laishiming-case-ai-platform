# 莱势明 AI 排产教学平台 · 完整配套资源 v2.0

> **AI 赋能数据驱动的注塑排产优化** — 7 个真实可运行的 AI Web 应用 + 57 万行真实业务数据 + 完整教学文档体系

[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status: v2.0](https://img.shields.io/badge/version-v2.0-blue)]()
[![Apps: 7](https://img.shields.io/badge/AI%20Apps-7-green)]()
[![Data: 572K rows](https://img.shields.io/badge/dataset-572,505%20rows-orange)]()
[![Offline: Yes](https://img.shields.io/badge/offline-supported-success)]()

---

## 📦 资源清单

| 目录 | 内容 | 数量 | 大小 |
|---|---|---|---|
| `apps/` | 7 个 AI Web 应用（HTML 单文件，断网可用） | 8 个 HTML | ~5.9 MB |
| `datasets/` | 14 张莱势明业务数据表（CSV） | 14 个 CSV | ~42 MB |
| `docs/app_manuals/` | 7 份独立 App 使用手册（PDF） | 7 个 PDF | ~1.7 MB |
| `notebooks/` | Python Notebook 等效代码 | 6 个 .ipynb | ~50 KB |
| `prompts/` | 教学型提示词全集 + 开发记录 | 11 个 MD | ~40 KB |
| `lib/` | Chart.js v4.4.7 离线版 | 1 个 JS | ~205 KB |
| `index.html` | 平台总览入口（双击启动） | 1 个 HTML | ~14 KB |
| **总计** | | **~50 个文件** | **~50 MB** |

---

## 🎯 七大 AI Web 应用（覆盖完整教学链条）

| 序 | 阶段 | 应用 | 中文名 | 核心功能 | 版本 |
|---|---|---|---|---|---|
| 1 | 📊 治理 | **DataPilot** | 排产数据治理 AI 助手 | CSV 拖拽 · 4 异常算法 · 5 填补策略 | v1.0 |
| 2 | 📐 建模 | **ModelTutor** | AI 运筹建模助教 | 自然语言 → α\|β\|γ → Pyomo / Gurobi 双代码 | **v2.0 Pro** |
| 3 | 🎯 决策 | **SchedulePilot** | AI 排产决策智能助手 | 6 What-If 场景 · 4 方案对比 · 自然语言报告 | **v2.0 Pro** |
| 4 | 📈 学习 | **ParamLab** | AI 参数学习实验台 | OLS / Ridge / Lasso / RF + SHAP | **v2.0 Pro** |
| 5 | ⚡ 算法 | **AlgoLab** | 智能优化算法实验台 | GA / SA / TS / ALNS + 5 实例 | **v2.0 Pro** |
| 6 | 🩺 诊断 | **DiagnosePilot** | 排产健康度 AI 诊断仪表板 | 5 维健康度 · 3 类对标 · 7 ROI 排序 | **v2.0 Pro** |
| 7 | 💰 评估 | **ROILab** | 数据驱动排产 ROI 仿真器 | NPV / IRR / Tornado / Monte Carlo 10K | **v2.0 Pro** |

---

## 📊 14 张莱势明业务数据表（共 572,505 行）

| # | 文件 | 行数 | 内容 |
|---|---|---|---|
| 1 | `machines.csv` | 29 | 29 台异构注塑机基础属性 |
| 2 | `products.csv` | 293 | 产品 SKU 主数据 |
| 3 | `customers.csv` | 20 | Tier 1 + 整车厂客户 |
| 4 | `operators.csv` | 48 | 操作员主数据 |
| 5 | `work_orders.csv` | **50,000** | 28 个月历史工单 |
| 6 | `machine_daily_logs.csv` | **200,000** | 30 分钟级设备日志 |
| 7 | `changeovers.csv` | 49,382 | 换模记录 |
| 8 | `deliveries.csv` | 30,000 | 客户交付记录 |
| 9 | `quality_inspections.csv` | 60,000 | 质量检验记录 |
| 10 | `material_consumption.csv` | 45,000 | 物料消耗记录 |
| 11 | `energy_logs.csv` | 73,950 | 能耗日志 |
| 12 | `operator_shifts.csv` | 40,783 | 操作员班次出勤 |
| 13 | `maintenance_events.csv` | 8,000 | 设备维修事件 |
| 14 | `inventory_snapshots.csv` | 15,000 | 库存日快照 |

---

## 🚀 快速开始

### 方法 1：本地双击启动（推荐）
```bash
1. 解压本资源 ZIP 到任意目录
2. 双击 index.html → 平台总览页打开
3. 点击任一应用卡片即可启动对应 AI Web 应用
```

### 方法 2：在线访问
- **Gitee Pages（主线）**：https://gitee.com/BipanZou/laishiming-case-ai-platform
- **GitHub Pages（镜像）**：https://bipanzou.github.io/laishiming-case-ai-platform/

### 方法 3：用 Python Notebook
```bash
cd notebooks/
jupyter notebook
# 打开任一 .ipynb 文件，按顺序运行单元格
```

---

## 📚 完整文档体系

### A. 每个 App 的独立使用手册（PDF）
`docs/app_manuals/` 目录下有 7 份 PDF 手册，每份覆盖：
- 应用简介与版本信息
- 安装与启动步骤
- 核心功能清单（表格化）
- 详细使用步骤
- 参数详解
- 理论基础与参考文献
- 教学场景设计（MBA + 本科）
- 常见问题 FAQ
- 扩展开发指南

### B. Python Notebook 等效代码（`notebooks/`）
6 份 Jupyter Notebook，对应 5 个核心算法应用 + 1 份数据探索：
- `00_数据探索_14张业务表.ipynb` — 数据集深度探索
- `01_DataPilot_数据治理.ipynb` — 4 异常 + 5 填补 + 5 维质量评分
- `02_ModelTutor_Pyomo完整实现.ipynb` — Pyomo R\|\|Cmax 求解
- `04_ParamLab_完整Python实现.ipynb` — OLS / Ridge / Lasso / RF + SHAP
- `05_AlgoLab_元启发式Python实现.ipynb` — GA / SA / TS / ALNS
- `07_ROILab_NPV与MonteCarlo.ipynb` — NPV / IRR / Tornado / Monte Carlo

### C. 提示词全集（`prompts/`）
11 份 Markdown 文档：
- `99_六段式模板说明.md` — "角色—任务—约束—示例—输出格式—反思"通用模板
- `01-07_*_主提示词.md` — 7 个应用的完整提示词（可直接复用）
- `_开发记录.md` — 项目完整开发时间线与团队分工

---

## 🛠 技术栈

- **前端框架**：Pure HTML5 + CSS3 + Vanilla JavaScript（无框架依赖）
- **可视化**：Chart.js v4.4.7（已本地化）
- **大模型**：DeepSeek-V3 / 通义千问 Qwen2.5-Max / 智谱 GLM-4 Plus
- **AI 编程助手**：通义灵码 / 字节 Trae / 腾讯 CodeBuddy
- **代码托管**：Gitee（主线）+ GitHub（镜像）
- **离线**：所有依赖本地化，断网完全可用

---

## 🎓 教学场景

### MBA / EMBA 课堂（90 分钟）
| 时段 | 环节 | 应用 |
|---|---|---|
| 0–10 min | 案例导入 | DiagnosePilot |
| 10–25 min | 数据治理 | DataPilot |
| 25–45 min | 数学建模 | ModelTutor |
| 45–65 min | 参数学习 | ParamLab + AlgoLab |
| 65–80 min | 人机决策 | SchedulePilot |
| 80–90 min | 商业评估 | ROILab |

### 本科课堂（4 学时课堂 + 4 学时实验）
- 重点应用：DataPilot / ModelTutor / ParamLab / AlgoLab（4 个偏技术）
- 实验作业：Pyomo 代码、4 算法 Benchmark、Python Notebook 复现

---

## 📜 引用

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

## 📄 版权许可

本项目采用 **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** 协议
- ✅ 教学使用：完全免费
- ✅ 学术研究：完全免费（请引用）
- ✅ 二次开发：允许（需相同协议共享）
- ⚠️ 商业用途：需联系作者授权

---

## 📮 联系方式

| 项目负责人 | 邮箱 | 单位 |
|---|---|---|
| **邹碧攀**（Bipan Zou）| bipanzou@zuel.edu.cn | 中南财经政法大学工商管理学院 |

**团队成员**：邹碧攀（教授）· 曹丽莉（副教授）· 赵雁（副教授）

---

© 2026 邹碧攀 等 · 中南财经政法大学工商管理学院 · CC BY-NC-SA 4.0
