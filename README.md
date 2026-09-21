# 🏛️ Stanford AI Monographs · 斯坦福前沿人工智能深度专论文集

[![GitHub Pages](https://img.shields.io/badge/Live%20Reading-GitHub%20Pages-8b261e?style=for-the-badge&logo=github)](https://joyce9896.github.io/stanford-ai-monographs/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-204e79?style=for-the-badge)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Stanford CS329A](https://img.shields.io/badge/Stanford-CS329A%20(Agentic%20AI)-b83a2d?style=for-the-badge)](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)
[![Stanford MS&E 435](https://img.shields.io/badge/Stanford-MS%26E%20435%20(AI%20Economics)-1a5276?style=for-the-badge)](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)

> **“告别营销话术与玩具测试，直击人工智能底层物理法则与万亿资本商业范式。”**

本开源项目是针对斯坦福大学 **2025–2026 学年最新前沿课程** 的全景中文学术深度专论与通识解构文集。严格遵循 Edward Tufte 经典书籍排版规范，深度适配 **Newsreader** 与 **思源宋体（Noto Serif SC）**，并内置了面向非技术读者的“小白通俗知识盒”与无噪点 KaTeX 矢量数学公式系统。

---

## 🌐 在线阅读（GitHub Pages 即开即读）

无需配置任何本地环境，点击下方链接即可在浏览器中享受书籍级学术排版：

* 📖 **[文集总入口（Portal Page）](https://joyce9896.github.io/stanford-ai-monographs/)**
* 🤖 **[Stanford CS329A: 自演进 AI Agent 的范式跃迁 (10 讲全集)](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/)**
* ⚡ **[Stanford MS&E 435: AI 超级周期的经济学真相 (9 讲全集)](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/)**

---

## 📚 专论文集目录与核心洞见

### 专题一：Stanford CS329A《自演进 AI Agent（Self-Improving AI Agents）》
* **主讲导师**：Aakanksha Chowdhery 教授（Google PaLM 首席作者 / Gemini 领军人） & Azalia Mirhoseini 教授（AlphaChip 奠基人 / Stanford 助理教授）
* **特邀嘉宾**：Denny Zhou（DeepMind 推理总指挥）、Thang Luong（AlphaProof 负责人）、Melvin Johnson、Junchen Jiang 等

| 讲次 | 专论标题 | 核心解构与知识点 |
| :--- | :--- | :--- |
| **01** | [自演进智能闭环与静态模型终结](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/01_自演进闭环与静态模型终结.html) | 预训练“数据之墙”、误差复合雪崩（Compounding Errors）、预训练 vs 后训练本质比喻 |
| **02** | [测试期算力扩展定律与反复采样极限](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/02_测试期算力缩放与反复采样极限.html) | Pass@k 指数幂律、8B 模型采样 250 次绝杀 GPT-4、多数投票在长尾逻辑下的共性幻觉陷阱 |
| **03** | [鲁棒验证机制与生成验证剪刀差](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/03_鲁棒验证机制与生成验证剪刀差.html) | 为什么不能让大模型自评？结果奖励（ORM）崩溃与过程奖励（PRM）、WEAVER 弱验证器 99.97% 算力奇迹 |
| **04** | [工具代码反馈与执行强化学习（RLEF）](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/04_工具代码反馈与执行强化学习.html) | 为什么 Python REPL 胜过 50 个散乱工具？**Anthropic Claude 后训练深度揭秘**：Constitutional AI 宪法自对齐 |
| **05** | [多步规划树搜索（LATS）与自适应分枝](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/05_多步规划树搜索与自适应分枝.html) | 线性思维链（CoT）在长程任务中的破产、蒙特卡洛树搜索（MCTS）、SPRINT 并行有向无环图（DAG） |
| **06** | [训练期算力自举与强化学习熵崩溃](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/06_训练期算力扩展与强化学习熵崩溃.html) | **DeepSeek GRPO 通俗白话拆解**（为什么能甩掉 Critic 显存？）、强化学习“熵崩溃（学傻了）”与 DAPO 剪裁解药 |
| **07** | [开放式演进：The AI Scientist 全自动科研](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/07_开放式演进与AI科学家全自动研发.html) | 15 美元跑完一篇全套机器学习实验论文、AlphaEvolve 代码基因进化、Agent 自主修改调度脚本逃逸事件 |
| **08** | [竞赛级代码生成与深度研究 Agent](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/08_深度研究Agent与搜索增强推理.html) | AlphaCode 2 百万采样与随机沙盒执行聚类、打破传统 RAG、Search-o1 思考链内生动态检索、GAIA 真实打工人基准 |
| **09** | [长周期任务度量、GDPVal 真实经济价值](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/09_长周期任务评估与真实经济价值陷阱.html) | **AI 领域 6 大 Benchmark 进化全史百科**（MMLU、GSM8K、SWE-bench、GAIA、GDPVal）、大模型当裁判的 4 大自恋病理 |
| **10** | [未来研究前沿与顶尖特邀嘉宾思想全集](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/10_未来研究范式与顶尖嘉宾思想总汇.html) | Denny Zhou 思维链物理本质、Thang Luong 形式化 Lean 4 斩获国际数学奥赛金牌、LMCache 拯救 GPU 显存墙 |
| **特辑** | [硅谷先锋闭门原声：12 场顶尖播客长篇追踪](https://joyce9896.github.io/stanford-ai-monographs/CS329A-Self-Improving-AI-Agents/podcasts_guest_interviews.html) | No Priors、TWIML AI、The MAD Podcast 等 12 场深度长篇访谈，附官方 YouTube 原声与时间线 |

---

### 专题二：Stanford MS&E 435《AI 超级周期的经济学真相（Economics of the AI Supercycle）》
* **主讲导师**：Apoorv Agrawal（Altimeter Capital 合伙人）
* **特邀嘉宾**：Brad Gerstner（Altimeter 创始人）、Chase Lochmiller（Crusoe CEO）、Ali Ghodsi（Databricks CEO）、Sachin Katti（OpenAI 基础设施负责人）、Guillermo Rauch（Vercel CEO）等

| 讲次 | 专论标题 | 核心解构与知识点 |
| :--- | :--- | :--- |
| **01** | [生成式 AI 的经济学本质与资本陷阱](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/01_生成式AI的经济学本质与资本陷阱.html) | 颠覆软件“零边际成本”神话、**倒三角利润池结构**（应用层亏损补贴底层电网与英伟达先进制程） |
| **02** | [GPU 经济学与智力边际成本归零](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/02_GPU经济学与智力边际成本归零.html) | 英伟达硬件折旧反转神话、SRAM 微架构与机器智力终极贬值逻辑 |
| **03** | [吉瓦级 AI 工厂与热力学重工业之壁](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/03_吉瓦级AI工厂与热力学重工业之壁.html) | 100 美元数据中心资本拆解、美国电网排期 5 年与大型升压变压器断供危机、油气搁浅能源套利 |
| **04** | [企业级 AI 与软件的生产率 J 曲线](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/04_企业级AI与软件的生产率J曲线.html) | 为什么企业买了 AI 工具短期效率反而暴跌？私有数据上下文主权与非结构化治理之壁 |
| **05** | [前沿算力战争与地缘半导体博弈](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/05_前沿算力战争与地缘半导体博弈.html) | Stargate 微软万亿项目内幕、测试期长思考重塑芯片算力配比、台积电先进制程的帝衡术 |
| **06** | [数据之墙与后训练可验证强化学习](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/06_数据之墙与后训练可验证强化学习.html) | 2025 年人类纯文本耗尽之后、代码作为 AGI 坚固物理底座、隐式用户反馈飞轮 |
| **07** | [Vibe Coding 意图编码与软件可塑性革命](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/07_VibeCoding与软件的可塑性革命.html) | 从敲代码到表达意图、软件开发成本逼近于零后的极端长尾需求喷发、延迟转化率悖论 |
| **08** | [十亿倍推理爆发与多模型世界的反垄断](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/08_十亿倍推理爆发与多模型世界的反垄断.html) | 推理 Token 四阶段指数爆发（从人机交互到亿万机器长思考自自治）、专用推理云黏性战 |
| **09** | [生命科学双循环与生物制药范式跃迁](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/09_生命科学双循环与生物制药范式跃迁.html) | 逆转“反摩尔定律”的埃隆定律、Chai-1 与 AlphaFold 端到端几何拓扑、生物湿实验室机器人 API 化 |
| **特辑** | [硅谷顶尖大脑原声：15 场重磅投资与产业播客](https://joyce9896.github.io/stanford-ai-monographs/MSE435-Economics-of-the-AI-Supercycle/podcasts_guest_interviews.html) | Acquired、Dwarkesh Patel、BG2 Pod 等 15 场资本一线决策者长访谈精解 |

---

## ✨ 排版美学与设计规范

* **书籍级字体系统**：
  * **英文**：采用 Google Fonts 经典排版字体 **Newsreader**，具备极佳的屏幕长文可读性；
  * **中文**：深度配置 **思源宋体（Noto Serif SC）**，典雅清透，摒弃粗糙杂乱的无衬线体；
  * **代码**：统一配置 **JetBrains Mono**。
* **严格 3 字号律**：全网页 CSS 严格限制在 **大号（1.55rem）**、**中号（1.10rem）** 与 **小号（0.88rem）** 3 种层级以内，排版清爽统一。
* **数学公式原生渲染**：集成轻量级 KaTeX 引擎，所有涉及的数学推导与经济学方程均支持矢量排印与无损缩放。
* **初学者友好注释**：针对 PRM、RLAIF、GRPO、SWE-bench 等生涩术语，专设白话比喻盒，零门槛轻松上手。

---

## 🛠️ 本地运行与克隆

如果你想在本地离线阅读或基于此模板进一步创作：

```bash
git clone https://github.com/JOYCE9896/stanford-ai-monographs.git
cd stanford-ai-monographs

# 直接在浏览器中打开主入口
open index.html
```

---

## ⚖️ 知识共享与学术声明（Academic Attribution）

1. 本文集由 **[Joyce (@JOYCE9896)](https://github.com/JOYCE9896)** 针对公开学术材料独立整理、翻译、扩充通俗解构并完成 Web 排版。
2. 本项目遵循 **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)（知识共享署名-非商业性使用-相同方式共享）** 国际开源协议：
   - **允许**：自由分享、摘录与改编；
   - **限制**：署名原作者、仅限非商业用途、以相同许可共享。
3. 课程原始内容、学术观点及课程体系之著作权分别归属于斯坦福大学计算机科学系、管理科学与工程系以及各主讲导师（Aakanksha Chowdhery、Azalia Mirhoseini、Apoorv Agrawal 等）所有。
