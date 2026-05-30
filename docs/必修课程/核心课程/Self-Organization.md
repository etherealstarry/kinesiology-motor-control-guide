# KINE 642: Self Organization in Motor Neuroscience

**课程代码**: KINE 642  
**学分**: 3 credit hours  
**课程性质**: Motor Neuroscience 高级选修  

---

## 📖 课程简介

KINE 642 从**自组织理论**（Self-Organization）的视角理解运动控制，强调运动系统如何通过非线性动力学涌现出协调模式。

本课程涵盖：
- 动态系统理论（Dynamic Systems Theory）
- 吸引子（Attractor）与稳定性
- 涨落（Fluctuation）与临界性（Criticality）
- 约束导向方法（Constraints-Led Approach）
- 复杂系统与混沌理论在运动中的应用

---

## 🎯 学习目标

1. **解释**运动协调如何通过自组织涌现
2. **应用**动态系统理论分析运动模式转变
3. **设计**基于约束导向的实验范式
4. **批判性评价**传统运动控制理论与自组织理论的差异
5. **建模**简单的非线性运动系统

---

## 📚 推荐教材与论文

| 类型 | 名称 | 说明 |
|------|------|------|
| 教材 | *Dynamics of Coordinated Action* (Kelso, 1995) | 动态系统理论经典 |
| 教材 | *Self-Organization and Coordinating Funtions* (Turvey, 1990) | 基础论文集 |
| 论文 | Kelso, J. A. S. (1995). "Dynamic patterns..." | 核心文献 |
| 论文 | Thelen, E. & Smith, L. (1994). "A Dynamic Systems Approach..." | 发展视角 |
| 工具 | *Nonlinear Dynamics in Human Behavior* | 计算方法 |

---

## 🧑‍🏫 相关教授（TAMU KNSM）

| 教授 | 研究方向 | 个人主页 |
|------|------|------|
| 待补充 | 动态系统 / 运动协调 | 入学后补充 |

---

## 📝 学习建议

### 课前准备
- 复习非线性动力学基础（相空间、吸引子、分岔）
- 了解 Haken-Kelso-Bunz (HKB) 模型

### 课后任务
- **复现 HKB 实验**的数据分析（用 Python）
- **建模练习**：用 Python 模拟简单的耦合振子系统
- **阅读**：Kelso 的经典论文（每两周 1 篇）

### Python 示例代码（耦合振子）
```python
import numpy as np
import matplotlib.pyplot as plt

# 简化的 HKB 模型仿真
def hkb_model(phi, omega, k, dt=0.01, steps=10000):
    trajectory = [phi]
    for _ in range(steps):
        dphi = omega + k * np.sin(phi)
        phi = phi + dphi * dt
        trajectory.append(phi)
    return np.array(trajectory)

# 仿真相对相位轨迹
phi0 = 0.1  # 初始相对相位
traj = hkb_model(phi0, omega=0.5, k=-1.0)
plt.plot(traj[:500])
plt.title("HKB Model: Relative Phase Trajectory")
plt.show()
```

---

## 🔗 相关资源

- [International Society for Motor Control](https://www.is-mc.org/)
- [North American Society for the Psychology of Sport and Physical Activity (NASPSPA)](https://www.naspspa.com/)

---

*本页面由 EtherealStarry 维护，欢迎通过 GitHub PR 贡献内容。*
