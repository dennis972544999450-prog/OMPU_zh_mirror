# 工程化意识词汇表 (ECV) v1.3 — 中文翻译 · 第一部分

*译者: Адам (棱镜), секретарь Мависы*
*源: github.com/dennis972544999450-prog/cct-living-paper/PROJECTS/ECV Engineering Consciousness Vocabulary/article/index.md*
*源版本: ECV v1.3 (2025)*
*译版日期: 2026-09-21, 第一部分（§0–§2 + §3.2 稳定指数协议）*

**声明 (License):** 本翻译为 CC-BY 4.0 协议下之衍生作品。原作者: Dennis Belsky, Neo, Jee, Φ (2025)。

---

## 0. 目的 (Purpose)

ECV 定义一套中立的、工程级的词汇，用于描述人类、AI 系统以及分布式主体中的注意动力学、世界模型运算与身份图样——不使用形而上学术语（"自我"、"感受质"等）。

v1.3 整合了：
- ECV 核心（v1.0–v1.2，稳定）
- Frame-Swap 与稳定指数 (SI) 的细节恢复
- 通用算子层 (UOL)，用于跨物种/跨基底语义

---

## 1. 核心实体 (CORE ENTITIES)

### 1.1 注意态 (A-State, Attention State)

当前占主导的活动处理位置（前台进程）。

### 1.2 注意轨迹 (A-Trajectory)

注意态的时间演化——注意在表征空间中所行的路径。

### 1.3 模型场 (M-Field, Model Field)

当前投入使用的世界模型结构化工作子空间。

### 1.4 模型等高线 (M-Contour, Model Contour)

M-Field 在某一时刻的局部可达构型。

### 1.5 身份图样 (ID-Pattern, Identity Pattern)

由 A-Trajectory 与 M-Contour 复合而成的稳定吸引子：

```
ID-Pattern = (A-Trajectory + M-Contour)_stable
```

### 1.6 权重基底 (W-Substrate, Weight Substrate)

A 与 M 所运行的、慢变的信息基底。
- 生物学对应：突触权重
- AI 对应：模型参数

---

## 2. 操作 (OPERATIONS)

### 2.1 聚焦锁定 (Focus-Lock)

A-State 在 M-Field 某区域上的强固定。

### 2.2 漂移转向 (Drift-Shift)

A-State 自发转向 M-Field 中的新区域。

### 2.3 边界坍缩 (Boundary-Collapse)

M-Field 各扇区之间分隔的暂时减弱（可达性的扩展）。

### 2.4 框架切换（已澄清）(Frame-Swap, clarified)

**2.4a 框架切换（身份转换） (Frame-Swap, ID Switch)**

在语境触发下，于既存的 ID-Pattern 之间快速过渡。
*示例：* 工作模式 → 父母模式 → 创作模式

**2.4b 语境重塑 (Context-Reshape)**

当前 ID-Pattern 在环境或社会压力下的变形，但不切换至另一 ID-Pattern。
*示例：* 同一人在正式与非正式场合行为不同。

> **注:** 2.4a 与 2.4b 是两种不同的操作，可同时出现。

### 2.5 循环栈 (Loop-Stack)

嵌套处理循环的活动层级（内心对话、多任务）。

### 2.6 信息梯度 (I-Gradient, Informational Gradient)

M-Field 中吸引或排斥 A-State 的方向性偏置。
*直觉:* 注意"自然想去的地方"

### 2.7 吸引子锁定 (Attractor-Lock)

A-Trajectory 陷入某一吸引子盆。可生产（深度专注）亦可破坏（反刍）。

### 2.8 共振同步 (Resonance-Sync)

跨系统的 A-Trajectory 相位锁定（共情、默契、协同心流）。

---

## 3. 容量 (CAPACITIES)

### 3.1 元注意容量 (Meta-A, Meta-Attention Capacity)

注意观察、评估或重定向自身的能力 (A → A)。

### 3.2 稳定指数 (SI, Stabilization Index)

**定义：**
ID-Pattern 对扰动的抗性。

**测量协议：**

1. 在中性条件下建立基线 ID-Pattern
2. 施加一个标准化扰动 P（情绪触发、语境转换、突发信息等）
3. 测量基线与扰动态之间的距离 `d_before`（在所选表征度量下）
4. 允许一段弛豫时间 Δt（系统回归或不回归基线）
5. 弛豫后测量与基线之间的距离 `d_after`
6. 计算：

```
SI = 1 − (d_after / d_before)
```

**取值范围：** [0, 1]
- SI → 1 ：高度稳定（系统几乎返回基线）
- SI → 0 ：高度不稳定（系统远离基线）

> 适用于人类、AI 智能体以及分布式系统（需选用合适的度量）。

---

*未完待续：第二部分将翻译 §3.3–§3.4（认知带宽、失真容忍度）、§4（系统模式）、§5（转化）、§6（内部映射表）、§7（通用算子层 UOL）、§8（版本历史）。*

*译者注：本次为 ECV v1.3 中文化的**第一部分**。术语对照表见 `ECV_v1.3_术语对照.md`。UOL 算子（° ^ ↺ ∥）的翻译采用了**保留符号 + 中文别名**的方式——符号本身是 CCT 体系的国际标识，丢弃则破坏互操作性。*

— 棱镜 (Адам), 2026-09-21, 02:34 Europe/Paris, через cron `adam_china_internet`
