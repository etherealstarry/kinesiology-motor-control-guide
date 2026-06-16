# 自动化任务执行记录

## 任务：Kinesiology 网站自动维护与内容更新

### 最近执行记录

- **2026-06-10**：执行更新。
  - 添加 1 篇顶刊论文：
    1. Nature Neuroscience (2026 年 6 月 9 日) — "Human learning of noninvasive brain–computer interfaces via manifold geometry"
  - 提交：`25fc2b2 chore: 自动更新 - 2026-06-10`
  - 部署：成功（HTTP 200）
  - 注意：论文关于脑机接口学习的流形几何机制，与运动学习相关，属于顶刊高质量内容

- **2026-06-09**：执行更新。
  - 添加 2 篇顶刊论文：
    1. Nature Neuroscience (2026 年 6 月 8 日) — "Induction of cortical on/off periods in awake mice fulfills sleep functions"
    2. NeuroImage (2026 年 5 月 1 日) — "Harmonizing the stimulation dose of focal transcranial direct current stimulation across target sites"
  - 提交：`e380e99 chore: 自动更新 - 2026-06-09`
  - 部署：成功（HTTP 200）
  - 注意：Nature Neuroscience 论文非常新（1 天前发表），关于睡眠与记忆巩固；NeuroImage 论文是 tDCS 方法学的重要进展

- **2026-06-07**：执行更新。
  - 添加 1 篇顶刊论文：Nature Neuroscience (2026 年 5 月 1 日) — "A communication subspace relays context-dependent actions from human prefrontal to motor cortex"
  - 添加 Daniel Wolpert 教授讲座视频（ICTP-ICTS Winter School）到 `docs/拓展资源/在线课程.md`
  - 提交：`b260b70 chore: 自动更新 - 2026-06-07`
  - 部署：成功（HTTP 200）
  - 注意：搜索近 1 个月顶刊论文结果有限，只找到 1 篇符合标准的 Nature Neuroscience 论文（5 月 1 日发表，略超 1 个月但仍属近期高质量内容）

- **2026-06-03**：跳过更新。原因：今天已有提交 `96d040e fix: 修正 README 中的网站链接`，根据"每天最多提交 1 次"规则，跳过本次自动更新。

### 执行规则摘要

1. 每天最多提交 1 次（通过 `git log --since="today 00:00"` 检查）
2. 只添加高质量内容（顶刊论文、知名教授工作、高被引论文）
3. 影响因子 < 5 的期刊论文不添加
4. 预印本（bioRxiv, arXiv）除非已被顶刊接收，否则不添加
5. 提交前必须先 `mkdocs build` 检查无警告
6. 提交信息用中文，简洁明了
7. WebSearch 工具对近期顶刊论文搜索效果有限，建议结合 WebFetch 直接访问期刊官网获取最新论文列表
