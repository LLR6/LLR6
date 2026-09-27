<div align="center">

<img src="assets/hero-anime.png" alt="日系动漫女孩与蓝色雪夜咖啡店" width="100%" />

# ◈ LR / LLR6

### 把好奇心写进代码，把工程结果留给复现。

`安全检测` · `AI Agent` · `Android / 平板工具` · `自动化`

[![NightWatch](https://img.shields.io/badge/SECURITY-NightWatch-80D8FF?style=for-the-badge)](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building)
[![LR Agent](https://img.shields.io/badge/AI-LR--Agent-9C8CFF?style=for-the-badge)](https://github.com/LLR6/LR-agent)
[![LR Tablet](https://img.shields.io/badge/ANDROID-LR--Tablet-FF9BC5?style=for-the-badge)](https://github.com/LLR6/LR-Tablet)

**◉ SYSTEM ONLINE　｜　研究 · 构建 · 验证 · 复盘**

</div>

---

## 你好，我是 LR 👋

我从化工专业跨到计算机与网络安全。CTF 和攻防实践让我更想弄明白：一个可疑行为为什么会被发现，工具的判断依据是什么。于是我开始做安全检测、AI Agent 和自己真正会用的学习工具。这里记录代码、实验和踩过的坑；欢迎跑示例、检查思路、提 Issue。

> 我目前关注 **行为关联与证据链、Agent 的可验证性、离线优先的学习体验**。更喜欢把「为什么这样设计、哪里可能失效」写清楚。项目能力以仓库中的代码、示例和测试为准。

### 🛰️ 项目雷达

| 项目 | 一句话说明 | 从哪里开始看 |
| :--- | :--- | :--- |
| **[NightWatch](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building)** | 本地安全事件关联：登录序列、端口扇出、周期外联和 DNS 异常；告警保留触发证据 | [规则与快速运行](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building#readme) |
| **[LR-agent](https://github.com/LLR6/LR-agent)** | 可操作工作区的 Agent 实验台：任务执行、审查、隔离候选、策略消融与验证 | [架构、命令与测试](https://github.com/LLR6/LR-agent#readme) |
| **[LR-Tablet](https://github.com/LLR6/LR-Tablet)** | 面向横屏平板的英语阅读训练器：双栏阅读、导入、作答、批注与本地记录 | [体验与 Android 构建](https://github.com/LLR6/LR-Tablet#readme) |
| **[LR Lab](https://github.com/LLR6/-)** | Android、本地工具与安全实验的集合 | [项目索引](https://github.com/LLR6/-#readme) |

### 🧰 开源小工具：拿来就能跑

| 工具 | 适合在什么时候用 | 入口 |
| :--- | :--- | :--- |
| **Android CI Doctor** | Gradle / Android CI 构建失败，想从日志中快速找到带行号的签名、JDK、SDK 或产物线索 | [源码与示例](https://github.com/LLR6/lr-android-ci-doctor) |
| **CTF Tracebook** | CTF 做完后，把终端记录整理为可核查的复盘草稿，默认遮盖 flag 和常见口令 | [源码与示例](https://github.com/LLR6/lr-ctf-tracebook) |
| **Detection Threshold Lab** | 对周期外联检测阈值做可复现实验，看误报和漏报如何变化 | [源码与示例](https://github.com/LLR6/lr-detection-lab) |

这三个项目都有本地示例、测试和明确的适用边界；欢迎提出**可复现的输入与预期结果**。

### 🔬 给想看技术细节的读者

- **检测工程**：NightWatch 把事件、时间窗口和实体关联起来，同时保留告警证据；规则是待人工核验的信号，不能把高熵 DNS 或周期连接直接等同于攻击。
- **Agent 可靠性**：LR-agent 记录工具执行和验证结果；隔离候选工作区，比较不同策略的效果，并对实验噪声与启发式评分给出边界说明。
- **产品工程**：LR-Tablet 从横屏阅读出发，把训练、解析、批注和统计放进同一流程，同时提供本地运行和 Android 构建步骤。

<details>
<summary><b>⌁ 直接运行三个项目</b></summary>

NightWatch（Python 环境）：

```bash
git clone https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building.git
cd Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building
python -m venv .venv
pip install -e ".[dev]"
pytest -q
nightwatch samples/demo.jsonl --format md --out report.md
```

LR-Tablet（Web 开发环境）：

```bash
git clone https://github.com/LLR6/LR-Tablet.git
cd LR-Tablet
npm install
npm run dev
```

LR-agent 的模型配置、Docker 和测试命令请看 [项目 README](https://github.com/LLR6/LR-agent#readme)。涉及 API Key 的配置只在自己的环境中填写。

</details>

### 🌙 正在研究

`可解释告警`　`Agent 策略的反例与失效边界`　`自动化测试`　`本地优先的软件体验`

如果你是导师或研究同学，建议从 **NightWatch 的规则与证据输出** 或 **LR-agent 的实验和验证设计** 开始看。若你发现误报、复现障碍或设计漏洞，欢迎在对应仓库开 Issue 讨论。

<div align="center">

— 代码会更新，结论要能被检查。—

</div>
