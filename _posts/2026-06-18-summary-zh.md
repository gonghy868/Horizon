---
layout: default
title: "Horizon Summary: 2026-06-18 (ZH)"
date: 2026-06-18
lang: zh
---

> 从 74 条内容中筛选出 20 条重要资讯。

---

1. [开源模型市场份额超越闭源模型](#item-1) ⭐️ 9.0/10
2. [Poolside 发布 Laguna M.1：面向智能体编程的 225B MoE 模型](#item-2) ⭐️ 9.0/10
3. [发现 1 万个 GitHub 仓库分发木马恶意软件](#item-3) ⭐️ 8.0/10
4. [医院和大学以 90%更低成本实现药物再利用](#item-4) ⭐️ 8.0/10
5. [Midjourney 启动医学影像项目](#item-5) ⭐️ 8.0/10
6. [AMD 悄然移除消费级 Ryzen CPU 内存加密](#item-6) ⭐️ 8.0/10
7. [OpenAI 推理模型助力诊断儿童罕见遗传病](#item-7) ⭐️ 8.0/10
8. [使用 GPT-5.4 的 AI 化学家改进药物合成反应](#item-8) ⭐️ 8.0/10
9. [OpenAI 推出 LifeSciBench 评估 AI 在生命科学中的表现](#item-9) ⭐️ 8.0/10
10. [行李箱机器人通过真实气体传感器变嗨](#item-10) ⭐️ 8.0/10
11. [泄露文件显示 OpenAI 每年亏损数十亿美元](#item-11) ⭐️ 8.0/10
12. [瑞士议会解除新建核电站禁令](#item-12) ⭐️ 7.0/10
13. [康奈尔大学高级编译器课程转为在线自学](#item-13) ⭐️ 7.0/10
14. [Modos 彩色电子纸显示器实现 60Hz 刷新率](#item-14) ⭐️ 7.0/10
15. [W Social 转向闭源引发争议](#item-15) ⭐️ 7.0/10
16. [Gerrymandle：每日重划选区解谜游戏](#item-16) ⭐️ 7.0/10
17. [Meta 与 TerraPower 合作建设八座 Natrium 核电站](#item-17) ⭐️ 7.0/10
18. [DeepSeek 聊天新增视觉理解功能](#item-18) ⭐️ 7.0/10
19. [Ubiquiti 推出基于 ZFS 的企业级 NAS](#item-19) ⭐️ 7.0/10
20. [Git 忽略文件的替代方法](#item-20) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [开源模型市场份额超越闭源模型](https://www.reddit.com/r/LocalLLaMA/comments/1u96545/oss_models_decisively_overtook_proprietary_models/) ⭐️ 9.0/10

根据 OpenRouter 最近三个月的数据，开源模型在市场份额上已决定性地超越闭源模型，标志着 AI 模型采用格局的重大转变。 这一趋势表明对开源 AI 的信任和偏好正在增长，可能加速创新、降低成本，并推动先进 AI 能力在各行业的普及。 OpenRouter 是一个多模型 AI 推理平台，四周内记录了 9750 万次 API 请求，其数据被用作研究 LLM 需求的经验性采用指标。

reddit · r/LocalLLaMA · /u/Comfortable-Rock-498 · 6月18日 13:21

**背景**: OpenRouter 是一个提供统一 API 访问数百个 AI 模型的平台，跟踪使用情况并提供集中计费。这些数据反映了开发者和企业的实际采用情况，是市场趋势的可靠指标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/data">Data - Authoritative AI Usage Data for Research | OpenRouter</a></li>
<li><a href="https://openrouter.ai/state-of-ai">State of AI 2025: 100T Token LLM Usage Study | OpenRouter</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**标签**: `#open-source`, `#AI`, `#market share`, `#OpenRouter`, `#LLMs`

---

<a id="item-2"></a>
## [Poolside 发布 Laguna M.1：面向智能体编程的 225B MoE 模型](https://www.reddit.com/r/LocalLLaMA/comments/1u9b2i3/poolsidelagunam1_hugging_face_225ba23b/) ⭐️ 9.0/10

Poolside 发布了 Laguna M.1，这是一个总参数量为 225B 的混合专家模型，每个 token 激活 23B 参数，专为智能体编程和长周期任务设计。它在 SWE-bench Verified（74.6%）和 Terminal-Bench 2.0（45.8%）等基准测试上取得了有竞争力的结果。 此次发布意义重大，因为它带来了一个大规模、开源（Apache 2.0）的 MoE 模型，在智能体编程方面与前沿模型竞争，可能加速 AI 辅助软件开发。其高效的 23B 激活参数使其能够在消费级硬件上部署。 Laguna M.1 使用 70 层全局注意力、256 个专家（top-k=16 路由）和无辅助损失的负载均衡。它支持 262,144 token 的上下文窗口以及在工具调用之间交错思考。

reddit · r/LocalLLaMA · /u/pmttyji · 6月18日 16:30

**背景**: 混合专家（MoE）模型每个 token 仅激活总参数的一部分，从而以较低的计算成本实现大模型容量。SwiGLU 是一种门控激活函数，用于许多现代 LLM。由 DeepSeek 首创的无辅助损失负载均衡通过调整路由偏置而不污染训练目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sebastianraschka.com/faq/docs/swiglu-modern-llms.html">What is SwiGLU, and why is it common in modern LLM feed-forward layers?</a></li>
<li><a href="https://medium.com/mlwithdev/deepseek-series-auxiliary-loss-free-load-balancing-for-mixture-of-experts-5dbd4e983bba">DeepSeek Series: Auxiliary - Loss - Free Load Balancing for... | Medium</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区对该发布表示兴奋，注意到其有竞争力的性能和 Apache 2.0 许可证。一些用户将其与 DeepSeek-V4 和 Qwen3.5 等其他开放模型进行有利比较，而另一些用户则讨论了本地部署的实际影响。

**标签**: `#LLM`, `#Mixture-of-Experts`, `#Agentic Coding`, `#Open Source`, `#AI`

---

<a id="item-3"></a>
## [发现 1 万个 GitHub 仓库分发木马恶意软件](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 8.0/10

一名安全研究人员发现 1 万个 GitHub 仓库在分发木马恶意软件，这些仓库由不同账户创建、名称各异，但共享一种共同模式，使得自动化检测成为可能。 这凸显了 GitHub 平台被大规模、系统性地滥用于供应链攻击，可能影响无数无意中下载恶意代码的开发者和组织。 这些仓库并非分支，看起来合法，且可能针对自动化代理而非人类，通过频繁删除提交和推送来逃避检测。

hackernews · HN RSS · 6月18日 11:45 · [社区讨论](https://news.ycombinator.com/item?id=48583928)

**背景**: 软件供应链攻击涉及将恶意代码注入受信任的软件组件。像 GitHub 这样的开源仓库是常见目标，因为开发者经常在未彻底审查的情况下下载依赖项。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://orchidfiles.com/github-repositories-distributing-malware/">How I found 10,000 GitHub repositories distributing Trojan malware</a></li>
<li><a href="https://www.reversinglabs.com/blog/open-source-malware-sows-havoc-on-supply-chain">Open-source repository malware sows Havoc | ReversingLabs</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/Security/Attacks/Supply_chain_attacks">Supply chain attacks - Security | MDN - MDN Web Docs</a></li>

</ul>
</details>

**社区讨论**: 评论者对 GitHub 的应对不力表示失望，分享了恶意仓库出现在趋势列表和冒充合法项目的亲身经历。一些人指出时间点与重大选举吻合，暗示针对代理的有目标攻击。

**标签**: `#malware`, `#GitHub`, `#security`, `#supply chain attack`, `#open source`

---

<a id="item-4"></a>
## [医院和大学以 90%更低成本实现药物再利用](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 8.0/10

医院和大学正以比传统药物开发低 90%的成本重新利用现有药物治疗新适应症，但监管和专利壁垒限制了其广泛推广。 这可能大幅降低医疗成本，并为制药公司忽视的罕见病提供治疗方案，但当前的激励和监管机制更倾向于专利修饰而非廉价替代方案。 药物再利用是指为已获批药物寻找新用途，从而跳过早期安全性试验。然而，若无制造商同意或新的监管途径，再利用的适应症通常仍属于超说明书用药，无法正式上市。

hackernews · HN RSS · 6月18日 10:33 · [社区讨论](https://news.ycombinator.com/item?id=48583386)

**背景**: 药物再利用是一种将现有药物用于新适应症的策略，可节省时间和资金。尽管前景广阔，但财务和监管障碍——例如对专利过期药物新用途缺乏专利保护——阻碍了投资。像 Cures Within Reach 这样的非营利组织资助罕见病的再利用研究，但规模化需要政策变革。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9336118/">Drug repurposing : a systematic review on root causes, barriers and...</a></li>
<li><a href="https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2019.01664/full">Frontiers | On-Label or Off-Label? Overcoming Regulatory and...</a></li>
<li><a href="https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2025.1670845/full">Frontiers | Overcoming barriers to off-patent drug repurposing: a lifecycle-based policy solutions</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了个人经历：有人指出 esketamine（Spravato）是氯胺酮的专利修饰版本，可能效果更差，体现了激励机制的缺陷；另有人强调非营利组织资助亨廷顿病再利用研究的价值；还有人指出缺乏无需制造商参与即可正式批准再利用用途的监管途径。

**标签**: `#drug repurposing`, `#healthcare costs`, `#regulatory barriers`, `#pharmaceutical innovation`

---

<a id="item-5"></a>
## [Midjourney 启动医学影像项目](https://www.midjourney.com/medical/blogpost) ⭐️ 8.0/10

Midjourney 宣布了一个名为 Midjourney Medical 的医学影像项目，利用 AI 将超声数据重建为类似 CT 的图像，目标是在 60 秒内完成全身扫描。 这标志着 Midjourney 进入医疗保健领域，是其 AI 图像生成技术的新应用，可能使医学影像更快、更便宜、更易获取，从而可能改变预防性医疗。 该扫描仪使用一个浸水环，配备来自 Butterfly Network 的数千个换能器，AI 将原始超声数据重建为类似于 CT 扫描的横截面图像。

hackernews · HN RSS · 6月18日 01:59 · [社区讨论](https://news.ycombinator.com/item?id=48579650)

**背景**: 传统超声实时生成二维图像，而 CT 扫描提供详细的三维横截面，但涉及辐射且成本较高。Midjourney 的方法旨在利用 AI 重建，将超声的安全性和速度与 CT 的诊断质量结合起来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.midjourney.com/medical">Midjourney Medical</a></li>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/952011/midjourney-medical-ai-ultrasound-scan">Midjourney Medical goes from AI image generation to... | The Verge</a></li>
<li><a href="https://www.auntminnie.com/clinical-news/ultrasound/news/15828012/midjourney-unveils-planned-ultrasound-scanner-with-help-from-butterfly">Midjourney unveils planned ultrasound scanner with help... | AuntMinnie</a></li>

</ul>
</details>

**社区讨论**: 放射科医生对创新表示兴奋，但担心由于物理限制，超声无法完全取代 CT，一些人质疑品牌定位以及为健康人群进行常规全身扫描的想法。

**标签**: `#AI`, `#medical imaging`, `#Midjourney`, `#healthcare`, `#ultrasound`

---

<a id="item-6"></a>
## [AMD 悄然移除消费级 Ryzen CPU 内存加密](https://www.tomshardware.com/pc-components/cpus/amd-silently-removes-memory-encryption-from-consumer-ryzen-cpus-leaving-users-unaware-that-they-may-be-vulnerable-security-feature-vanishes-after-newer-agesa-firmware-amd-engineers-go-radio-silent-when-pressed-about-the-change) ⭐️ 8.0/10

AMD 通过较新的 AGESA 固件更新悄然移除了消费级 Ryzen CPU 的内存加密功能，导致用户可能面临安全漏洞而不自知。该功能称为透明安全内存加密（TSME），此前在某些消费级 Ryzen 处理器上可用，但现已被静默禁用。 这一变化使消费级 Ryzen 用户面临潜在的物理攻击（如 RAMbleed 和冷启动攻击）以及 ECC 错误漏洞。AMD 缺乏沟通引发了对透明度和信任的担忧，尤其是该功能此前可用且用户可自行启用。 移除是通过 AGESA 固件更新实施的，AMD 将固件提供给主板制造商，然后通过 BIOS 更新分发给用户。TSME 功能使用 AMD 安全处理器在启动时生成的单一密钥加密系统内存，以防范物理内存攻击。

hackernews · HN RSS · 6月18日 08:08 · [社区讨论](https://news.ycombinator.com/item?id=48582320)

**背景**: AMD 的内存加密技术包括安全内存加密（SME）和安全加密虚拟化（SEV），主要面向企业/服务器 CPU。透明安全内存加密（TSME）是其变体，可透明地加密所有系统内存，此前在某些消费级 Ryzen CPU 上可用。AGESA（AMD 通用封装软件架构）是 AMD 平台上初始化 CPU 和内存的固件，更新通常带来性能改进或新功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.amd.com/en/developer/sev.html">AMD Secure Encrypted Virtualization (SEV) | AMD</a></li>
<li><a href="https://docs.kernel.org/arch/x86/amd-memory-encryption.html">19. AMD Memory Encryption — The Linux Kernel documentation</a></li>
<li><a href="https://www.corsair.com/us/en/explorer/diy-builder/memory/why-you-should-care-about-amd-agesa-updates/">Why you should care about AMD AGESA updates | CORSAIR</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些用户淡化风险，认为消费级硬件遭遇物理访问攻击的可能性不大；而另一些用户则强调实际影响，如对 RAMbleed 和 ECC 错误的防护。此外，用户对消费级和企业级产品之间人为的功能划分感到不满，呼吁 AMD 提高透明度。

**标签**: `#AMD`, `#security`, `#memory encryption`, `#CPU`, `#firmware`

---

<a id="item-7"></a>
## [OpenAI 推理模型助力诊断儿童罕见遗传病](https://openai.com/index/diagnose-rare-childhood-diseases) ⭐️ 8.0/10

研究人员使用 OpenAI 推理模型，在先前未解决的儿童罕见遗传病病例中识别出 18 个新诊断。 这展示了 AI 显著提高罕见病诊断率的潜力，这些疾病往往多年无法确诊，并可能为受影响儿童带来更早的干预和更好的预后。 该模型（可能是 OpenAI o3 或类似推理模型）通过分析临床数据、遗传信息和文献来提出诊断并给出推理依据，在先前未解决的病例中实现了 18 个新诊断。

rss · OpenAI Blog · 6月18日 08:00

**背景**: 罕见遗传病影响全球数百万儿童，但由于症状复杂和缺乏专科知识，诊断常常被延误。AI 推理模型（如 OpenAI o3）旨在进行逐步逻辑分析，非常适合整合多种数据源以识别罕见疾病。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenAI_o3">OpenAI o3 - Wikipedia</a></li>
<li><a href="https://www.nature.com/articles/d41586-026-00290-9">AI succeeds in diagnosing rare diseases</a></li>

</ul>
</details>

**标签**: `#AI`, `#healthcare`, `#rare diseases`, `#diagnosis`, `#OpenAI`

---

<a id="item-8"></a>
## [使用 GPT-5.4 的 AI 化学家改进药物合成反应](https://openai.com/index/ai-chemist-improves-reaction) ⭐️ 8.0/10

OpenAI 与 Molecule.one 共同开发了一种近乎自主的 AI 化学家，基于 GPT-5.4，成功改进了药物化学中一项具有挑战性的反应。该系统自主设计并执行实验以优化反应条件。 这一进展展示了大型语言模型通过自动化复杂化学合成任务来加速药物发现的潜力。它可能显著降低新药开发的时间和成本。 该 AI 化学家使用了 GPT-5.4，相比 GPT-5.2，其事实错误减少了 33%，并增强了计算机使用能力。该系统与 Molecule.one 的逆合成预测软件集成，自主规划并执行实验。

rss · OpenAI Blog · 6月17日 10:00

**背景**: GPT-5.4 是 OpenAI 于 2026 年 3 月发布的大型语言模型，包含 GPT-5.4 Thinking、Pro、mini 和 nano 等变体。在桌面环境使用基准测试 OSWorld-Verified 中，它获得了 75%的分数，优于 GPT-5.2 的 47.3%，并接近人类平均分 72.4%。Molecule.one 开发用于逆合成预测的 AI 软件，帮助化学家找到合成目标分子的高效途径。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.4">GPT-5.4</a></li>
<li><a href="https://molecule.one/">molecule . one - Making Molecules . Discovering Chemistry</a></li>

</ul>
</details>

**标签**: `#AI`, `#Chemistry`, `#Drug Discovery`, `#GPT-5.4`, `#Autonomous Systems`

---

<a id="item-9"></a>
## [OpenAI 推出 LifeSciBench 评估 AI 在生命科学中的表现](https://openai.com/index/introducing-life-sci-bench) ⭐️ 8.0/10

OpenAI 推出了 LifeSciBench，这是一个由专家编写和审核的基准测试，包含 750 个任务，旨在评估 AI 系统在真实世界生命科学研究任务和决策中的表现。 LifeSciBench 满足了在生命科学等高风险领域对严格 AI 评估的关键需求，因为错误可能带来严重后果。该基准测试的专家编写评分标准和同时关注准确性与推理过程，为 AI 安全评估设立了新标准。 该基准测试包含 750 个任务，其中 79% 需要多个推理或决策步骤，平均每个任务四个步骤。目前测试过的最强 AI 模型仅通过了 36.1% 的任务，凸显了该基准的难度。

rss · OpenAI Blog · 6月17日 00:00

**背景**: 基准测试是用于衡量 AI 在特定领域表现的标准测试。LifeSciBench 旨在反映真实生命科学工作的复杂性，超越简单的问答，评估多步推理和操作实用性。这是确保 AI 系统在关键领域部署前安全可靠这一更广泛努力的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.marktechpost.com/2026/06/17/openai-releases-lifescibench-a-750-task-benchmark-grading-ai-models-on-real-life-science-research-with-expert-written-rubric/">OpenAI Releases LifeSciBench, a 750-Task Benchmark Grading AI Models on Real Life-Science Research With Expert-Written Rubric - MarkTechPost</a></li>

</ul>
</details>

**标签**: `#AI`, `#benchmark`, `#life sciences`, `#OpenAI`, `#evaluation`

---

<a id="item-10"></a>
## [行李箱机器人通过真实气体传感器变嗨](https://www.reddit.com/r/LocalLLaMA/comments/1u9a17y/my_suitcase_robot_gets_high_now_off_a_real_gas/) ⭐️ 8.0/10

一个名为 Sparky 的行李箱机器人使用 MQ-2 气体传感器实时动态调整 LLM 采样参数（temperature、top_p、top_k），当检测到烟雾时，其回应会真正变得更随机、更“迷糊”。 这种将物理传感器与 LLM 采样参数相结合的新颖方式产生了非脚本化的涌现行为，展示了让 AI 交互更加动态和情境感知的创意方法。 MQ-2 传感器每 0.5 秒读取一次烟雾，并与自适应清洁空气基线对比，将烟雾转化为 0-10 的相位，该相位在数分钟内衰减。在相位 10 时，temperature 达到约 1.6，top_p 为 0.99，top_k 为 120，导致机器人的语音变得更嘈杂、更具联想性。

reddit · r/LocalLLaMA · /u/CreativelyBankrupt · 6月18日 15:52

**背景**: LLM 采样参数如 temperature、top_p 和 top_k 控制文本生成的随机性。较高的 temperature 增加随机性，而 top_p 和 top_k 限制可能的下一个 token 池。MQ-2 是一种半导体气体传感器，对烟雾和可燃气体敏感，常用于气体泄漏检测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/MQ-2_and_MQ-9_gas_sensors">MQ-2 and MQ-9 gas sensors</a></li>
<li><a href="https://rumn.medium.com/setting-top-k-top-p-and-temperature-in-llms-3da3a8f74832">Setting Top - K , Top - P and Temperature in LLMs | Medium</a></li>
<li><a href="https://machinelearningplus.com/gen-ai/llm-temperature-top-p-top-k-explained/">LLM Temperature , Top - P , and... - machinelearningplus</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区称赞该项目的创意和幽默，许多人询问传感器集成和自适应基线的技术细节。一些用户讨论了区分大麻烟雾与其他烟雾的挑战，建议使用 MQ-135 传感器或结合颗粒物传感器。

**标签**: `#LLM`, `#robotics`, `#creative coding`, `#sensor integration`, `#emergent behavior`

---

<a id="item-11"></a>
## [泄露文件显示 OpenAI 每年亏损数十亿美元](https://www.reddit.com/r/LocalLLaMA/comments/1u8tcob/leaked_financial_docs_show_openai_is_losing/) ⭐️ 8.0/10

泄露的财务文件显示，OpenAI 每年亏损数十亿美元，引发对其商业模式可持续性的质疑。 这一披露意义重大，因为 OpenAI 是领先的 AI 公司，其财务困境可能预示着 AI 行业在盈利能力和投资回报方面面临更广泛的挑战。 据称，泄露的文件显示，尽管收入可观，但 OpenAI 的成本（包括计算、人才和运营）远超收入，导致巨额亏损。

reddit · r/LocalLLaMA · /u/johnnyApplePRNG · 6月18日 01:55

**背景**: OpenAI 是一家知名的 AI 研究和部署公司，以 ChatGPT 和 GPT-4 等产品闻名。AI 行业是资本密集型行业，需要在计算基础设施和熟练人才方面进行大量投资，许多公司在追求长期增长的同时处于亏损状态。

**社区讨论**: Reddit 社区反应不一，一些用户质疑 OpenAI 的长期生存能力，另一些人则认为高投入是高速增长科技公司的典型特征。部分评论强调了更高效模型和替代商业策略的必要性。

**标签**: `#OpenAI`, `#finance`, `#AI industry`, `#business model`, `#leaked documents`

---

<a id="item-12"></a>
## [瑞士议会解除新建核电站禁令](https://www.bluewin.ch/en/news/switzerland/parliament-lifts-ban-on-new-nuclear-power-plants-3257535.html) ⭐️ 7.0/10

瑞士议会投票决定解除新建核电站的禁令，但该决定仍需在全民公投中获得批准。 此举可能重塑瑞士的能源政策，有望通过新建核项目解决季节性能源短缺问题，并减少对化石燃料的依赖。 该禁令最初是在 2011 年福岛核事故后引入的。预计该决定将面临左翼和绿党的强烈反对，并可能举行全民公投。

hackernews · HN RSS · 6月18日 14:17 · [社区讨论](https://news.ycombinator.com/item?id=48585746)

**背景**: 瑞士目前运营着四座核反应堆，提供约三分之一的电力。该国存在季节性能源不平衡，夏季水电和太阳能过剩，冬季则出现短缺。解除禁令可能允许采用小型模块化反应堆（SMR）等先进反应堆设计。

**社区讨论**: 评论意见不一：一些人认为核能是昂贵且分散注意力的选项，而另一些人则认为 SMR 代表有前途的未来。鉴于左翼和绿党的强烈反对，人们对公投结果持怀疑态度。

**标签**: `#nuclear energy`, `#Switzerland`, `#energy policy`, `#politics`, `#referendum`

---

<a id="item-13"></a>
## [康奈尔大学高级编译器课程转为在线自学](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

康奈尔大学的 CS6120 高级编译器课程现已作为免费自学在线资源开放，涵盖 SSA 形式和动态编译等主题。 这使得高质量的编译器教育面向全球受众，可能有助于培养下一代编译器工程师和研究人员。 该课程包含讲座、阅读材料和作业，但社区反馈指出，其动态编译部分主要关注跟踪编译（trace compilation），一些人认为这是死胡同，而缺少去优化（deoptimization）和分层编译等现代技术。

hackernews · HN RSS · 6月18日 11:04 · [社区讨论](https://news.ycombinator.com/item?id=48583606)

**背景**: SSA（静态单赋值）形式是编译器中使用的一种中间表示，其中每个变量只赋值一次，从而实现高效的优化。动态编译，包括即时编译（JIT），在运行时优化代码。本课程建立在编译器基础知识之上，探索高级优化和运行时技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SSA_form">SSA form</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_compilation">Dynamic compilation</a></li>

</ul>
</details>

**社区讨论**: 社区评论对免费资源表示赞赏，但批评其强调跟踪编译，认为这已过时。有人质疑该课程为何被称为“高级”，因为许多主题在入门课程中已有涉及。其他人则讨论了编译器中的机器学习等相关话题。

**标签**: `#compilers`, `#online course`, `#programming languages`, `#computer science education`

---

<a id="item-14"></a>
## [Modos 彩色电子纸显示器实现 60Hz 刷新率](https://spectrum.ieee.org/modos-e-paper-monitor) ⭐️ 7.0/10

两人初创公司 Modos 正在开发 Modos Flow，这是一款 13.3 英寸彩色电子纸显示器，原生分辨率为 3200x2400，支持触摸输入，刷新率达 60Hz。 这一突破将电子纸从传统的静态显示领域推向更广阔的应用，实现更流畅的视频播放和交互功能，同时保持低功耗和户外可读性。 60Hz 刷新率得益于新的显示驱动技术，该显示器目前处于筹款阶段，尚未公布发布日期。

hackernews · HN RSS · 6月18日 11:41 · [社区讨论](https://news.ycombinator.com/item?id=48583897)

**背景**: 电子纸显示器（如电子阅读器所用）通常刷新率较低（例如 10-15Hz），且仅限于黑白或慢速彩色更新。由于电泳墨水的物理特性，实现 60Hz 彩色电子纸一直是一个长期挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spectrum.ieee.org/modos-e-paper-monitor">Modos Color Monitor Pushes E-Paper Displays Further - IEEE Spectrum</a></li>
<li><a href="https://smartthermostathub.com/informational/behold-a-60-hz-refresh-rate-e-ink-monitor/">Behold a 60 Hz Refresh Rate E -ink Monitor - Smart Thermostat Hub</a></li>

</ul>
</details>

**社区讨论**: 社区评论对其规格和独立初创公司的韧性表示兴奋，有人提到潜在应用如 AI 驱动的交互式肖像。还分享了创作者制作的 YouTube 视频。

**标签**: `#e-paper`, `#display technology`, `#hardware`, `#startup`

---

<a id="item-15"></a>
## [W Social 转向闭源引发争议](https://blog.elenarossini.com/w-social-public-institutions-and-the-theater-of-european-digital-sovereignty/) ⭐️ 7.0/10

Elena Rossini 的一篇博文质疑欧洲社交网络 W Social 是否已转向闭源，引发对其透明度和商业模式的担忧。 此事意义重大，因为 W Social 被宣传为欧洲数字主权项目，转向闭源将破坏其开源承诺，并削弱用户和政界人士的信任。 社区评论指出，W Social 的 GitHub 仓库曾暂时隐藏后又恢复可见，该项目以有限责任公司形式运营，创始人来自金融领域，引发对其盈利动机的质疑。

hackernews · HN RSS · 6月18日 12:46 · [社区讨论](https://news.ycombinator.com/item?id=48584497)

**背景**: W Social 是一个欧洲社交媒体平台，在知名政界人士支持下推出，旨在提供美国平台的替代方案。开源透明常被视为数字主权的关键，因为它允许公众审查代码和数据管理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/We,_Socialists!">We, Socialists!</a></li>
<li><a href="https://techforhumanitylab.clahs.vt.edu/the-practical-imperative-of-european-digital-sovereignty/">The Practical Imperative of European Digital Sovereignty – Tech for...</a></li>

</ul>
</details>

**社区讨论**: 评论者对 W Social 的动机表示怀疑，有人称其为“带欧洲口音的 TruthSocial”，还有人指出创始人的金融背景。一些人提到，其他欧洲 ATproto 项目如 Eurosky 运营更加透明。

**标签**: `#open source`, `#social media`, `#European digital sovereignty`, `#W Social`, `#transparency`

---

<a id="item-16"></a>
## [Gerrymandle：每日重划选区解谜游戏](https://gerrymandle.cc/) ⭐️ 7.0/10

一款名为 Gerrymandle 的每日解谜游戏上线，玩家通过重划选区来偏袒某一政党，从而在互动中学习选区划分的操纵技巧。 该游戏将复杂且常不透明的政治策略普及给公众，促进公民教育并提高对选举公平性的认识。 游戏设定了一条规则：若两党在一个选区中得票持平，则无人获胜；这简化了现实中的平局处理，但有效传达了选区划分的核心概念。

hackernews · HN RSS · 6月18日 14:16 · [社区讨论](https://news.ycombinator.com/item?id=48585739)

**背景**: Gerrymandering（选区划分不公）是指操纵选区边界以利于某一政党或群体的行为。常见策略包括“分散”（将反对派选民分散到多个选区）和“集中”（将反对派选民集中到少数选区）。该术语源于 1812 年马萨诸塞州一个形似蝾螈的选区，由州长埃尔布里奇·格里签署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gerrymandering">Gerrymandering</a></li>
<li><a href="https://en.wikipedia.org/wiki/Electoral_district">Electoral district</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞该游戏是公民课堂的优秀教育工具，有人建议增加比例代表制作为替代方案。还有人引用了关于公平选区划分协议的学术论文，并讨论了选区规模对选区划分不公的影响。

**标签**: `#gerrymandering`, `#game`, `#civic tech`, `#politics`, `#education`

---

<a id="item-17"></a>
## [Meta 与 TerraPower 合作建设八座 Natrium 核电站](https://neutronbytes.com/2026/01/09/terrapower-in-mega-deal-with-meta-for-eight-natrium-345-mw-advanced-nuclear-plants/) ⭐️ 7.0/10

Meta 与 TerraPower 签署了一项商业协议，资助部署八座 Natrium 先进核反应堆，每座容量为 345 兆瓦，首批机组目标最早于 2032 年交付。 这笔交易代表了对先进核能的重大投资，用于为 AI 数据中心供电，标志着科技巨头向无碳基荷电力的转变。它可能加速下一代核反应堆的商业化，并为类似合作树立先例。 该协议包括 Meta 的前期资金投入，而不仅仅是购电协议（PPA），但未披露具体金额。TerraPower 的首座 Natrium 示范反应堆计划于 2031 年投运，因此 2032 年生产机组的交付目标颇具挑战性。

hackernews · HN RSS · 6月18日 15:13 · [社区讨论](https://news.ycombinator.com/item?id=48586648)

**背景**: Natrium 是 TerraPower 开发的先进核反应堆设计，采用钠冷快堆与熔盐热能存储系统相结合。它是美国能源部先进反应堆示范计划选中的两个设计之一，获得了大量资金。TerraPower 是一家总部位于华盛顿州贝尔维尤的美国核能创新公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.terrapower.com/natrium/">TerraPower Natrium | Advanced Nuclear Energy</a></li>
<li><a href="https://en.wikipedia.org/wiki/TerraPower">TerraPower - Wikipedia</a></li>
<li><a href="https://www.energy.gov/ne/articles/next-gen-nuclear-plant-and-jobs-are-coming-wyoming">Next-Gen Nuclear Plant and Jobs Are Coming... | Department of Energy</a></li>

</ul>
</details>

**社区讨论**: 社区评论对在 2032 年前交付八座反应堆的可行性表示怀疑，考虑到监管障碍以及首座示范堆 2031 年的投运时间。一些人质疑 Meta 在没有明确产品的情况下进行巨额 AI 投入，而另一些人则对私营公司运营核反应堆及潜在的扩散风险表示担忧。

**标签**: `#nuclear energy`, `#AI infrastructure`, `#Meta`, `#TerraPower`, `#data centers`

---

<a id="item-18"></a>
## [DeepSeek 聊天新增视觉理解功能](https://chat.deepseek.com/) ⭐️ 7.0/10

DeepSeek 在其聊天应用中引入了视觉理解功能，使 AI 能够描述图像，但不能生成或修改图像。 此次更新标志着 DeepSeek 进入多模态 AI 领域，允许用户通过描述与图像交互，从而扩展了应用在可访问性和内容分析方面的实用性。 视觉功能仅限于理解和描述图像，不支持图像生成或编辑。用户可以上传图像供 AI 分析和描述。

hackernews · HN RSS · 6月18日 06:17 · [社区讨论](https://news.ycombinator.com/item?id=48581458)

**背景**: 多模态 AI 模型可以处理多种类型的数据，例如文本和图像。DeepSeek 此前专注于纯文本交互；此次更新增加了图像理解能力，类似于 GPT-4V 等其他 AI 聊天机器人的功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=_8tcA9-14JQ">DeepSeek Tutorial: How to Use Deep Seek For Beginners - YouTube</a></li>
<li><a href="https://deepseek.chat/">DeepSeek - Advanced AI Chat Assistant</a></li>

</ul>
</details>

**社区讨论**: 社区成员指出缺少文本转语音和语音转文本功能，有些人报告在静默更新后收到中文回复。总体而言，视觉功能的加入受到欢迎，但被视为增量更新。

**标签**: `#AI`, `#multimodal`, `#DeepSeek`, `#vision`

---

<a id="item-19"></a>
## [Ubiquiti 推出基于 ZFS 的企业级 NAS](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti 发布了 Enterprise NAS，这是一款基于 ZFS 文件系统的 16 盘位存储设备，配备双 25GbE SFP28 端口和冗余电源，售价为 3999 美元。 这标志着 Ubiquiti 进入企业级 NAS 市场，利用 ZFS 的数据完整性和高级功能，可能对已使用 UniFi 网络的中小企业存储领域产生颠覆性影响。 该 NAS 支持 16 个热插拔盘位、双 25GbE SFP28 端口和冗余电源。但社区成员质疑机械硬盘能否饱和 25Gbps 链路，并指出 3999 美元的定价对某些用户可能偏高。

hackernews · HN RSS · 6月18日 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48585866)

**背景**: ZFS 是一种高级文件系统和卷管理器，以数据完整性、快照和高效复制著称。Ubiquiti 以其 UniFi 网络产品闻名，这款 NAS 将其生态系统扩展到中小企业的存储领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nascompares.com/news/unifi-enterprise-nas-enas-review-16-bays-zfs-25gbe-iscsi/">UniFi Enterprise NAS ENAS Review – 16 Bays, ZFS... - NAS Compares</a></li>
<li><a href="https://www.ui.com/">UniFi - Rethinking IT - Ubiquiti</a></li>

</ul>
</details>

**社区讨论**: 社区情绪总体积极，称赞 Ubiquiti 的无订阅模式和采用 ZFS。但存在对机械硬盘饱和 25GbE 以及 3999 美元价格的担忧，一些人认为它针对的是管理 UniFi 网络的 MSP。

**标签**: `#NAS`, `#ZFS`, `#Ubiquiti`, `#enterprise storage`, `#networking`

---

<a id="item-20"></a>
## [Git 忽略文件的替代方法](https://nelson.cloud/.gitignore-isnt-the-only-way-to-ignore-files-in-git/) ⭐️ 7.0/10

一篇文章指出，Git 提供了两种无需提交忽略规则即可忽略文件的替代方法：全局排除文件和每个仓库的 .git/info/exclude 文件。 这有助于开发者避免用个人或环境特定的模式污染项目的 .gitignore 文件，从而减少合并冲突并保持仓库整洁。 全局排除文件通过 core.excludesFile 配置（默认 ~/.config/git/ignore），而 .git/info/exclude 是每个仓库本地的且不会被提交。

hackernews · HN RSS · 6月18日 10:29 · [社区讨论](https://news.ycombinator.com/item?id=48583356)

**背景**: Git 使用 .gitignore 文件来指定 Git 应忽略的故意未跟踪文件。然而，有时你只想为本地设置忽略文件，例如编辑器临时文件或操作系统特定文件（如 .DS_Store）。全局排除文件和每个仓库的排除文件可以满足此目的，而不会影响其他协作者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.github.com/en/get-started/git-basics/ignoring-files">You can configure Git to ignore files you don't want to check in to GitHub.</a></li>
<li><a href="https://git-scm.com/docs/gitignore">Git - gitignore Documentation</a></li>
<li><a href="https://jumptuck.com/blog/2020-11-25-git-core-excludes/">Quick Tip: Git Global Exclude File - Jumptuck</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍赞赏全局排除功能，认为它可以避免不必要的 .gitignore 杂乱。有人建议使用 ~/.config/git/ignore 作为标准位置，而其他人则分享了创造性用法，例如用于临时文件的 'attic' 目录。关于操作系统特定文件的按用户忽略应该是全局还是项目级别，引发了一场讨论。

**标签**: `#Git`, `#Version Control`, `#Best Practices`, `#Developer Tools`

---