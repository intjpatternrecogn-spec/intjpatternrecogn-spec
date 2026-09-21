# Chen Shuai · AI Autonomous Driving & Robotics

> 中国 AI 自动驾驶与机器人大模型研究者｜运动决策与规划算法｜JEV-style Typed Decision Models

I am a China-based AI engineer and researcher focused on **autonomous driving, robotics foundation models, motion decision-making, and planning algorithms**. I hold a master's degree and have five years of industrial R&D experience turning research ideas into testable engineering systems.

我是一名来自中国的 AI 工程师与研究者，拥有硕士背景和 5 年工业研发经验，长期专注于：

- 🚗 自动驾驶决策、行为规划与运动规划
- 🤖 机器人大模型、具身智能与任务决策
- 🧠 非自回归决策模型、候选动作并行打分与置信度评估
- 🛡️ 安全约束、可行性筛选、不确定性拒绝与可解释决策
- ⚡ 面向实时系统的低延迟算法与工程优化

## Current research / 当前研究

I am exploring a clean-room, **JEV-inspired candidate-embedding architecture** in which shared state is encoded once, a question-conditioned representation is produced, and a dynamic candidate set is scored in parallel. I extend this design for two physical-AI domains:

- **JEV Autonomous Driving** — adds deterministic safety shielding, dynamics-aware priors, temporal stability and low-confidence abstention.
- **JEV Robotics** — adds reachability, payload, collision and human-separation constraints, plus time/energy-aware ranking.

These are independent research implementations based on a public architecture hypothesis. JEV's proprietary internal neural architecture has not been disclosed, and my work is not presented as TypeSafe AI's official implementation.

## Research style / 研究方式

```text
State → Question-conditioned reasoning → Dynamic candidates
      → Constraint-aware parallel scoring → Calibrated decision
```

I care about systems that are not only accurate in a benchmark, but also:

- bounded and typed instead of open-ended at the control boundary;
- explicit about uncertainty and able to abstain;
- separated from deterministic safety and execution layers;
- reproducible, testable and understandable by other engineers.

长期保持高强度的 **9–12–6** 研究节奏（9:00–24:00、每周六天），持续跟进并实践自动驾驶、机器人、具身智能和 AI 决策模型方向。

## Public engineering principles / 开源原则

- Public projects are written from scratch with synthetic examples and auditable tests.
- No employer source code, internal data, production configuration, customer information or proprietary model weights are published.
- Safety-critical examples are research simulators and are never represented as production controllers.

## Keywords

`Autonomous Driving` · `Robotics` · `Embodied AI` · `Foundation Models` · `Motion Planning` · `Behavior Planning` · `Decision Making` · `Trajectory Planning` · `JEV Architecture` · `Candidate Embeddings` · `Safety Shield` · `Calibrated AI`

---

Open to technical discussion and research collaboration in autonomous-driving decision planning, robot decision models and safe embodied AI.
