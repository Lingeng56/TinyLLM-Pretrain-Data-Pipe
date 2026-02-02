# 学习流程 Guidance（TinyLLM 预训练数据流水线 · 工业级扩展版）

> 目标：用“学会知识点 + 动手实践”的方式，逐步搭建一个可扩展、多源、可追溯、可复现、可监控的数据管道。

## 使用方式
- 每个阶段都有独立 guidance 文档，路径：`memory_bank/todo/`
- 完成阶段后：
  - 在对应文档里补充“实际命令 / 遇到的问题 / 修正点”
  - 回到本文件勾选完成状态

## Guidance 索引
- [ ] 00 工程骨架与标准：`memory_bank/todo/00_工程骨架与标准.MD`
- [ ] 01 多源采集与融合：`memory_bank/todo/01_多源采集与融合.MD`
- [ ] 02 清洗与标准化：`memory_bank/todo/02_清洗与标准化.MD`
- [ ] 03 质量过滤：`memory_bank/todo/03_质量过滤.MD`
- [ ] 04 版本管理与可追溯：`memory_bank/todo/04_版本管理与可追溯.MD`
- [ ] 05 Tokenizer 与序列化：`memory_bank/todo/05_Tokenizer与序列化.MD`
- [ ] 06 数据打包与训练对接：`memory_bank/todo/06_数据打包与训练对接.MD`
- [ ] 07 数据质量指标体系：`memory_bank/todo/07_数据质量指标体系.MD`
- [ ] 08 性能与工程化：`memory_bank/todo/08_性能与工程化.MD`
- [ ] 09 评估与实验对比：`memory_bank/todo/09_评估与实验对比.MD`
- [ ] 10 文档与复现：`memory_bank/todo/10_文档与复现.MD`

## 里程碑
- [ ] M1：多源采集 + 清洗 + 过滤闭环
- [ ] M2：tokenizer + packer + 训练可用格式
- [ ] M3：质量指标体系 + 可追溯版本管理
- [ ] M4：性能优化 + 断点续跑 + 对比评估

---

备注：每个阶段完成后在对应 guidance 文档追加“问题记录 / 下一步计划”。
