# KINE 640: Motor Neuroscience II

> 博士核心理论进阶课 | 3 学分 | Spring 学期 | Lei / Buchanan / Du 授课

---

## 📋 课程信息

| 维度 | 详情 |
|------|------|
| 学分 | 3 |
| 学期 | Spring（第二学期） |
| 先修 | KINE 606（建议） |
| 班级规模 | 8-12 人 |
| 授课教授 | Yuming Lei（最可能）、Buchanan、Yue Du（轮换） |
| 评估方式 | 论文讨论 + method presentation + final research proposal |

---

## 👨‍🏫 教授教学风格

| 维度 | Lei（最可能） | Buchanan | Du |
|------|-------------|----------|-----|
| RMP | 4.0/5 | 2.4/5 | 🆕 |
| 教学侧重 | 脑刺激方法学、实验设计 | 理论辩论、模型比较 | 计算建模、心理物理学 |
| 课件 | 不够用，需自建知识 | 课件=全部考点 | 未知 |
| 口音 | ⚠️ 中文口音 | 清晰 | 清晰 |
| 优势 | 活跃研究者，可能打开 rotation | Program Chair，影响深远 | 研究兴趣与你重合 |

---

## 🔬 核心知识体系

### 四大模块

```
模块 1: 理论辩论
├── FBS (Feldman) vs OFC (Todorov)
├── OFC vs Active Inference
└── 各脑区在 OFC 中的角色分工

模块 2: 神经调控技术
├── TMS（经颅磁刺激）
├── tDCS/tACS（经颅电刺激）
├── EEG（脑电图）
└── fMRI（功能磁共振）

模块 3: 运动学习前沿
├── 多时间尺度学习模型
├── 显性 vs 隐性学习
└── Savings & Spontaneous Recovery

模块 4: 计算建模
├── OFC 仿真
├── 贝叶斯模型
└── 强化学习模型
```

---

## 📝 自编概念闪卡

### 理论辩论（15 张）

| # | 正面 | 背面 |
|---|------|------|
| 1 | FBS (Equilibrium-Point Hypothesis) 核心主张？ | 运动由 λ (muscle threshold length) 控制，CNS 不计算力而设定平衡点 |
| 2 | OFC 如何反驳 FBS？ | FBS 解释不了为什么 deafferented 病人仍能运动中纠正误差（反馈增益 K_t 是预编程的） |
| 3 | Active Inference 的最小化目标？ | 自由能 (Free Energy) = 惊喜 (Surprise) + 复杂性 |
| 4 | Active Inference 如何解释运动？ | 运动 = 通过行动(采样)减少对感觉后果的预测不确定性 |
| 5 | OFC 和 Active Inference 的根本区别？ | OFC 最小化 cost function，Active Inference 最小化 surprise |
| 6 | M1 在 OFC 中的角色？ | 实施最优反馈增益 K_t — TMS 改变 M1 兴奋性会改变反馈增益 |
| 7 | 小脑在 OFC 中的角色？ | 正向模型 — 预测动作的感觉后果 |
| 8 | 基底节在 OFC 中的角色？ | 动作选择 + 运动 vigor（多巴胺调节 effort 的 cost） |
| 9 | 顶叶在 OFC 中的角色？ | 多感觉状态估计 — 结合视觉和本体感觉信息 |
| 10 | 为什么 OFC 成为主流而 FBS 被边缘化？ | OFC 有更强的预测力（能预测 optimal feedback gain），且有神经生理证据支持 |

### 神经调控技术（15 张）

| # | 正面 | 背面 |
|---|------|------|
| 11 | TMS 的原理？ | 法拉第电磁感应 → 线圈电流 → 磁场 → 皮层去极化 |
| 12 | MEP (Motor Evoked Potential) 是什么？ | TMS 刺激 M1 → EMG 记录到的肌肉反应 → 衡量皮层脊髓兴奋性 |
| 13 | RMT (Resting Motor Threshold) 的定义？ | 静息状态下 TMS 50% 概率诱发 >50 μV MEP 的最小刺激强度 |
| 14 | SICI vs ICF？ | SICI=短间隔皮层内抑制(GABA_A)；ICF=皮层内易化(谷氨酸) |
| 15 | rTMS 的 LTP/LTD 类效应？ | 高频 rTMS(≥5Hz)→LTP 类增强；低频(≤1Hz)→LTD 类抑制 |
| 16 | tDCS 的 Anodal vs Cathodal？ | Anodal=去极化→兴奋性↑；Cathodal=超极化→兴奋性↓ |
| 17 | tDCS 相比 TMS 的优势和劣势？ | 优势=便宜 可做 sham 双盲；劣势=效应量小 重复性争议 |
| 18 | EEG 的 ERD/ERS 分别代表什么？ | ERD=事件相关去同步化(皮层激活)；ERS=事件相关同步化(抑制/休息) |
| 19 | fMRI 的 BOLD 信号和神经元活动的关系？ | BOLD = 氧合/脱氧血红蛋白比值变化 → 不是直接测量神经元活动 |
| 20 | MVPA (多体素模式分析) 相比传统 GLM 的优势？ | GLM 看"哪里激活"；MVPA 看"激活模式编码了什么信息" |

### 运动学习前沿（10 张）

| # | 正面 | 背面 |
|---|------|------|
| 21 | Savings 的定义和可能的神经机制？ | 再次学习更快——反映的是"还记得怎么补偿"，不是"适应快" |
| 22 | Spontaneous Recovery 说明什么？ | 适应消退后，休息→偏差自发恢复 — 说明记忆没有被 erase，只是被新记忆抑制 |
| 23 | 多时间尺度模型的基本思想？ | 学习=快速过程(对误差敏感但遗忘快) + 慢速过程(对误差不敏感但保持好) |
| 24 | 显性策略 (Explicit Strategy) 和隐性适应 (Implicit Adaptation) 如何分离？ | 显性=可以口头报告的瞄准策略；隐性=不受意识控制的逐步偏转 |
| 25 | 为什么显性和隐性学习会竞争？ | 显性策略减少了感觉预测误差→隐性适应减少→Savings 降低 |

---

## ✏️ 自编模拟考题

### 概念辨析

**Q1**：OFC 说"中枢神经系统选择最优反馈增益 K_t 来最小化运动成本和精度的综合代价"。Active Inference 说"中枢神经系统通过行动减少预测不确定性"。举一个具体实验例子，说明哪种解释更有说服力。

**Q2**：你用 TMS 刺激 M1 让受试在做 reach 任务时产生 MEP。如果让受试用更大的力，MEP 会怎么变化？如果让受试做更精确的任务，MEP 会怎么变化？从 OFC 的角度解释。

### 实验设计

**Q3**：你想验证"小脑是正向模型"这个假说。设计一个实验：
- 用什么任务？（说明为什么选这个）
- 怎么做"虚拟损伤"？
- 预测小脑 TMS/损伤后的行为缺陷是什么？

**Q4**：有人声称 tDCS 能增强运动学习。你怀疑只是 placebo 效应。设计一个实验区分真实效应和安慰剂效应。

### 方法学评审

**Q5**：你读到一篇论文声称"anodal tDCS over M1 显著提高运动技能学习"。但你注意到他们用了 0.5 mA、5 分钟的单次刺激，样本量 n=8。作为 reviewer，你会提出哪些方法学 concern？

---

## 📚 分级阅读清单

### 🟢 入门

| # | 阅读 | 重点 |
|---|------|------|
| 1 | Rossi et al. (2009) *Clin Neurophysiol* | TMS 安全与操作指南 — 必读 |
| 2 | [SimNIBS Tutorial](https://simnibs.github.io/simnibs/) | tDCS 电场仿真入门 |

### 🟡 核心

| # | 论文 | 主题 |
|---|------|------|
| 3 | Friston (2010) *Nat Rev Neurosci* | 自由能原理入门 |
| 4 | Adams, Shipp & Friston (2013) | Active Inference 在运动中的应用 |
| 5 | Diedrichsen et al. (2010) *Trends Cog Sci* | 小脑内部模型综述 |
| 6 | Todorov (2004) *Nat Neurosci* | OFC 详细数学推导 |

### 🔴 前沿

| # | 论文 | 主题 |
|---|------|------|
| 7 | Herzfeld et al. (2018) *Nat Neurosci* | 小脑浦肯野细胞的 error encoding |
| 8 | Celnik et al. (TMS papers) | TMS 在运动学习中的应用 |
| 9 | Kim et al. (2023) | Spontaneous Recovery 的计算模型 |

---

## 🔗 在线学习资源

| 资源 | 类型 | 说明 | 链接 |
|------|------|------|------|
| **Neurology Final** | Quizlet 闪卡 | 235+230 张神经系统概念卡 | [Quizlet Key Concepts](https://quizlet.com/1115874643/) |
| **NeuroSynth** | 数据库 | 按脑区/功能搜 fMRI 文献 | [neurosynth.org](https://neurosynth.org/) |
| **SimNIBS** | 软件 | tDCS/TMS 电场仿真 | [simnibs.github.io](https://simnibs.github.io/) |
| **MNE-Python** | 软件 | EEG/MEG 分析 | [mne.tools](https://mne.tools/) |
| **Brian2** | 软件 | 脉冲神经网络建模 | [briansimulator.org](https://briansimulator.org/) |

---

## 🔥 高分策略

### Lei 教 640（最可能）
1. **提前学 TMS/tDCS 基础知识** — 他的课围绕方法学展开
2. **课件不够 → 自己建知识体系** — 用 OneNote/Obsidian 整理每个方法的核心概念
3. **去他 lab 看一次 TMS 实验** — 动手理解远胜于纸上谈兵
4. **口音可能有障碍** — 录音 + 课后补笔记

### Buchanan 教 640
5. **理论辩论 = 核心考点** — FBS vs OFC vs Active Inference 对比必须烂熟
6. **准备你的"立场"** — 他会在课上逼你选一边并 defend

### 通用
7. **640 的 final paper = 你的第一个研究 proposal** — 研究方法学（用到 TMS? EEG? fMRI?），为博士论文做准备
8. **KINE 640 → Prelim 考试直接关联** — 这门课覆盖 Prelim method section 的核心内容

---

> 📝 **学术理论笔记**：已有详细课程笔记 → [Motor-Neuroscience-II.md](../必修课程/核心课程/Motor-Neuroscience-II.md)
> 
> 🔗 相邻课程：[KINE 606 ←](KINE606-Motor-Neuroscience-I.md) | [KINE 641 →](KINE641-Developmental.md)
