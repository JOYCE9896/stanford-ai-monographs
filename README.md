# Stanford AI 课程

斯坦福大学 2025-2026 学年六门 AI 课程的笔记整理：
* CS329A: Self-Improving AI Agents
* MS&E 435: Economics of the AI Supercycle
* CS336: Language Modeling from Scratch
* CS25: Transformers United V6
* EE392B: Industrial AI
* CS283: Governing Artificial Intelligence

网页基于 Tufte CSS 排版，正文对涉及的模型训练方法、推理验证机制与评测基准补充了背景说明。

[![GitHub Pages](https://img.shields.io/badge/Reading-GitHub%20Pages-8b261e?style=flat-square&logo=github)](https://joyce9896.github.io/stanford-ai-monographs/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-204e79?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Stanford CS329A](https://img.shields.io/badge/Stanford-CS329A-b83a2d?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
[![Stanford MS&E 435](https://img.shields.io/badge/Stanford-MS%26E%20435-1a5276?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)
[![Stanford CS336](https://img.shields.io/badge/Stanford-CS336-6b3fa0?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/)
[![Stanford CS25](https://img.shields.io/badge/Stanford-CS25-2f6f4f?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/)
[![Stanford EE392B](https://img.shields.io/badge/Stanford-EE392B-a3691a?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/)
[![Stanford CS283](https://img.shields.io/badge/Stanford-CS283-3b3b3b?style=flat-square)](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/)

---

## 在线阅读

浏览器直接访问：

* [课程总入口](https://joyce9896.github.io/stanford-ai-monographs/)
* [Stanford CS329A: Self-Improving AI Agents（10 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
* [Stanford MS&E 435: Economics of the AI Supercycle（9 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)
* [Stanford CS336: Language Modeling from Scratch（10 讲笔记 + 特辑）](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/)
* [Stanford CS25: Transformers United V6（9 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/)
* [Stanford EE392B: Industrial AI（10 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/)
* [Stanford CS283: Governing Artificial Intelligence（10 讲笔记）](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/)

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

## Stanford CS336: Language Modeling from Scratch

课程以"从零构建"为教学法核心，要求学生亲手实现分词器、Transformer、分布式训练与对齐算法的完整技术栈。

* 主讲：Percy Liang、Tatsunori Hashimoto（斯坦福大学计算机系）

| 讲次 | 标题 | 主要内容 |
| :--- | :--- | :--- |
| 01 | [Overview与Tokenization的第一性原理](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/01_Overview与Tokenization的第一性原理.html) | BPE 合并机制、字节级分词消灭未登录词、词表规模权衡 |
| 02 | [PyTorch资源核算与显存精算](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/02_PyTorch资源核算与显存精算.html) | 6ND 算力法则、混合精度显存分解、Roofline 模型与 MFU |
| 03 | [模型架构与超参数选择的工程直觉](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/03_模型架构与超参数选择的工程直觉.html) | Pre-Norm、RMSNorm、SwiGLU、RoPE、GQA 的设计权衡 |
| 04 | [混合专家模型MoE的路由与负载均衡](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/04_混合专家模型MoE的路由与负载均衡.html) | Top-k 门控路由、辅助负载均衡损失、专家容量与 All-to-All 通信 |
| 05 | [GPU计算范式与Triton底层内核优化](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/05_GPU计算范式与Triton底层内核优化.html) | SRAM/HBM 内存层级、FlashAttention 在线 Softmax、Triton 块级编程 |
| 06 | [并行训练策略的全景解构](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/06_并行训练策略的全景解构.html) | 数据/张量/流水线并行、FSDP 显存分片、3D 并行组合拓扑 |
| 07 | [ScalingLaws与算力最优配比预测](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/07_ScalingLaws与算力最优配比预测.html) | Chinchilla 幂律公式、IsoFLOP 曲线、训练-推理全生命周期成本 |
| 08 | [推理系统与模型评估方法论](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/08_推理系统与模型评估方法论.html) | KV Cache、连续批处理、PagedAttention、基准测试污染 |
| 09 | [预训练数据工程的全流程剖析](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/09_预训练数据工程的全流程剖析.html) | 网页抓取清洗、MinHash LSH 近似去重、数据配比与评估集去污染 |
| 10 | [对齐三部曲：SFT、RLHF与强化学习](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/10_对齐三部曲SFT_RLHF与强化学习.html) | SFT 模仿学习、Bradley-Terry/PPO、DPO 单阶段目标、GRPO 群体相对优化 |
| 特辑 | [业界嘉宾：从Qwen到LLaMA的开源模型体系建设者](https://joyce9896.github.io/stanford-ai-monographs/CS336-Language-Modeling-from-Scratch/11_业界嘉宾特辑.html) | 通义千问团队负责人 Junyang Lin 与 Meta AI 研究科学家 Mike Lewis 的客座讲座整理 |

---

## Stanford CS25: Transformers United V6

斯坦福长年公开对外的 Transformers 前沿研讨课，V6 主题为"从表征学习到世界模型"，Spring 2026 于 Skilling Auditorium 举行并开放 Zoom 直播。

* 组织者：Steven Feng、Karan P. Singh、Michael C. Frank、Christopher Manning

| 讲次 | 嘉宾 | 主题 |
| :--- | :--- | :--- |
| 01 | [课程组织者](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/01_Transformer架构全景与统一表征范式.html) | Transformer 架构全景与六年演进脉络 |
| 02 | [Hazel Nam & Lucas Maes（Brown）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/02_联合嵌入预测架构与世界模型.html) | 联合嵌入预测架构（JEPA）与世界模型 |
| 03 | [Albert Gu（CMU / Cartesia AI）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/03_状态空间模型与Transformer的效率博弈.html) | 状态空间模型与 Transformer 的效率博弈 |
| 04 | [Nouamane Tazi（Hugging Face）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/04_万卡集群训练与超大规模并行工程.html) | 万卡集群训练与超大规模并行工程 |
| 05 | [Shrimai Prabhumoye（Mistral AI）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/05_预训练范式的未来与效率转向.html) | 预训练范式的未来与效率转向 |
| 06 | [Andrew Lampinen（Anthropic）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/06_参数记忆与情境学习的泛化分野.html) | 参数记忆与情境学习的泛化分野 |
| 07 | [Vivek Natarajan（Google DeepMind）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/07_协作式AI智能体与科学医学发现.html) | 协作式 AI 智能体与科学医学发现 |
| 08 | [Victoria Lin（Thinking Machines）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/08_原生多模态智能与统一表征.html) | 原生多模态智能与统一表征 |
| 09 | [Charles Frye（Modal）](https://joyce9896.github.io/stanford-ai-monographs/CS25-Transformers-United/09_生产级Transformer推理服务工程.html) | 生产级 Transformer 推理服务工程 |

---

## Stanford EE392B: Industrial AI

课程聚焦制造业、军工、机器人、半导体、零售与汽车等垂直行业的 AI 落地工程实践，每讲一位业界嘉宾。

* 主讲：Daniel O'Neill、Dimitry Gorinevsky（斯坦福大学电子工程系）

| 讲次 | 嘉宾/机构 | 主题 |
| :--- | :--- | :--- |
| 01 | [Dan O'Neill（Stanford）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/01_工业AI的定义边界与第四次工业革命序章.html) | 工业 AI 的定义边界与第四次工业革命序章 |
| 02 | [Nick Landolfi（Unusual Ventures）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/02_工业AI风险投资版图与早期赛道判断.html) | 工业 AI 风险投资版图与早期赛道判断 |
| 03 | [Tyler Dillstrom（Northrop Grumman）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/03_军工级AI系统的研发部署与可靠性工程.html) | 军工级 AI 系统的研发部署与可靠性工程 |
| 04 | [Emerson Collective / Field AI](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/04_具身智能与机器人在真实场景中的落地.html) | 具身智能与机器人在真实场景中的落地 |
| 05 | [Arvind Jayaraman（KLA Tencor）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/05_半导体计量学中的AI质检革命.html) | 半导体计量学中的 AI 质检革命 |
| 06 | [Matthew Johns（Microsoft）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/06_AIOps与智能运维的自动化闭环.html) | AIOps 与智能运维的自动化闭环 |
| 07 | [An Phan（Aitomatic）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/07_半导体数字孪生与物理引导建模.html) | 半导体数字孪生与物理引导建模 |
| 08 | [David Tepper（Pay-i）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/08_AI成本治理与生成式金融科技.html) | AI 成本治理与生成式金融科技 |
| 09 | [Mohan Akelia（Walmart）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/09_零售供应链中的AI预测与优化.html) | 零售供应链中的 AI 预测与优化 |
| 10 | [Alexei Andreev（Autotech Ventures）](https://joyce9896.github.io/stanford-ai-monographs/EE392B-Industrial-AI/10_汽车产业AI变革与底特律的再工业化.html) | 汽车产业 AI 变革与底特律的再工业化 |

---

## Stanford CS283: Governing Artificial Intelligence

跨法学院、计算机系、传播学系与政治系联合开设，系统讨论 AI 治理的法律、政策与制度设计。

* 主讲：Nathaniel Persily、Rob Reich、Anka Reuel、Sanmi Koyejo

| 讲次 | 标题 | 主要内容 |
| :--- | :--- | :--- |
| 01 | [AI转型的竞争性叙事与前沿科技治理史鉴](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/01_AI转型的竞争性叙事与前沿科技治理史鉴.html) | AI 2027 vs. 常态化技术论、核能/生物技术/互联网监管史 |
| 02 | [技术根基解构与算法公平性的度量困境](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/02_技术根基解构与算法公平性的度量困境.html) | SGD 与思维链技术基础、Kleinberg 公平性不可能定理 |
| 03 | [生成式AI操纵民主话语与隐私权的边界](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/03_生成式AI操纵民主话语与隐私权的边界.html) | 幻觉与提示注入、训练数据隐私与更正权困境 |
| 04 | [欧盟AI法案与美国算力门槛之治理分野](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/04_欧盟AI法案与美国算力门槛之治理分野.html) | EU AI Act 风险分级、加州 SB 1047/SB 53 算力阈值 |
| 05 | [全球治理版图的多元路径与AI经济学](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/05_全球治理版图的多元路径与AI经济学.html) | 中国/印度/非洲治理路径、劳动力市场与反垄断 |
| 06 | [算力基础设施能耗博弈与国家安全地缘政治](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/06_算力基础设施能耗博弈与国家安全地缘政治.html) | 数据中心能耗、硬件可核查机制、芯片出口管制 |
| 07 | [企业内部治理机制与评估基准的技术陷阱](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/07_企业内部治理机制与评估基准的技术陷阱.html) | 模型卡片、负责任扩展政策、基准测试污染与构念效度 |
| 08 | [数据透明度悖论与生成式AI版权战争](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/08_数据透明度悖论与生成式AI版权战争.html) | 开放权重双重效应、OpenAI诉纽约时报案 |
| 09 | [智能体自主性风险与人机关系的哲学追问](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/09_智能体自主性风险与人机关系的哲学追问.html) | 多智能体涌现风险、图灵测试的当代回响 |
| 10 | [反垄断诽谤责任认定与AI未来的终极叙事](https://joyce9896.github.io/stanford-ai-monographs/CS283-Governing-AI/10_反垄断诽谤责任认定与AI未来的终极叙事.html) | AI 市场权力的反垄断应对、课程终极叙事总结 |

---

## 排版原则

* **字体一致**：英文全站统一使用 Source Serif 4，中文全站统一使用思源宋体（Noto Serif SC）。代码块与正文保持完全一致的字体族，不再使用第三方等宽字体。
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
