# Stanford AI Monographs

斯坦福前沿人工智能课程（2025-2026 学年）的研读笔记与技术注释文集。包含计算机系与管理科学系的两门专题课程，所有内容整理为单文件网页，排版基于 Tufte CSS，并补充了算法背景与基准测试的历史脉络。

[![GitHub Pages](https://img.shields.io/badge/Live%20Reading-GitHub%20Pages-8b261e?style=flat-square&logo=github)](https://joyce9896.github.io/stanford-ai-monographs/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-204e79?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Stanford CS329A](https://img.shields.io/badge/Stanford-CS329A%20(Agentic%20AI)-b83a2d?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
[![Stanford MS&E 435](https://img.shields.io/badge/Stanford-MS%26E%20435%20(AI%20Economics)-1a5276?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)

---

## 在线阅读

直接通过浏览器打开，免安装：

* [文集总入口（Portal Page）](https://joyce9896.github.io/stanford-ai-monographs/)
* [Stanford CS329A: 自演进 AI Agent 研讨（共 10 讲）](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
* [Stanford MS&E 435: AI 超级周期的经济学（共 9 讲）](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)

---

## 专题一：Stanford CS329A（Self-Improving AI Agents）

课程关注大语言模型如何通过强化学习、代码环境反馈和搜索算法实现推理能力的自我演进。

* 主讲：Aakanksha Chowdhery（Google PaLM 共同第一作者）、Azalia Mirhoseini（AlphaChip 第一作者，斯坦福助理教授）
* 特邀分享：Denny Zhou（Google DeepMind）、Thang Luong（AlphaProof 团队）等

| 讲次 | 标题 | 核心内容 |
| :--- | :--- | :--- |
| 01 | [自演进闭环与静态模型终结](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/01_自演进闭环与静态模型终结.html) | 预训练数据存量边界、自回归序列的累积误差、预训练与后训练的分工 |
| 02 | [测试期算力缩放与反复采样极限](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/02_测试期算力缩放与反复采样极限.html) | 测试期推理算力分配、Pass@k 采样规律、多数投票在逻辑长尾题中的边界 |
| 03 | [鲁棒验证机制与生成验证剪刀差](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/03_鲁棒验证机制与生成验证剪刀差.html) | 结果监督（ORM）与过程监督（PRM）的优缺点、弱模型验证强模型的可行性 |
| 04 | [工具代码反馈与执行强化学习](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/04_工具代码反馈与执行强化学习.html) | 代码执行沙盒作为强化学习奖励源（RLEF）、Anthropic 的 Constitutional AI 与 RLAIF 训练流程 |
| 05 | [多步规划树搜索与自适应分枝](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/05_多步规划树搜索与自适应分枝.html) | 线性思维链的容错短板、蒙特卡洛树搜索（MCTS）在推理任务中的应用、SPRINT 并行探索 |
| 06 | [训练期算力扩展与强化学习熵崩溃](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/06_训练期算力扩展与强化学习熵崩溃.html) | DeepSeek GRPO 算法省去 Critic 网络的显存机制、强化学习训练中的策略熵衰减与剪裁策略 |
| 07 | [开放式演进与AI科学家全自动研发](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/07_开放式演进与AI科学家全自动研发.html) | The AI Scientist 自动化实验流程、代码变异演进算法、自动化科研的边界与安全防范 |
| 08 | [深度研究Agent与搜索增强推理](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/08_深度研究Agent与搜索增强推理.html) | AlphaCode 2 的聚类过滤策略、思维链内生搜索、GAIA 基准对真实办公任务的评估方式 |
| 09 | [长周期任务评估与真实经济价值陷阱](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/09_长周期任务评估与真实经济价值陷阱.html) | 常见基准测试脉络（MMLU、GSM8K、SWE-bench、GAIA、GDPVal）、LLM-as-a-Judge 的评估偏差 |
| 10 | [未来研究范式与顶尖嘉宾思想总汇](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/10_未来研究范式与顶尖嘉宾思想总汇.html) | Denny Zhou 关于思维链本质的探讨、Lean 4 形式化数学验证、长上下文下的 KV Cache 显存优化 |
| 特辑 | [硅谷嘉宾访谈精选](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/podcasts_guest_interviews.html) | 收录 No Priors、TWIML AI、The MAD Podcast 等 12 场针对主讲导师与研究者的深度访谈 |

---

## 专题二：Stanford MS&E 435（Economics of the AI Supercycle）

课程探讨生成式 AI 的资本支出、商业模式、算力基础设施与传统工业约束。

* 主讲：Apoorv Agrawal（Altimeter Capital 合伙人）
* 讨论嘉宾来自 Crusoe、Databricks、OpenAI 基础架构团队、Vercel 等

| 讲次 | 标题 | 核心内容 |
| :--- | :--- | :--- |
| 01 | [生成式AI的经济学本质与资本陷阱](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/01_生成式AI的经济学本质与资本陷阱.html) | 生成式 AI 的可变推理成本、基础设施硬件开支与应用层利润分配 |
| 02 | [GPU经济学与智力边际成本归零](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/02_GPU经济学与智力边际成本归零.html) | 硬件折旧周期、SRAM 与 HBM 显存带宽限制、单位 Token 推理成本走势 |
| 03 | [吉瓦级AI工厂与热力学重工业之壁](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/03_吉瓦级AI工厂与热力学重工业之壁.html) | 吉瓦级数据中心建设、电网接入排期、高压变压器供应链瓶颈与现场能源开发 |
| 04 | [企业级AI与软件的生产率J曲线](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/04_企业级AI与软件的生产率J曲线.html) | 企业软件引入新技术时的生产率 J 曲线、私有数据权限管理与清洗成本 |
| 05 | [前沿算力战争与地缘半导体博弈](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/05_前沿算力战争与地缘半导体博弈.html) | 先进制程晶圆产能分配、CoWoS 封装限制、推理模型对硬件架构需求的变化 |
| 06 | [数据之墙与后训练可验证强化学习](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/06_数据之墙与后训练可验证强化学习.html) | 高质量自然语言语料存量、合成数据生成方法、代码与数学作为可自动验证信号 |
| 07 | [VibeCoding与软件的可塑性革命](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/07_VibeCoding与软件的可塑性革命.html) | 意图驱动编程对传统研发流程的改变、长尾定制软件的开发成本变化 |
| 08 | [十亿倍推理爆发与多模型世界的反垄断](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/08_十亿倍推理爆发与多模型世界的反垄断.html) | 推理 Token 需求规模测算、批处理与交互式调用的差异、独立云服务商的生态定位 |
| 09 | [生命科学双循环与生物制药范式跃迁](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/09_生命科学双循环与生物制药范式跃迁.html) | 结构生物学模型（AlphaFold、Chai-1）、干实验室筛选与湿实验室验证的闭环循环 |
| 特辑 | [产业与投资人访谈精选](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/podcasts_guest_interviews.html) | 收录 Acquired、Dwarkesh Podcast、BG2 等 15 场围绕数据中心、能源与商业落地的讨论 |

---

## 排版与阅读支持

* **字体搭配**：英文采用 Google Fonts 的 Newsreader，中文搭配思源宋体（Noto Serif SC），代码块采用 JetBrains Mono。
* **字号分级**：全站 CSS 控制为 3 级尺寸（大号 1.55rem 用于各级标题，正文 1.10rem，小号 0.88rem 用于边注、标签和表头），保持视线连贯。
* **数学公式**：通过 KaTeX 引擎渲染公式与数学推导，并为移动端及离线查看优化了文本格式。
* **概念注释**：正文中对 PRM、RLAIF、GRPO 以及常见评测基准等技术名词增加了背景说明，便于对照阅读。

---

## 本地查阅

网页为纯静态文件，克隆后直接打开即可：

```bash
git clone https://github.com/JOYCE9896/stanford-ai-monographs.git
cd stanford-ai-monographs

# 浏览器打开首页
open index.html
```

---

## 声明与致谢

1. 本项目为个人学术学习笔记整理，遵循 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可（署名、非商业性使用、相同方式共享）。
2. 课程大纲、课件及讲座原始内容著作权归斯坦福大学、授课教师及演讲嘉宾所有。
