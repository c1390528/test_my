# test_my
## 0. 科研智能体的定义与由来

### 0.1 概念溯源

"科研智能体"（英文文献中称 **Autonomous Research Agent**、**AI Scientist** 或 **Scientific Agent**）这一概念并非一蹴而就，而是经历了从工具辅助到自主代理的逐步演化：

- **2016-2020（预兆期）**：Google DeepMind 的 AlphaGo → AlphaFold 1 展示了AI在特定科学问题上的超人类能力，但这些是"专用模型"而非"通用Agent"。2017年 Zoph & Le 提出的 Neural Architecture Search (NAS) 首次让AI自主搜索模型架构，被视为最早的"自治科研"雏形 [[Zoph & Le, 2017]]。
- **2020-2023（单模型辅助期）**：AlphaFold 2 (2020) 解决蛋白质折叠、ChatGPT (2022) 开启对话式AI、GPT-4 (2023) 引入 Function Calling。此阶段AI是"被动的计算预言机"——人类定义问题，AI返回答
案。Wei et al. 将其称为 **Level 1: AI as a Computational Oracle** [[Wei et al., 2025]]。
- **2023-2024（Agent觉醒期）**：ReAct 框架 (Yao et al., 2023) 将推理与工具调用交替进行；LangChain 等Agent框架成熟；2024年8月 Sakana AI Scientist v1 首次实现端到端的ML研究自动化，被广泛>认为是第一个"AI Scientist"原型 [[Lu et al., 2024]]。
- **2024-2025（Agentic Science形成期）**：多Agent协作、长上下文推理、大规模并行探索成为可能。学术界开始用 **"Agentic Science"** 这一术语指代AI从工具向自主科研伙伴转变的新范式 [[Wei et al., 2025]]。2025年出现多篇综述论文，尝试为"科研智能体"建立统一定义。
- **2026（Nature元年）**：Co-Scientist、AI Scientist v2、Robin三篇论文先后发表于Nature，标志着科研智能体获得主流学术界的正式认可。同时，关于定义、验证标准和伦理的学术讨论进入白热化。

### 0.2 学术定义共识

截至2026年10月，学术界对科研智能体的定义尚未完全统一，但已有4篇核心综述论文形成了较为清晰的共识框架：

#### 定义一：Ding et al. (2026) — 以"决策自治"为核心

> "**An autonomous research agent is an LLM-driven system that executes at least one stage of the research lifecycle with non-trivial decision autonomy, meaning the system, not a human, selects the next action within that stage.**"

- 来源：*Autonomous Research Agents: A Survey of AI Scientists and the Verification Gap*, arXiv:2608.05179 (2026.6)
- 关键标准：系统（而非人类）选择"下一步做什么"
- 涵盖范围：单阶段Agent（如仅生成假设）到全流水线（从想法到论文）
- 排除范围：单轮Prompt（人类驱动每一步的情况）
- 核⼼贡献：提出 **L0-L5 六级自治分类**，并首次系统量化"验证缺口"（24个可运行系统中仅38%提供可复现性证据）

#### 定义二：Wei et al. (2025) — 以"Agentic Science范式"为框架

> "**Agentic Science denotes a specific stage within AI for Science evolution, in which AI operates as an autonomous scientific agent capable of formulating hypotheses, designing and executing experiments, interpreting results, and iteratively refining theories with reduced dependence on human guidance.**"

- 来源：*From AI for Science to Agentic Science: A Survey on Autonomous Scientific Discovery*, arXiv:2508.14111 (2025.8)
- 作者单位：上海AI实验室、浙江大学、复旦大学、清华大学、UBC等
- 核⼼贡献：提出 **AI for Science 四阶段演进模型**（L1计算预言机 → L2部分Agent → L3完整Agentic → L4创意协作者）
- 另贡献：**五大核心能力** 归纳（推理规划、工具集成、记忆机制、多Agent协作、优化进化）



https://aniwatchtv.to 
https://arnebrachhold.de 
https://aryion.com 
https://earnbitmoon.club 
https://freetype.org 
https://hdhub4u.mov 
https://ifconfig.io 
https://insightfulreads.net 
https://jts-blog.com
https://l-frii.com 
https://life3dblog.com
https://mangapark.net 
https://mangareader.to 
https://manhuaus.com 
https://myupchar.com 
https://nakheelteam.cc 
https://onlar.az 
https://pdfdrive.com 
https://prodevreal.com 
https://sflix.to 
https://suksesbogil.com 
https://surahquran.com 
https://voz.vn 
https://xbanxia.com 


- name: aniwatchtv
  host: aniwatchtv.to
  url: https://aniwatchtv.to
  sub_urls:
  - https://aniwatchtv.to
- name: arnebrachhold
  host: arnebrachhold.de
  url: https://arnebrachhold.de
  sub_urls:
  - https://arnebrachhold.de
- name: aryion
  host: aryion.com
  url: https://aryion.com
  sub_urls:
  - https://aryion.com
- name: earnbitmoon
  host: earnbitmoon.club
  url: https://earnbitmoon.club
  sub_urls:
  - https://earnbitmoon.club
- name: freetype
  host: freetype.org
  url: https://freetype.org
  sub_urls:
  - https://freetype.org
- name: hdhub4u
  host: hdhub4u.mov
  url: https://hdhub4u.mov
  sub_urls:
  - https://hdhub4u.mov
- name: ifconfig
  host: ifconfig.io
  url: https://ifconfig.io
  sub_urls:
  - https://ifconfig.io
- name: insightfulreads
  host: insightfulreads.net
  url: https://insightfulreads.net
  sub_urls:
  - https://insightfulreads.net
- name: jtsblog
  host: jts-blog.com
  url: https://jts-blog.com
  sub_urls:
  - https://jts-blog.com
- name: lfrii
  host: l-frii.com
  url: https://l-frii.com
  sub_urls:
  - https://l-frii.com
- name: life3dblog
  host: life3dblog.com
  url: https://life3dblog.com
  sub_urls:
  - https://life3dblog.com
- name: mangapark
  host: mangapark.net
  url: https://mangapark.net
  sub_urls:
  - https://mangapark.net
- name: mangareader
  host: mangareader.to
  url: https://mangareader.to
  sub_urls:
  - https://mangareader.to
- name: manhuaus
  host: manhuaus.com
  url: https://manhuaus.com
  sub_urls:
  - https://manhuaus.com
- name: myupchar
  host: myupchar.com
  url: https://myupchar.com
  sub_urls:
  - https://myupchar.com
- name: nakheelteam
  host: nakheelteam.cc
  url: https://nakheelteam.cc
  sub_urls:
  - https://nakheelteam.cc
- name: onlar
  host: onlar.az
  url: https://onlar.az
  sub_urls:
  - https://onlar.az
- name: pdfdrive
  host: pdfdrive.com
  url: https://pdfdrive.com
  sub_urls:
  - https://pdfdrive.com
- name: prodevreal
  host: prodevreal.com
  url: https://prodevreal.com
  sub_urls:
  - https://prodevreal.com
- name: sflix
  host: sflix.to
  url: https://sflix.to
  sub_urls:
  - https://sflix.to
- name: suksesbogil
  host: suksesbogil.com
  url: https://suksesbogil.com
  sub_urls:
  - https://suksesbogil.com
- name: surahquran
  host: surahquran.com
  url: https://surahquran.com
  sub_urls:
  - https://surahquran.com
- name: voz
  host: voz.vn
  url: https://voz.vn
  sub_urls:
  - https://voz.vn
- name: xbanxia
  host: xbanxia.com
  url: https://xbanxia.com
  sub_urls:
  - https://xbanxia.com

