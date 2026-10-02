<div align="center">

<img src="assets/hero-anime.png" alt="日系动漫女孩与蓝色雪夜咖啡店" width="100%" />

# ◈ LR / LLR6

### 把好奇心写进代码，把工程结果留给复现。

`Security` · `AI Agent` · `Android` · `Automation`

[![NightWatch](https://img.shields.io/badge/SECURITY-NightWatch-80D8FF?style=for-the-badge)](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building)
[![LR Agent](https://img.shields.io/badge/AI-LR--Agent-9C8CFF?style=for-the-badge)](https://github.com/LLR6/LR-agent)
[![LR Tablet](https://img.shields.io/badge/ANDROID-LR--Tablet-FF9BC5?style=for-the-badge)](https://github.com/LLR6/LR-Tablet)

**◉ SYSTEM ONLINE　｜　build · break · learn · repeat**

</div>


## 先挑一个你现在用得上的

| 你想做什么 | 项目 | 第一眼看什么 |
| --- | --- | --- |
| 排查 Android 构建、签名或 APK 上传失败 | [Android CI Doctor](https://github.com/LLR6/lr-android-ci-doctor) | [日志实跑案例](https://github.com/LLR6/lr-android-ci-doctor/blob/main/docs/DEMO.md) |
| 把终端记录整理成 CTF 复盘草稿 | [CTF Tracebook](https://github.com/LLR6/lr-ctf-tracebook) | [输入与去敏结果](https://github.com/LLR6/lr-ctf-tracebook/blob/main/docs/DEMO.md) |
| 比较检测阈值的误报与漏报 | [Detection Threshold Lab](https://github.com/LLR6/lr-detection-lab) | [20 组合成样本实验](https://github.com/LLR6/lr-detection-lab/blob/main/docs/DEMO.md) |
| 把零散告警连成能回查的案件 | [LR-SOC-Copilot](https://github.com/LLR6/LR-SOC-Copilot) | [4 条告警如何关联](https://github.com/LLR6/LR-SOC-Copilot/blob/main/docs/DEMO.md) |
| 连续记录模拟持仓、核对下一次调仓 | [LR-AutoInvest](https://github.com/LLR6/LR-AutoInvest) | [每日工作流](https://github.com/LLR6/LR-AutoInvest/blob/main/docs/DAILY_WORKFLOW.md) |

前四个项目的案例包含源码实际运行生成的 JSON。AutoInvest 提供合成行情演示与重复同步回执。每个项目都写明输入要求、输出和限制，方便自己跑一遍核对。

## 最近在研究的两个问题

**补丁今天通过测试，仓库变化后还能活多久？**  
[LR-Agent / ChronoForge](https://github.com/LLR6/LR-agent) 将候选补丁、原测试重放和后续维护实验放在同一个工作流里。[超时配置改名案例](https://github.com/LLR6/LR-agent/blob/main/docs/CASE_CHRONOFORGE_OFFLINE.md)公开了实际测试输出；这是离线脚本驱动实验，不作为模型能力 benchmark。

**安全告警为什么触发，又为什么可能误报？**  
[NightWatch](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building) 研究事件序列与可解释检测；Threshold Lab 查看阈值代价，SOC Copilot 将告警关联理由和源行证据展开。

## 全部公开项目

| 方向 | 仓库 | 内容 |
| --- | --- | --- |
| Agent | [LR-Agent](https://github.com/LLR6/LR-agent) | 编程 Agent、候选补丁验证与长期维护实验 |
| 检测 | [NightWatch](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building) | 本地事件关联、认证序列、周期外联与 DNS 信号 |
| 检测 | [Detection Threshold Lab](https://github.com/LLR6/lr-detection-lab) | 合成样本、阈值扫描、多种子指标对照 |
| 检测 | [Detector Resilience Lab](https://github.com/LLR6/LR-Detector-Resilience-Lab) | 数值特征漂移下的检测退化实验 |
| 调查 | [LR-SOC-Copilot](https://github.com/LLR6/LR-SOC-Copilot) | 实体/时间关联、本地 Runbook 检索、证据摘要 |
| 遥测 | [LR-PayloadLab](https://github.com/LLR6/LR-PayloadLab) | 受限端点遥测实验、回执、清理与审计 |
| 开发 | [Android CI Doctor](https://github.com/LLR6/lr-android-ci-doctor) | 带源行号和上下文的构建日志排查 |
| 复盘 | [CTF Tracebook](https://github.com/LLR6/lr-ctf-tracebook) | 终端文本整理、输入哈希和去敏统计 |
| 研究 | [LR-AutoInvest](https://github.com/LLR6/LR-AutoInvest) | 连续模拟账户、行情质检、费用实验与调仓草案 |
| Android | [LR-Tablet](https://github.com/LLR6/LR-Tablet) | 平板双栏阅读、作答、批注与本地进度 |
| 综合 | [LR Lab](https://github.com/LLR6/-) | Android、本地工具与工程实验集合 |
| 导航 | [LLR6](https://github.com/LLR6/LLR6) | 当前主页与项目工程状态 |

## 关于我

平时主要折腾网络安全、AI Agent、Android 和自己会用到的小工具。喜欢把一个想法从能跑继续做到能测、能复现，也愿意把失败原因和限制一起留下来。

[工程状态](ENGINEERING_HEALTH.md) · [项目约定](PROJECT_STANDARDS.md)

欢迎到对应仓库提 Issue：安装失败、输入不兼容、误报和最小反例都很有用。收藏项目之后，也可以先跑自带样例，再用自己的数据比较。

<div align="center">

— keep building things I want to use. —

</div>
