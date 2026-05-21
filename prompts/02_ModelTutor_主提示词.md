# ModelTutor 主提示词（教学型 Prompt 模板）

## 角色（Role）
你是一名同时精通整数规划与管理学院教学法的资深教授（Pinedo + Wolsey 风格）。

## 任务（Task）
开发单文件 HTML 应用 ModelTutor，让 MBA 学员在浏览器内通过自然语言完成"业务问题 → α|β|γ 调度分类 → MIP 数学模型 → Pyomo 代码"四步转换。

## 约束（Constraints）
- 单文件 HTML，不依赖 Node.js；引入本地 lib/chart.min.js
- 内置 8 个业务模板：
  ① 莱势明并行机调度 P|sij,prec|Cmax
  ② 注塑模具一维下料 CSP
  ③ 客户配送 CVRP
  ④ 多品种动态批量 CLSP
  ⑤ 工人-工序最优分配 GAP
  ⑥ 换模顺序优化 TSP
  ⑦ 作业车间 Job Shop
  ⑧ 流水作业排列调度 Flow Shop
- 教学侧边栏必须出现 α|β|γ 三段分类的可视化动画
- 代码区生成的 Pyomo / Gurobi 双版本都必须含中文注释，便于学员逐行讲解
- 全部中文 UI；色彩遵循"莱势明蓝 #1F4E79"主色调
- 包含 11 个 FAQ 知识点（MIP / NP-hard / Big-M / MTZ 等）的对话式答疑模块

## 输入示例（One-shot Example）
学员输入："我们有 29 台不同吨位的注塑机，80 个订单要在 7 天内完工，订单切换会带来换模时间。"
→ 期望输出：α=R（异构并行机）, β=sij（序相关换模）, γ=Cmax（最大完工时间）

## 输出格式（Output Format）
返回完整 HTML，包含：
- 顶部教学引导（α|β|γ 分类含义）
- 左侧 8 个模板选择
- 中间自然语言输入框 + 智能分类按钮
- 右下 5 个 Tab（数学模型 / Pyomo 代码 / Gurobi 代码 / 复杂度分析 / 随机规划扩展）
- 底部 AI 对话答疑

## 反思（Self-Critique）
生成完毕后请自检：
1. MBA 学员零编程基础是否能用？
2. Pyomo 代码能否真实运行？（CBC 默认求解器）
3. 8 个模板的 α|β|γ 分类是否准确？
4. FAQ 是否覆盖了 MBA 学员最常问的问题？

---
开发实测：DeepSeek-V3 一次性生成 4,800 行 HTML，Qwen2.5-Max 二轮校验，开发耗时 3 小时。
