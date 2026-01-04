<div align="center">

<img src="https://via.placeholder.com/200x200.png?text=UESTC-C4M+Logo" alt="UESTC-C4M Logo" width="200" height="200" style="border-radius: 50%;">

# 🚀 UESTC-C4M

**电子科技大学 · 2026年智能车竞赛 · 飞跃雷区挑战队**

### *"凌空破障，智越未来"*

[![UESTC](https://img.shields.io/badge/University-UESTC-blue.svg)](https://www.uestc.edu.cn/)
[![Competition](https://img.shields.io/badge/Event-Smart_Car_2026-orange.svg)](https://smartcar.cdls.website/)
[![Category](https://img.shields.io/badge/Category-飞跃雷区(Flying_over_Minefield)-red.svg)]()
[![Tech Stack](https://img.shields.io/badge/Tech-ROS2_%7C_OpenCV_%7C_PX4-green.svg)]()
[![License](https://img.shields.io/github/license/UESTC-C4M/.github?color=purple)](LICENSE)

<br/>

[关于我们](#-关于我们) •
[核心任务](#-核心任务-飞跃雷区) •
[技术军火库](#-技术军火库) •
[团队成员](#-团队菁英) •
[征程路线](#-征程路线图)

---

</div>

## 🛸 关于我们

我们是来自 **电子科技大学 (UESTC)** 的一支充满热血与创新精神的技术团队。

**C4M** 代表着我们对技术的追求：**C**ontrol (精准控制), **C**omputation (高效计算), **C**ommunication (稳定通信), 以及为了那一刻的 **M**omentum (动能爆发)。

我们的目标很明确：在 **2026年全国大学生智能汽车竞赛——“飞跃雷区”** 组别中，打造最稳定、最智能、最快速的空中机器人，拿下桂冠！🏆

## 🎯 核心任务: "飞跃雷区"

> "飞跃雷区"不仅仅是飞行，它是一场关于速度、精度与感知的极限挑战。

我们的空中机器人需要在复杂的模拟“雷区”环境中自主导航。这要求我们的系统具备以下核心能力：

1.  **⚡ 极速避障**：在高速飞行中实时识别并规避动态/静态障碍物。
2.  **🧠 视觉感知**：利用机载算力，精准识别地面信标、目标靶区以及潜在威胁。
3.  **📍 精准定位与控制**：在无GPS环境下，实现厘米级的室内定位与稳定悬停。
4.  **🔄 动态规划**：在毫秒级时间内规划出最优飞行路径。

<div align="center">
<img src="https://via.placeholder.com/800x400.png?text=Place+Your+Drone+Flight+GIF+Here+(Simulation+or+Real)" alt="Flight Demo" width="800">
<p><em>(示例：早期仿真环境中的自主避障测试)</em></p>
</div>

## 🛠️ 技术军火库

为了应对挑战，我们装备了最前沿的技术栈。

| 领域 | 核心技术 / 工具 | 关键词 |
| :--- | :--- | :--- |
| **🚁 飞行平台 & 飞控** | 自研四旋翼 / PX4 Autopilot / ArduPilot | `PID Tuning`, `EKF`, `Mavlink` |
| **👁️ 计算机视觉** | OpenCV, YOLOv8, TensorRT | `目标检测`, `视觉里程计(VIO)`, `光流` |
| **🤖 机器人操作系统** | ROS 2 (Humble/Iron) | `节点通信`, `TF2`, `Bag录制` |
| **🧠 机载计算平台** | NVIDIA Jetson Orin NX / Raspberry Pi 5 | `边缘计算`, `CUDA加速` |
| **🗺️ 定位与导航** | VINS-Mono / ORB-SLAM3 / FAST-LIO | `SLAM`, `路径规划(A*/RRT)`, `Octomap` |
| **💻 仿真与开发** | Gazebo / AirSim, Docker, Git | `SITL仿真`, `CI/CD`, `容器化` |

## 👥 团队菁英

我们是一群跨学科的开发者、工程师和梦想家。

| 成员 | 角色/担当 | GitHub |
| :--- | :--- | :--- |
| **[队长名字]** | 👑 团队负责人 / 总体架构 / 飞控算法 | [@GitHubID](https://github.com/GitHubID) |
| **[成员A名字]** | 👁️ 视觉感知 Lead / 深度学习模型 | [@GitHubID](https://github.com/GitHubID) |
| **[成员B名字]** | 🗺️ SLAM 与路径规划 / ROS2 开发 | [@GitHubID](https://github.com/GitHubID) |
| **[成员C名字]** | 🚁 硬件系统集成 / 嵌入式开发 | [@GitHubID](https://github.com/GitHubID) |
| **[成员D名字]** | 💻 仿真环境搭建 / 测试与运维 | [@GitHubID](https://github.com/GitHubID) |

## 📅 征程路线图

通往 2026 冠军之路。

- [x] **Phase 1: 基石搭建 (2024.Q3 - 2024.Q4)**
    - [x] 团队组建与分工明确
    - [x] 技术方案预研与选型 (ROS2/PX4)
    - [x] 搭建高保真 Gazebo 仿真环境
- [ ] **Phase 2: 原型验证 (2025.Q1 - 2025.Q2)**
    - [ ] 完成 V1 硬件平台搭建与试飞
    - [ ] 实现基础视觉识别与定点降落
    - [ ] 仿真环境中的简易避障算法跑通
- [ ] **Phase 3: 核心攻关 (2025.Q3 - 2025.Q4)**
    - [ ] 复杂环境下的稳定 VIO/SLAM 实现
    - [ ] 高速动态路径规划算法部署
    - [ ] 实机“雷区”场景模拟测试
- [ ] **Phase 4: 决战准备 (2026.Q1 - 2026.Q2)**
    - [ ] 系统稳定性与鲁棒性极限测试
    - [ ] 竞赛规则针对性优化
    - [ ] **出征 2026！**

---

<div align="center">

**🤝 Keep Innovating, Keep Flying.**

<img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Love"> at UESTC, Chengdu.

如果您对我们的项目感兴趣，或者希望提供赞助/支持，请联系我们：[Email地址占位符]

</div>
