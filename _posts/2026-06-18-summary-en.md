---
layout: default
title: "Horizon Summary: 2026-06-18 (EN)"
date: 2026-06-18
lang: en
---

> From 74 items, 20 important content pieces were selected

---

1. [Open-Source Models Overtake Proprietary in Market Share](#item-1) ⭐️ 9.0/10
2. [Poolside Releases Laguna M.1: 225B MoE Model for Agentic Coding](#item-2) ⭐️ 9.0/10
3. [10,000 GitHub Repos Found Distributing Trojan Malware](#item-3) ⭐️ 8.0/10
4. [Drug Repurposing by Hospitals and Universities Cuts Costs 90%](#item-4) ⭐️ 8.0/10
5. [Midjourney Launches Medical Imaging Project](#item-5) ⭐️ 8.0/10
6. [AMD Silently Removes Memory Encryption from Consumer Ryzen CPUs](#item-6) ⭐️ 8.0/10
7. [OpenAI Reasoning Model Helps Diagnose Rare Childhood Genetic Diseases](#item-7) ⭐️ 8.0/10
8. [AI Chemist Using GPT-5.4 Improves Drug-Making Reaction](#item-8) ⭐️ 8.0/10
9. [OpenAI Launches LifeSciBench for AI in Life Sciences](#item-9) ⭐️ 8.0/10
10. [Suitcase Robot Gets High via Real Gas Sensor](#item-10) ⭐️ 8.0/10
11. [Leaked Docs Show OpenAI Losing Billions Annually](#item-11) ⭐️ 8.0/10
12. [Swiss parliament lifts ban on new nuclear plants](#item-12) ⭐️ 7.0/10
13. [Cornell's Advanced Compilers Course Goes Self-Guided Online](#item-13) ⭐️ 7.0/10
14. [Modos Color E-Paper Monitor Achieves 60Hz Refresh Rate](#item-14) ⭐️ 7.0/10
15. [W Social's Closed Source Shift Sparks Debate](#item-15) ⭐️ 7.0/10
16. [Gerrymandle: Daily Puzzle Game on Redistricting](#item-16) ⭐️ 7.0/10
17. [Meta Partners with TerraPower for Eight Natrium Nuclear Plants](#item-17) ⭐️ 7.0/10
18. [DeepSeek Chat Adds Vision Understanding](#item-18) ⭐️ 7.0/10
19. [Ubiquiti Unveils Enterprise NAS with ZFS and 25GbE](#item-19) ⭐️ 7.0/10
20. [Git Ignore Alternatives Beyond .gitignore](#item-20) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Open-Source Models Overtake Proprietary in Market Share](https://www.reddit.com/r/LocalLLaMA/comments/1u96545/oss_models_decisively_overtook_proprietary_models/) ⭐️ 9.0/10

Based on the last three months of OpenRouter data, open-source models have decisively overtaken proprietary models in market share, marking a significant shift in AI model adoption. This trend signals growing trust and preference for open-source AI, which could accelerate innovation, reduce costs, and democratize access to advanced AI capabilities across industries. OpenRouter, a multi-model AI inference platform, recorded 97.5 million API requests in four weeks, and its data is used as an empirical adoption metric to study LLM demand.

reddit · r/LocalLLaMA · /u/Comfortable-Rock-498 · Jun 18, 13:21

**Background**: OpenRouter is a platform that provides a unified API to access hundreds of AI models, tracking usage and offering centralized billing. The data reflects real-world adoption by developers and businesses, making it a reliable indicator of market trends.

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/data">Data - Authoritative AI Usage Data for Research | OpenRouter</a></li>
<li><a href="https://openrouter.ai/state-of-ai">State of AI 2025: 100T Token LLM Usage Study | OpenRouter</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**Tags**: `#open-source`, `#AI`, `#market share`, `#OpenRouter`, `#LLMs`

---

<a id="item-2"></a>
## [Poolside Releases Laguna M.1: 225B MoE Model for Agentic Coding](https://www.reddit.com/r/LocalLLaMA/comments/1u9b2i3/poolsidelagunam1_hugging_face_225ba23b/) ⭐️ 9.0/10

Poolside has released Laguna M.1, a 225B total parameter Mixture-of-Experts model with 23B activated parameters per token, designed specifically for agentic coding and long-horizon tasks. It achieves competitive results on benchmarks like SWE-bench Verified (74.6%) and Terminal-Bench 2.0 (45.8%). This release is significant because it brings a large-scale, open-source (Apache 2.0) MoE model that rivals frontier models in agentic coding, potentially accelerating AI-assisted software development. Its efficient 23B active parameters make it feasible for deployment on consumer hardware. Laguna M.1 uses 70 layers with global attention, 256 experts with top-k=16 routing, and auxiliary-loss-free load balancing. It supports a 262,144 token context window and interleaved thinking between tool calls.

reddit · r/LocalLLaMA · /u/pmttyji · Jun 18, 16:30

**Background**: Mixture-of-Experts (MoE) models activate only a fraction of their total parameters per token, enabling large model capacity with lower computational cost. SwiGLU is a gated activation function used in many modern LLMs. Auxiliary-loss-free load balancing, pioneered by DeepSeek, adjusts routing biases without contaminating the training objective.

<details><summary>References</summary>
<ul>
<li><a href="https://sebastianraschka.com/faq/docs/swiglu-modern-llms.html">What is SwiGLU, and why is it common in modern LLM feed-forward layers?</a></li>
<li><a href="https://medium.com/mlwithdev/deepseek-series-auxiliary-loss-free-load-balancing-for-mixture-of-experts-5dbd4e983bba">DeepSeek Series: Auxiliary - Loss - Free Load Balancing for... | Medium</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed excitement about the release, noting its competitive performance and Apache 2.0 license. Some users compared it favorably to other open models like DeepSeek-V4 and Qwen3.5, while others discussed the practical implications for local deployment.

**Tags**: `#LLM`, `#Mixture-of-Experts`, `#Agentic Coding`, `#Open Source`, `#AI`

---

<a id="item-3"></a>
## [10,000 GitHub Repos Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 8.0/10

A security researcher discovered 10,000 GitHub repositories distributing Trojan malware, all created by different accounts with unique names but sharing a common pattern that allowed automated detection. This highlights a massive, systemic abuse of GitHub's platform for supply chain attacks, potentially affecting countless developers and organizations that unknowingly download malicious code. The repositories are not forks, appear legitimate, and are likely targeting automated agents rather than humans, with frequent commit deletions and pushes to evade detection.

hackernews · HN RSS · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: Software supply chain attacks involve injecting malicious code into trusted software components. Open-source repositories like GitHub are common targets because developers often download dependencies without thorough vetting.

<details><summary>References</summary>
<ul>
<li><a href="https://orchidfiles.com/github-repositories-distributing-malware/">How I found 10,000 GitHub repositories distributing Trojan malware</a></li>
<li><a href="https://www.reversinglabs.com/blog/open-source-malware-sows-havoc-on-supply-chain">Open-source repository malware sows Havoc | ReversingLabs</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/Security/Attacks/Supply_chain_attacks">Supply chain attacks - Security | MDN - MDN Web Docs</a></li>

</ul>
</details>

**Discussion**: Commenters express frustration with GitHub's inadequate response, sharing personal experiences of malware repos appearing in trending lists and impersonating legitimate projects. Some note the timing aligns with major elections, suggesting targeted attacks on agents.

**Tags**: `#malware`, `#GitHub`, `#security`, `#supply chain attack`, `#open source`

---

<a id="item-4"></a>
## [Drug Repurposing by Hospitals and Universities Cuts Costs 90%](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 8.0/10

Hospitals and universities are repurposing existing drugs for new uses at 90% lower cost than traditional drug development, but regulatory and patent barriers limit widespread adoption. This could dramatically reduce healthcare costs and provide treatments for rare diseases that pharmaceutical companies ignore, but current incentives and regulations favor patented modifications over cheaper alternatives. Drug repurposing involves finding new uses for already-approved drugs, bypassing early-stage safety trials. However, without manufacturer consent or a new regulatory pathway, repurposed uses often remain off-label and cannot be officially marketed.

hackernews · HN RSS · Jun 18, 10:33 · [Discussion](https://news.ycombinator.com/item?id=48583386)

**Background**: Drug repurposing is a strategy that uses existing drugs for new indications, potentially saving time and money. Despite its promise, financial and regulatory barriers—such as the lack of patent protection for new uses of off-patent drugs—discourage investment. Nonprofits like Cures Within Reach fund repurposing studies for rare diseases, but scaling up requires policy changes.

<details><summary>References</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9336118/">Drug repurposing : a systematic review on root causes, barriers and...</a></li>
<li><a href="https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2019.01664/full">Frontiers | On-Label or Off-Label? Overcoming Regulatory and...</a></li>
<li><a href="https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2025.1670845/full">Frontiers | Overcoming barriers to off-patent drug repurposing: a lifecycle-based policy solutions</a></li>

</ul>
</details>

**Discussion**: Commenters shared personal experiences: one noted that esketamine (Spravato) is a patented modification of ketamine that may be less effective, illustrating broken incentives. Another highlighted a nonprofit funding repurposing studies for Huntington's disease, emphasizing the value for rare diseases. A third pointed out the lack of a regulatory pathway to officially approve repurposed uses without manufacturer involvement.

**Tags**: `#drug repurposing`, `#healthcare costs`, `#regulatory barriers`, `#pharmaceutical innovation`

---

<a id="item-5"></a>
## [Midjourney Launches Medical Imaging Project](https://www.midjourney.com/medical/blogpost) ⭐️ 8.0/10

Midjourney has announced a medical imaging project called Midjourney Medical, which uses AI to reconstruct ultrasound data into CT-like images, aiming to enable full-body scans in as little as 60 seconds. This marks Midjourney's entry into healthcare, a novel application of its AI image generation technology that could make medical imaging faster, cheaper, and more accessible, potentially transforming preventive care. The scanner uses a water-immersion ring with thousands of transducers from Butterfly Network, and the AI reconstructs raw ultrasound data into cross-sectional images similar to CT scans.

hackernews · HN RSS · Jun 18, 01:59 · [Discussion](https://news.ycombinator.com/item?id=48579650)

**Background**: Traditional ultrasound produces 2D images in real-time, while CT scans provide detailed 3D cross-sections but involve radiation and higher cost. Midjourney's approach aims to combine the safety and speed of ultrasound with the diagnostic quality of CT using AI reconstruction.

<details><summary>References</summary>
<ul>
<li><a href="https://www.midjourney.com/medical">Midjourney Medical</a></li>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/952011/midjourney-medical-ai-ultrasound-scan">Midjourney Medical goes from AI image generation to... | The Verge</a></li>
<li><a href="https://www.auntminnie.com/clinical-news/ultrasound/news/15828012/midjourney-unveils-planned-ultrasound-scanner-with-help-from-butterfly">Midjourney unveils planned ultrasound scanner with help... | AuntMinnie</a></li>

</ul>
</details>

**Discussion**: Radiologists express excitement about innovation but raise concerns that ultrasound cannot fully replace CT due to physical limitations, and some question the branding and the idea of routine full-body scans for healthy individuals.

**Tags**: `#AI`, `#medical imaging`, `#Midjourney`, `#healthcare`, `#ultrasound`

---

<a id="item-6"></a>
## [AMD Silently Removes Memory Encryption from Consumer Ryzen CPUs](https://www.tomshardware.com/pc-components/cpus/amd-silently-removes-memory-encryption-from-consumer-ryzen-cpus-leaving-users-unaware-that-they-may-be-vulnerable-security-feature-vanishes-after-newer-agesa-firmware-amd-engineers-go-radio-silent-when-pressed-about-the-change) ⭐️ 8.0/10

AMD has quietly removed memory encryption from consumer Ryzen CPUs through a newer AGESA firmware update, leaving users unaware of potential security vulnerabilities. The feature, known as Transparent Secure Memory Encryption (TSME), was previously available on some consumer Ryzen processors but has been silently disabled. This change exposes consumer Ryzen users to potential physical attacks like RAMbleed and cold boot attacks, as well as ECC error vulnerabilities. The lack of communication from AMD raises concerns about transparency and trust, especially since the feature was previously available and could be enabled by users. The removal was implemented via AGESA firmware updates, which are provided by AMD to motherboard manufacturers and then distributed to users through BIOS updates. The feature TSME encrypts system memory using a single key generated by the AMD Secure Processor at boot, protecting against physical memory attacks.

hackernews · HN RSS · Jun 18, 08:08 · [Discussion](https://news.ycombinator.com/item?id=48582320)

**Background**: AMD's memory encryption technologies include Secure Memory Encryption (SME) and Secure Encrypted Virtualization (SEV), which are primarily marketed for enterprise/server CPUs. Transparent Secure Memory Encryption (TSME) is a variant that encrypts all system memory transparently and was available on some consumer Ryzen CPUs. AGESA (AMD Generic Encapsulated Software Architecture) is the firmware that initializes the CPU and memory on AMD platforms, and updates often bring performance improvements or new features.

<details><summary>References</summary>
<ul>
<li><a href="https://www.amd.com/en/developer/sev.html">AMD Secure Encrypted Virtualization (SEV) | AMD</a></li>
<li><a href="https://docs.kernel.org/arch/x86/amd-memory-encryption.html">19. AMD Memory Encryption — The Linux Kernel documentation</a></li>
<li><a href="https://www.corsair.com/us/en/explorer/diy-builder/memory/why-you-should-care-about-amd-agesa-updates/">Why you should care about AMD AGESA updates | CORSAIR</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some users downplay the risk, arguing that physical access attacks are unlikely for consumer hardware, while others highlight real-world impacts like protection against RAMbleed and ECC errors. There is also frustration over artificial feature segmentation between consumer and enterprise products, with calls for more transparency from AMD.

**Tags**: `#AMD`, `#security`, `#memory encryption`, `#CPU`, `#firmware`

---

<a id="item-7"></a>
## [OpenAI Reasoning Model Helps Diagnose Rare Childhood Genetic Diseases](https://openai.com/index/diagnose-rare-childhood-diseases) ⭐️ 8.0/10

Researchers used an OpenAI reasoning model to identify 18 new diagnoses in previously unsolved cases of rare genetic diseases in children. This demonstrates AI's potential to significantly improve diagnostic rates for rare diseases, which often go undiagnosed for years, and could lead to earlier interventions and better outcomes for affected children. The model, likely OpenAI o3 or a similar reasoning model, analyzes clinical data, genetic information, and literature to suggest diagnoses with underlying reasoning, achieving 18 new diagnoses in previously unsolved cases.

rss · OpenAI Blog · Jun 18, 08:00

**Background**: Rare genetic diseases affect millions of children worldwide, but diagnosis is often delayed due to symptom complexity and lack of specialist knowledge. AI reasoning models, like OpenAI o3, are designed to perform step-by-step logical analysis, making them well-suited for integrating diverse data sources to identify rare conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenAI_o3">OpenAI o3 - Wikipedia</a></li>
<li><a href="https://www.nature.com/articles/d41586-026-00290-9">AI succeeds in diagnosing rare diseases</a></li>

</ul>
</details>

**Tags**: `#AI`, `#healthcare`, `#rare diseases`, `#diagnosis`, `#OpenAI`

---

<a id="item-8"></a>
## [AI Chemist Using GPT-5.4 Improves Drug-Making Reaction](https://openai.com/index/ai-chemist-improves-reaction) ⭐️ 8.0/10

OpenAI and Molecule.one developed a near-autonomous AI chemist powered by GPT-5.4 that successfully improved a challenging reaction used in medicinal chemistry. The system autonomously designed and executed experiments to optimize the reaction conditions. This advancement demonstrates the potential of large language models to accelerate drug discovery by automating complex chemical synthesis tasks. It could significantly reduce the time and cost of developing new pharmaceuticals. The AI chemist used GPT-5.4, which features a 33% reduction in factual errors compared to GPT-5.2 and improved computer use capabilities. The system integrated with Molecule.one's retrosynthesis prediction software to plan and execute experiments autonomously.

rss · OpenAI Blog · Jun 17, 10:00

**Background**: GPT-5.4 is a large language model released by OpenAI in March 2026, with variants including GPT-5.4 Thinking, Pro, mini, and nano. It scored 75% on the OSWorld-Verified benchmark for desktop environment use, outperforming GPT-5.2's 47.3% and approaching the average human score of 72.4%. Molecule.one develops AI software for retrosynthesis prediction, helping chemists find efficient ways to synthesize target molecules.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.4">GPT-5.4</a></li>
<li><a href="https://molecule.one/">molecule . one - Making Molecules . Discovering Chemistry</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Chemistry`, `#Drug Discovery`, `#GPT-5.4`, `#Autonomous Systems`

---

<a id="item-9"></a>
## [OpenAI Launches LifeSciBench for AI in Life Sciences](https://openai.com/index/introducing-life-sci-bench) ⭐️ 8.0/10

OpenAI has introduced LifeSciBench, an expert-authored and expert-reviewed benchmark consisting of 750 tasks designed to evaluate AI systems on real-world life science research tasks and decisions. LifeSciBench addresses the critical need for rigorous AI evaluation in high-stakes domains like life sciences, where errors could have serious consequences. The benchmark's expert-authored rubrics and focus on both accuracy and reasoning process set a new standard for AI safety assessment. The benchmark includes 750 tasks, 79% of which require multiple reasoning or decision-making steps, averaging four steps per task. The strongest AI model tested so far passed only 36.1% of tasks, highlighting the difficulty of the benchmark.

rss · OpenAI Blog · Jun 17, 00:00

**Background**: Benchmarks are standardized tests used to measure AI performance across specific domains. LifeSciBench is designed to reflect the complexity of real life science work, going beyond simple question-answering to evaluate multi-step reasoning and operational usefulness. This is part of a broader effort to ensure AI systems are safe and reliable before deployment in critical fields.

<details><summary>References</summary>
<ul>
<li><a href="https://www.marktechpost.com/2026/06/17/openai-releases-lifescibench-a-750-task-benchmark-grading-ai-models-on-real-life-science-research-with-expert-written-rubric/">OpenAI Releases LifeSciBench, a 750-Task Benchmark Grading AI Models on Real Life-Science Research With Expert-Written Rubric - MarkTechPost</a></li>

</ul>
</details>

**Tags**: `#AI`, `#benchmark`, `#life sciences`, `#OpenAI`, `#evaluation`

---

<a id="item-10"></a>
## [Suitcase Robot Gets High via Real Gas Sensor](https://www.reddit.com/r/LocalLLaMA/comments/1u9a17y/my_suitcase_robot_gets_high_now_off_a_real_gas/) ⭐️ 8.0/10

A suitcase robot named Sparky uses an MQ-2 gas sensor to dynamically adjust LLM sampling parameters (temperature, top_p, top_k) in real time, causing its responses to become genuinely more random and 'loopy' when smoke is detected. This novel integration of a physical sensor with LLM sampling parameters creates emergent, non-scripted behavior, showcasing a creative way to make AI interactions more dynamic and context-aware. The MQ-2 sensor reads smoke every 0.5 seconds against an adaptive clean-air baseline, converting smoke into a 0–10 phase that decays over minutes. At phase 10, temperature reaches ~1.6, top_p 0.99, and top_k 120, causing the robot's speech to become noisier and more associative.

reddit · r/LocalLLaMA · /u/CreativelyBankrupt · Jun 18, 15:52

**Background**: LLM sampling parameters like temperature, top_p, and top_k control the randomness of text generation. Higher temperature increases randomness, while top_p and top_k limit the pool of possible next tokens. The MQ-2 is a semiconductor gas sensor sensitive to smoke and combustible gases, commonly used in gas leak detection.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/MQ-2_and_MQ-9_gas_sensors">MQ-2 and MQ-9 gas sensors</a></li>
<li><a href="https://rumn.medium.com/setting-top-k-top-p-and-temperature-in-llms-3da3a8f74832">Setting Top - K , Top - P and Temperature in LLMs | Medium</a></li>
<li><a href="https://machinelearningplus.com/gen-ai/llm-temperature-top-p-top-k-explained/">LLM Temperature , Top - P , and... - machinelearningplus</a></li>

</ul>
</details>

**Discussion**: The Reddit community praised the project's creativity and humor, with many asking for technical details on the sensor integration and adaptive baseline. Some users discussed the challenge of distinguishing cannabis smoke from other smoke, suggesting sensors like MQ-135 or a combination with a particulate matter sensor.

**Tags**: `#LLM`, `#robotics`, `#creative coding`, `#sensor integration`, `#emergent behavior`

---

<a id="item-11"></a>
## [Leaked Docs Show OpenAI Losing Billions Annually](https://www.reddit.com/r/LocalLLaMA/comments/1u8tcob/leaked_financial_docs_show_openai_is_losing/) ⭐️ 8.0/10

Leaked financial documents reveal that OpenAI is incurring billions of dollars in annual losses, raising questions about the sustainability of its business model. This disclosure is significant because OpenAI is a leading AI company, and its financial struggles could signal broader challenges in the AI industry regarding profitability and investment returns. The leaked documents reportedly show that despite substantial revenue, OpenAI's costs—including compute, talent, and operations—far exceed its income, leading to massive losses.

reddit · r/LocalLLaMA · /u/johnnyApplePRNG · Jun 18, 01:55

**Background**: OpenAI is a prominent AI research and deployment company known for products like ChatGPT and GPT-4. The AI industry is capital-intensive, requiring significant investment in computing infrastructure and skilled personnel, and many companies operate at a loss while pursuing long-term growth.

**Discussion**: The Reddit community expressed mixed reactions, with some users questioning OpenAI's long-term viability and others arguing that heavy investment is typical for high-growth tech companies. Some comments highlighted the need for more efficient models and alternative business strategies.

**Tags**: `#OpenAI`, `#finance`, `#AI industry`, `#business model`, `#leaked documents`

---

<a id="item-12"></a>
## [Swiss parliament lifts ban on new nuclear plants](https://www.bluewin.ch/en/news/switzerland/parliament-lifts-ban-on-new-nuclear-power-plants-3257535.html) ⭐️ 7.0/10

The Swiss parliament voted to lift the ban on building new nuclear power plants, a decision that still requires approval in a public referendum. This move could reshape Switzerland's energy policy, potentially enabling new nuclear projects to address seasonal energy shortages and reduce reliance on fossil fuels. The ban was originally introduced after the Fukushima disaster in 2011. The decision is expected to face strong opposition from left-leaning and green parties, and a referendum is likely to be held.

hackernews · HN RSS · Jun 18, 14:17 · [Discussion](https://news.ycombinator.com/item?id=48585746)

**Background**: Switzerland currently operates four nuclear reactors, which provide about one-third of its electricity. The country has a seasonal energy imbalance, with surplus hydro and solar power in summer and deficits in winter. Lifting the ban could allow for advanced reactor designs like small modular reactors (SMRs).

**Discussion**: Comments are mixed: some see nuclear as a costly distraction, while others believe SMRs represent a promising future. There is skepticism about the referendum's outcome, given strong opposition from left and green parties.

**Tags**: `#nuclear energy`, `#Switzerland`, `#energy policy`, `#politics`, `#referendum`

---

<a id="item-13"></a>
## [Cornell's Advanced Compilers Course Goes Self-Guided Online](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

Cornell University's CS6120 advanced compilers course is now available as a free, self-guided online resource, covering topics such as SSA form and dynamic compilation. This makes high-quality compiler education accessible to a global audience, potentially helping train the next generation of compiler engineers and researchers. The course includes lectures, readings, and assignments, but community feedback notes that its coverage of dynamic compilation focuses on trace compilation, which some consider a dead end, while missing modern techniques like deoptimization and tiering.

hackernews · HN RSS · Jun 18, 11:04 · [Discussion](https://news.ycombinator.com/item?id=48583606)

**Background**: SSA (Static Single Assignment) form is an intermediate representation used in compilers where each variable is assigned exactly once, enabling efficient optimizations. Dynamic compilation, including just-in-time (JIT) compilation, optimizes code at runtime. This course builds on foundational compiler knowledge to explore advanced optimization and runtime techniques.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SSA_form">SSA form</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_compilation">Dynamic compilation</a></li>

</ul>
</details>

**Discussion**: Community comments express appreciation for the free resource but critique its emphasis on trace compilation, which is seen as outdated. Some question what makes the course 'advanced' since many topics are covered in introductory courses. Others discuss related topics like ML in compilers.

**Tags**: `#compilers`, `#online course`, `#programming languages`, `#computer science education`

---

<a id="item-14"></a>
## [Modos Color E-Paper Monitor Achieves 60Hz Refresh Rate](https://spectrum.ieee.org/modos-e-paper-monitor) ⭐️ 7.0/10

Two-person startup Modos is developing the Modos Flow, a 13.3-inch color e-paper monitor with a native resolution of 3200x2400, touch input, and a 60Hz refresh rate. This breakthrough pushes e-paper beyond its traditional niche of static displays, enabling smoother video playback and interactive applications while retaining low power consumption and outdoor readability. The 60Hz refresh rate is made possible by a new display driver technology, and the monitor is currently in fundraising stage with no announced release date.

hackernews · HN RSS · Jun 18, 11:41 · [Discussion](https://news.ycombinator.com/item?id=48583897)

**Background**: E-paper displays, like those used in e-readers, typically have low refresh rates (e.g., 10-15Hz) and are limited to black-and-white or slow color updates. Achieving 60Hz color e-paper has been a long-standing challenge due to the physical properties of electrophoretic ink.

<details><summary>References</summary>
<ul>
<li><a href="https://spectrum.ieee.org/modos-e-paper-monitor">Modos Color Monitor Pushes E-Paper Displays Further - IEEE Spectrum</a></li>
<li><a href="https://smartthermostathub.com/informational/behold-a-60-hz-refresh-rate-e-ink-monitor/">Behold a 60 Hz Refresh Rate E -ink Monitor - Smart Thermostat Hub</a></li>

</ul>
</details>

**Discussion**: Community comments express excitement about the specs and the indie startup's resilience, with some noting potential applications like AI-powered interactive portraits. A YouTube video by the creator is also shared.

**Tags**: `#e-paper`, `#display technology`, `#hardware`, `#startup`

---

<a id="item-15"></a>
## [W Social's Closed Source Shift Sparks Debate](https://blog.elenarossini.com/w-social-public-institutions-and-the-theater-of-european-digital-sovereignty/) ⭐️ 7.0/10

A blog post by Elena Rossini questions whether W Social, a European social network, has switched to closed source, raising concerns about its transparency and business model. This matters because W Social has been promoted as a European digital sovereignty project, and a shift to closed source would undermine its open-source commitments and trust among users and politicians. Community comments note that W Social's GitHub repositories were temporarily hidden but later made visible again, and the project is run as an LLC with a founder from finance, raising questions about profit motives.

hackernews · HN RSS · Jun 18, 12:46 · [Discussion](https://news.ycombinator.com/item?id=48584497)

**Background**: W Social is a European social media platform that launched with high-profile political support, aiming to provide an alternative to US-owned platforms. Open-source transparency is often seen as key to digital sovereignty, as it allows public scrutiny of code and data handling.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/We,_Socialists!">We, Socialists!</a></li>
<li><a href="https://techforhumanitylab.clahs.vt.edu/the-practical-imperative-of-european-digital-sovereignty/">The Practical Imperative of European Digital Sovereignty – Tech for...</a></li>

</ul>
</details>

**Discussion**: Commenters express skepticism about W Social's motives, with one calling it 'TruthSocial with a European accent' and another noting the founder's financial background. Some point out that other European ATproto projects like Eurosky operate more transparently.

**Tags**: `#open source`, `#social media`, `#European digital sovereignty`, `#W Social`, `#transparency`

---

<a id="item-16"></a>
## [Gerrymandle: Daily Puzzle Game on Redistricting](https://gerrymandle.cc/) ⭐️ 7.0/10

A new daily puzzle game called Gerrymandle lets players redraw electoral districts to favor a political party, teaching the mechanics of gerrymandering through interactive play. This game makes a complex and often opaque political tactic accessible to the public, fostering civic education and awareness about electoral fairness. The game includes a rule that if two parties tie in a district, nobody wins it, which simplifies real-world tie-breaking but effectively conveys the core concept of gerrymandering.

hackernews · HN RSS · Jun 18, 14:16 · [Discussion](https://news.ycombinator.com/item?id=48585739)

**Background**: Gerrymandering is the manipulation of electoral district boundaries to advantage a particular party or group. Common tactics include 'cracking' (spreading opposition voters across many districts) and 'packing' (concentrating them in a few districts). The term originated from a 1812 Massachusetts district shaped like a salamander, signed by Governor Elbridge Gerry.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gerrymandering">Gerrymandering</a></li>
<li><a href="https://en.wikipedia.org/wiki/Electoral_district">Electoral district</a></li>

</ul>
</details>

**Discussion**: Commenters praised the game as a great educational tool for civics classes, with some suggesting adding proportional representation as an alternative. Others referenced academic papers on fair districting protocols and discussed the impact of district size on gerrymandering.

**Tags**: `#gerrymandering`, `#game`, `#civic tech`, `#politics`, `#education`

---

<a id="item-17"></a>
## [Meta Partners with TerraPower for Eight Natrium Nuclear Plants](https://neutronbytes.com/2026/01/09/terrapower-in-mega-deal-with-meta-for-eight-natrium-345-mw-advanced-nuclear-plants/) ⭐️ 7.0/10

Meta has signed a commercial agreement with TerraPower to fund the deployment of eight Natrium advanced nuclear reactors, each with a capacity of 345 MW, with initial units targeted for delivery as early as 2032. This deal represents a major investment in advanced nuclear energy to power AI data centers, signaling a shift toward carbon-free baseload power for tech giants. It could accelerate the commercialization of next-generation nuclear reactors and set a precedent for similar partnerships. The agreement includes upfront funding from Meta, not just a power purchase agreement (PPA), though no financial figures have been disclosed. TerraPower's first demonstration Natrium reactor is scheduled to go online in 2031, making the 2032 target for production units ambitious.

hackernews · HN RSS · Jun 18, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48586648)

**Background**: Natrium is an advanced nuclear reactor design developed by TerraPower, featuring a sodium-cooled fast reactor combined with a molten salt thermal energy storage system. It is one of two designs selected by the U.S. Department of Energy's Advanced Reactor Demonstration Program for extensive funding. TerraPower is an American nuclear innovation company headquartered in Bellevue, Washington.

<details><summary>References</summary>
<ul>
<li><a href="https://www.terrapower.com/natrium/">TerraPower Natrium | Advanced Nuclear Energy</a></li>
<li><a href="https://en.wikipedia.org/wiki/TerraPower">TerraPower - Wikipedia</a></li>
<li><a href="https://www.energy.gov/ne/articles/next-gen-nuclear-plant-and-jobs-are-coming-wyoming">Next-Gen Nuclear Plant and Jobs Are Coming... | Department of Energy</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about the feasibility of delivering eight reactors by 2032 given regulatory hurdles and the first demo reactor's 2031 timeline. Some question Meta's massive AI spending without a clear product, while others raise concerns about private companies operating nuclear reactors and potential proliferation risks.

**Tags**: `#nuclear energy`, `#AI infrastructure`, `#Meta`, `#TerraPower`, `#data centers`

---

<a id="item-18"></a>
## [DeepSeek Chat Adds Vision Understanding](https://chat.deepseek.com/) ⭐️ 7.0/10

DeepSeek has introduced vision understanding in its chat application, enabling the AI to describe images but not generate or modify them. This update marks DeepSeek's entry into multimodal AI, allowing users to interact with images through description, which broadens the app's utility for accessibility and content analysis. The vision feature is limited to understanding and describing images; it does not support image generation or editing. Users can upload images for the AI to analyze and describe.

hackernews · HN RSS · Jun 18, 06:17 · [Discussion](https://news.ycombinator.com/item?id=48581458)

**Background**: Multimodal AI models can process multiple types of data, such as text and images. DeepSeek previously focused on text-only interactions; this update adds image understanding capabilities, similar to features in other AI chatbots like GPT-4V.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=_8tcA9-14JQ">DeepSeek Tutorial: How to Use Deep Seek For Beginners - YouTube</a></li>
<li><a href="https://deepseek.chat/">DeepSeek - Advanced AI Chat Assistant</a></li>

</ul>
</details>

**Discussion**: Community members noted the lack of text-to-speech and speech-to-text features, and some reported receiving Chinese responses after a silent update. Overall, the addition of vision was welcomed but seen as incremental.

**Tags**: `#AI`, `#multimodal`, `#DeepSeek`, `#vision`

---

<a id="item-19"></a>
## [Ubiquiti Unveils Enterprise NAS with ZFS and 25GbE](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti announced the Enterprise NAS, a 16-bay storage appliance built on the ZFS file system, featuring dual 25GbE SFP28 ports and redundant power supplies, priced at $3999. This marks Ubiquiti's entry into the enterprise NAS market, leveraging ZFS's data integrity and advanced features, potentially disrupting the storage space for small-to-medium businesses already using UniFi networking. The NAS supports 16 hot-swappable bays, dual 25GbE SFP28 ports, and redundant power supplies. However, community members question whether spinning HDDs can saturate 25Gbps links, and note the $3999 price point may be high for some.

hackernews · HN RSS · Jun 18, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48585866)

**Background**: ZFS is an advanced file system and volume manager known for data integrity, snapshots, and efficient replication. Ubiquiti is best known for its UniFi networking products, and this NAS extends its ecosystem into storage for small-to-medium businesses.

<details><summary>References</summary>
<ul>
<li><a href="https://nascompares.com/news/unifi-enterprise-nas-enas-review-16-bays-zfs-25gbe-iscsi/">UniFi Enterprise NAS ENAS Review – 16 Bays, ZFS... - NAS Compares</a></li>
<li><a href="https://www.ui.com/">UniFi - Rethinking IT - Ubiquiti</a></li>

</ul>
</details>

**Discussion**: Community sentiment is generally positive, with praise for Ubiquiti's no-subscription model and ZFS adoption. However, concerns exist about saturating 25GbE with HDDs and the $3999 price, with some suggesting it targets MSPs managing UniFi networks.

**Tags**: `#NAS`, `#ZFS`, `#Ubiquiti`, `#enterprise storage`, `#networking`

---

<a id="item-20"></a>
## [Git Ignore Alternatives Beyond .gitignore](https://nelson.cloud/.gitignore-isnt-the-only-way-to-ignore-files-in-git/) ⭐️ 7.0/10

An article highlights that Git offers two alternative ways to ignore files without committing ignore rules: the global exclude file and the per-repository .git/info/exclude file. This helps developers avoid cluttering project .gitignore files with personal or environment-specific patterns, reducing merge conflicts and keeping repositories clean. The global exclude file is configured via core.excludesFile (default ~/.config/git/ignore), while .git/info/exclude is local to each repository and not committed.

hackernews · HN RSS · Jun 18, 10:29 · [Discussion](https://news.ycombinator.com/item?id=48583356)

**Background**: Git uses .gitignore files to specify intentionally untracked files that Git should ignore. However, sometimes you want to ignore files only for your local setup, such as editor temporary files or OS-specific files like .DS_Store. The global exclude file and per-repo exclude file serve this purpose without affecting other collaborators.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.github.com/en/get-started/git-basics/ignoring-files">You can configure Git to ignore files you don't want to check in to GitHub.</a></li>
<li><a href="https://git-scm.com/docs/gitignore">Git - gitignore Documentation</a></li>
<li><a href="https://jumptuck.com/blog/2020-11-25-git-core-excludes/">Quick Tip: Git Global Exclude File - Jumptuck</a></li>

</ul>
</details>

**Discussion**: Commenters widely appreciate the global exclude feature, noting it prevents unnecessary .gitignore clutter. Some suggest using ~/.config/git/ignore as the standard location, while others share creative uses like an 'attic' directory for temporary files. A debate arises about whether per-user ignores for OS-specific files should be global or project-level.

**Tags**: `#Git`, `#Version Control`, `#Best Practices`, `#Developer Tools`

---