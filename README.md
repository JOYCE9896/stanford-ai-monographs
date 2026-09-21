# Stanford AI 课程

斯坦福大学 2025-2026 学年两门 AI 课程的笔记整理：
* CS329A: Self-Improving AI Agents
* MS&E 435: Economics of the AI Supercycle

网页基于 Tufte CSS 排版，正文对涉及的模型训练方法、推理验证机制与评测基准补充了背景说明。

[![GitHub Pages](https://img.shields.io/badge/Reading-GitHub%20Pages-8b261e?style=flat-square&logo=github)](https://joyce9896.github.io/stanford-ai-monographs/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-204e79?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Stanford CS329A](https://img.shields.io/badge/Stanford-CS329A-b83a2d?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
[![Stanford MS&E 435](https://img.shields.io/badge/Stanford-MS%26E%20435-1a5276?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)

---

## 在线阅读

浏览器直接访问：

* [课程总入口](https://joyce9896.github.io/stanford-ai-monographs/)
* [Stanford CS329A: Self-Improving AI Agents（10 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
* [Stanford MS&E 435: Economics of the AI Supercycle（9 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)

---

## Stanford CS329A: Self-Improving AI Agents

课程主要关注 LLM 如何通过 Reinforcement Learning、环境反馈与搜索算法实现推理能力的自我演进。

* 主讲：Aakanksha Chowdhery（Google PaLM）、Azalia Mirhoseini（AlphaChip，Stanford）
* 嘉宾分享：Denny Zhou（Google DeepMind）、Thang Luong（AlphaProof）等

| 讲次 | 标题 | 主要内容 |
| :--- | :--- | :--- |
| 01 | [自演进闭环与静态模型终结](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/01_自演进闭环与静态模型终结.html) | Pre-training 数据存量边界、自回归序列的累积误差、Pre-training 与 Post-training 的分工 |
| 02 | [测试期算力缩放与反复采样极限](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/02_测试期算力缩放与反复采样极限.html) | Test-time compute 分配、Pass@k 采样规律、Majority Voting 在长尾逻辑题中的局限 |
| 03 | [鲁棒验证机制与生成验证剪刀差](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/03_鲁棒验证机制与生成验证剪刀差.html) | ORM 与 PRM 的对比、弱模型检验强模型输出的可行性 |
| 04 | [工具代码反馈与执行强化学习](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/04_工具代码反馈与执行强化学习.html) | 代码执行反馈强化学习（RLEF）、Anthropic 的 Constitutional AI 与 RLAIF 流程 |
| 05 | [多步规划树搜索与自适应分枝](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/05_多步规划树搜索与自适应分枝.html) | 线性 CoT 的容错短板、MCTS（蒙特卡洛树搜索）在推理任务中的应用、SPRINT 并行探索 |
| 06 | [训练期算力扩展与强化学习熵崩溃](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/06_训练期算力扩展与强化学习熵崩溃.html) | DeepSeek GRPO 算法省去 Critic 的显存机制、RL 训练中的策略熵衰减与剪裁策略 |
| 07 | [开放式演进与AI科学家全自动研发](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/07_开放式演进与AI科学家全自动研发.html) | The AI Scientist 自动化实验流程、代码变异演进算法、自动科研的边界与安全防范 |
| 08 | [深度研究Agent与搜索增强推理](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/08_深度研究Agent与搜索增强推理.html) | AlphaCode 2 的聚类过滤策略、CoT 内生搜索、GAIA Benchmark 对办公任务的评估方式 |
| 09 | [长周期任务评估与真实经济价值陷阱](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/09_长周期任务评估与真实经济价值陷阱.html) | 常见 Benchmark 脉络（MMLU、GSM8K、SWE-bench、GAIA、GDPVal）、LLM-as-a-Judge 评估偏差 |
| 10 | [未来研究范式与顶尖嘉宾思想总汇](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/10_未来研究范式与顶尖嘉宾思想总汇.html) | Denny Zhou 关于推理层级的讨论、Lean 4 形式化数学验证、长上下文下的 KV Cache 显存优化 |
| 特辑 | [嘉宾访谈选录](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/podcasts_guest_interviews.html) | 收录 No Priors、TWIML AI、The MAD Podcast 等 12 场针对主讲与研究者的深度访谈纪要 |

---

## Stanford MS&E 435: Economics of the AI Supercycle

课程探讨生成式 AI 的商业模式、基础设施开支与传统工业约束。

* 主讲：Apoorv Agrawal（Altimeter Capital 合伙人）
* 嘉宾来自 Crusoe、Databricks、OpenAI 基础架构团队、Vercel 等

| 讲次 | 标题 | 主要内容 |
| :--- | :--- | :--- |
| 01 | [生成式AI的经济学本质与资本陷阱](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/01_生成式AI的经济学本质与资本陷阱.html) | 可变推理成本结构、基础设施资本开支与应用层利润分配 |
| 02 | [GPU经济学与智力边际成本归零](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/02_GPU经济学与智力边际成本归零.html) | 硬件折旧周期、SRAM 与 HBM 显存带宽限制、单位 Token 推理成本走势 |
| 03 | [吉瓦级AI工厂与热力学重工业之壁](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/03_吉瓦级AI工厂与热力学重工业之壁.html) | 数据中心建设、电网排期、高压变压器供应链瓶颈与现场能源开发 |
| 04 | [企业级AI与软件的生产率J曲线](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/04_企业级AI与软件的生产率J曲线.html) | 企业软件引入新技术的生产率 J 曲线、私有数据权限管理与清洗成本 |
| 05 | [前沿算力战争与地缘半导体博弈](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/05_前沿算力战争与地缘半导体博弈.html) | 先进制程晶圆产能分配、CoWoS 封装限制、推理硬件需求变化 |
| 06 | [数据之墙与后训练可验证强化学习](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/06_数据之墙与后训练可验证强化学习.html) | 自然语言语料存量、合成数据生成方法、代码与数学作为可验证信号 |
| 07 | [VibeCoding与软件的可塑性革命](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/07_VibeCoding与软件的可塑性革命.html) | 意图驱动编程（Vibe Coding）对传统研发流程的影响、长尾小软件开发成本变化 |
| 08 | [十亿倍推理爆发与多模型世界的反垄断](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/08_十亿倍推理爆发与多模型世界的反垄断.html) | 推理 Token 需求测算、批处理与交互调用的差异、独立云服务商的生态定位 |
| 09 | [生命科学双循环与生物制药范式跃迁](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/09_生命科学双循环与生物制药范式跃迁.html) | 结构生物学模型（AlphaFold、Chai-1）、干实验室筛选与湿实验室验证的闭环 |
| 特辑 | [产业与投资人访谈选录](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/podcasts_guest_interviews.html) | 收录 Acquired、Dwarkesh Podcast、BG2 等 15 场围绕数据中心、能源与落地的访谈纪要 |

---

## 排版原则

* **字体一致**：英文全站统一使用 Newsreader，中文全站统一使用思源宋体（Noto Serif SC）。代码块与正文保持完全一致的字体族，不再使用第三方等宽字体。
* **字号精简**：全站仅保留 2 种字号（标题 1.35rem，所有正文、代码、表格、列表与页脚均为 1.05rem），杜绝字号过多带来的杂乱感。
* **排版克制**：去掉多余的色块、标签和多层装饰框，遵循简单的标题、段落与必要列表结构。
* **公式支持**：数学公式基于 KaTeX 矢量排印。

---

## 本地查阅

```bash
git clone https://github.com/JOYCE9896/stanford-ai-monographs.git
cd stanford-ai-monographs
open index.html
```

---

## 声明

1. 本项目为个人学术学习笔记整理，遵循 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可（署名、非商业性使用、相同方式共享）。
2. 课程大纲、课件及讲座原始内容著作权归斯坦福大学、授课教师及演讲嘉宾所有。
