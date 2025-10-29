# 光轮智能 Lightwheel AI
## 仿真强化学习研发工程师
### Simulation RL Engineer
工作地点：上海 / 北京

职位类型：全职 / Full-time

职位职责 / Responsibilities
- 设计、开发并优化机器人仿真与强化学习平台，支撑 VLA（Vision-Language-Action）等多模态智能体训练；
- 架构和维护多模态大模型（VLM/VLA）训练的分布式RL finetune训练基础设施，支持多机多卡训练和高效数据流；
- 负责 teleoperation 数据采集、replay pipeline、场景与任务构建等核心系统模块；
- 推动训练平台的“产品化 + 开源”，打造对外友好的代码结构、配置接口和使用文档, 参与社区维护与推广，提升技术影响力
任职要求 / Requirements
- 扎实的软件工程背景，熟练使用 Python 和 C++，有模块化设计、代码质量管理、性能优化等工程实践经验；
- 具备以下两类背景之一：
  - 机器人仿真经验：熟悉 IsaacSim / IsaacGym / MuJoCo / Sapien / Genesis 等平台中的一项或多项；
  - 自动驾驶仿真经验：熟悉 自研平台 / CARLA / LGSVL / AirSim ，有仿真平台开发、任务管理、sensor pipeline 构建等经验；
- 熟悉强化学习训练流程，了解 PPO / SAC / GRPO 等算法，具备训练环境调试经验；
- 熟悉 teleop 数据接入与 replay 机制；
- 熟悉分布式训练基础设施（如多机多卡训练、数据调度、显存优化）者优先；
- 加分项：
  - 有 Roboverse，RoboCasa、Genesis、Warp 等具身仿真平台开发或调试经验；
  - 主导或核心参与过开源项目，有 GitHub 上的工程贡献或框架推广经验；
  - 拥有“开源驱动产品”的意识，能独立开发可重用、易维护、易推广的组件或工具链。

---
### Sim2Real 机器人算法工程师
Sim2Real Robotic Algrithm Engineer

工作地点：上海 / 北京 

职位类型：全职 / Full-time

职位职责 / Responsibilities
- 构建从仿真训练到真实部署的完整 sim2real 流程，服务于 manipulation 等复杂机器人任务；
- 调优仿真资产的物理参数（质量、摩擦、接触、惯性等），确保行为在 sim/real 中对齐；
- 构建并维护 数据泛化 pipeline，支持基于遥操数据进行 manupulation 轨迹增强，提升现实泛化能力；
- 研究并解决 sim2real gap 的关键因素，包括 sensor、timing compensation、contact discrepancy 等；
- 在 Unitree G1/H1,  Franka，UR ，LeRobot，Aloha 等机器人平台上部署、调试、验证基于多模态策略的控制系统；
- 设计鲁棒性评估机制，对策略进行扰动测试与安全性评估。
任职要求 / Requirements
- 扎实的机器人控制和系统工程背景，具备真实 robot bring-up 或 control loop 调试经验；
- 熟悉仿真建模与真实调试之间的偏差来源，并具备调参与验证能力；
- 熟练掌握 sim2real pipeline 中常见技术（domain randomization, real2sim calibration, sensor latency compensation 等）；
- 熟悉 mimicgen 等trajectory augmentation原理，具备仿真或真实模仿学习数据构建经验；
- 有真实机器人部署经验者优先（Unitree G1/H1,  Franka，UR ，LeRobot，Aloha等）；
- 加分项：
  - 有完整的 sim2real 项目经验，能覆盖从仿真构建 → 模型训练 → 现实验证的全链条；
  - 熟悉 Mojoco / IsaacSim / Genesis 平台及其物理参数调优工具；
  - 熟悉视觉/语言控制策略的真实部署方法，或具备模仿学习、多模态行为模型部署经验。