# Exercise Guidance 规则（Notebook 驱动）

> 目的：用“Notebook 教学 + 真实项目落地”的方式推进每一章，保证你能从零学会并能独立实现。

## 总体流程（每一章通用）
1) **先做 Notebook 教学**（只在 `memory_bank/notebooks/` 里产出）
2) **再落地到真实项目文件**（对应的 `connectors/ processors/ validators/` 等）
3) **最后回写 TODO-LIST + 对应章节 Guidance 文档**（记录完成情况与问题）

---

## Notebook 结构规范（每一章必须包含）
### A. 章节目标与知识点
- 用超详细的中文解释“本章要学会的知识点”
- 必须包含：
  - 工业场景下为什么需要这一步
  - 常见坑与失败案例
  - 实际工程的约束（性能/合规/质量）

### B. 最小示例（概念 Demo）
- 用最小代码说明核心概念
- 只依赖标准库（如必须额外依赖要说明原因）

### C. Exercise 1：有 Skeleton 版本
- 提供**半成品代码**（函数/类结构已给）
- 你只填关键逻辑
- 要给出：
  - TODO 注释
  - 输入/输出示例
  - 运行方式

### D. Exercise 2：无 Skeleton 版本
- 不给任何代码结构
- 只描述任务目标、输入输出、验收标准
- 你独立实现

### E. 自检清单（必须）
- 给出可自测的 checklist
- 包含“是否满足 schema”“是否可复现”“是否可解释”

---

## 章节推进规则
- 顺序可调整，但必须保证：
  - 每章 Notebook 完成后再落地代码
  - 完成 1 章后，更新 `memory_bank/TODO-LIST.MD`
  - 在对应 `memory_bank/todo/XX_*.MD` 记录问题与修正

---

## Notebook 文件命名规则
- `memory_bank/notebooks/01_多源采集与融合.ipynb`
- `memory_bank/notebooks/02_清洗与标准化.ipynb`
- 依此类推

---

## 验收标准（每章必须满足）
- Notebook 里**知识点极其详细**
- Exercise 1/2 均可独立执行
- 真实项目文件有对应落地
- TODO-LIST 与 Guidance 文档已更新

---

## 互动方式（与你协作）
- 我先生成 Notebook 初稿
- 你人工校验并反馈
- 我按反馈迭代优化

---

## 章节开始顺序（按你的要求）
- 从 **01 多源采集与融合** 开始
- 在推进 01 的过程中同步落地 00 的骨架

