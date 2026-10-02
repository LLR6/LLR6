# 公开项目推荐记录

更新：2026-10-02

| 渠道 | 覆盖 | 状态 | 链接 |
|---|---|---|---|
| HelloGitHub | LR-Agent | 投稿已发布，等待审核 | https://github.com/521xueweihan/HelloGitHub/issues/3826 |
| GitHubDaily | 全部 11 个公开仓库（包括 2 个索引入口） | 目录式自荐已发布，等待审核 | https://github.com/GitHubDaily/GitHubDaily/issues/1134 |

## 已纳入的公开仓库

- [LR-Agent](https://github.com/LLR6/LR-agent)：隔离候选补丁、重放原测试，并在连续仓库维护场景中记录补丁生存和维护成本。研究原型，完整运行需要兼容模型接口。
- [Android CI Doctor](https://github.com/LLR6/lr-android-ci-doctor)：离线分析 Android / Gradle / CI 日志，输出规则、原行号、去敏证据和排查建议；不依赖模型 API。
- [CTF Tracebook](https://github.com/LLR6/lr-ctf-tracebook)：把已有纯文本终端记录整理为带源行号和哈希的 Markdown / JSON 复盘草稿，默认遮盖常见敏感字段，不自动编造解题推理。
- [NightWatch](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building)：本地安全事件关联与可解释检测引擎，关注认证序列、端口高扇出、周期连接和 DNS 信号，支持 Suricata / Zeek 日志适配。
- [Detection Threshold Lab](https://github.com/LLR6/lr-detection-lab)：用固定种子的带标签合成时间序列扫描周期检测阈值，比较误报、漏报、Precision / Recall，并保留逐组证据。
- [Detector Resilience Lab](https://github.com/LLR6/LR-Detector-Resilience-Lab)：在数值特征 CSV 上运行透明分类器与特征漂移实验，比较多个阈值和漂移强度下的退化；不处理可执行文件。
- [LR-SOC-Copilot](https://github.com/LLR6/LR-SOC-Copilot)：按实体和时间关联 JSONL 告警，检索本地 Runbook，输出带源文件行号的案件摘要；当前检索为词频余弦相似度，不宣称 LLM 自动调查。
- [LR-PayloadLab](https://github.com/LLR6/LR-PayloadLab)：用 JSON Manifest 声明无害端点遥测实验，检查动作、路径和资源约束，生成执行回执、哈希和回滚记录。
- [LR-Tablet](https://github.com/LLR6/LR-Tablet)：面向 Android 平板的本地优先阅读训练工具，双栏阅读、批注、计时、复盘、多格式导入与 APK 构建；题目导入应使用有权使用的资料。
- [LR Lab 综合实验仓库](https://github.com/LLR6/-)：公开工程实验与项目索引，包含 LR-Sentinel、LR-RepoGuard 和静态个人站点等子目录。
- [LLR6 主页仓库](https://github.com/LLR6/LLR6)：作品导航与工程状态入口，便于按 Agent、安全分析、Android 和本地工具方向查找项目；属于索引而非独立应用。

投稿成功不等于收录，也不表示获得用户或 Star。推荐稿按当前公开 README 描述能力，未把合成实验或展示动画描述为现实效果。
