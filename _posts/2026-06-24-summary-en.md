---
layout: default
title: "Horizon Summary: 2026-06-24 (EN)"
date: 2026-06-24
lang: en
---

> From 66 items, 20 important content pieces were selected

---

1. [Carmack: Pushing Team Too Hard During Quake Ruined id Software](#item-1) ⭐️ 8.0/10
2. [Open-Source AI: The Only Path for Global Access](#item-2) ⭐️ 8.0/10
3. [Krea 2: Open-weights 12B image model released](#item-3) ⭐️ 8.0/10
4. [Researcher claims Microsoft quantum breakthrough invalid due to Python errors](#item-4) ⭐️ 8.0/10
5. [Founding a GmbH in Germany: 152 Days of Bureaucracy](#item-5) ⭐️ 8.0/10
6. [OpenAI and Broadcom Unveil Jalapeño Inference Chip](#item-6) ⭐️ 8.0/10
7. [GPT-5 Pro Solves 3-Year Immunology Mystery](#item-7) ⭐️ 8.0/10
8. [CAPTCHAs Have Failed for 20 Years](#item-8) ⭐️ 8.0/10
9. [Google Adds Computer Use to Gemini 3.5 Flash](#item-9) ⭐️ 8.0/10
10. [Dijkstra's Personal Library Archived in Leuven](#item-10) ⭐️ 8.0/10
11. [Swiss Supreme Court Evaluates Abliterated Model Heretic](#item-11) ⭐️ 8.0/10
12. [Unlimited-OCR 3.3B Model Released on ModelScope](#item-12) ⭐️ 8.0/10
13. [20x Speedup for GLM5.2 on GH200 via Model Hacks](#item-13) ⭐️ 8.0/10
14. [AMD Strix Halo NPU Now Usable with ROCm Hybrid Mode](#item-14) ⭐️ 8.0/10
15. [Qwen Releases 35B MoE World Model for Agent Simulation](#item-15) ⭐️ 8.0/10
16. [US Bill Mandates Location Tracking for Advanced AI Chips](#item-16) ⭐️ 8.0/10
17. [RubyLLM: Unified Ruby Framework for Major AI Providers](#item-17) ⭐️ 7.0/10
18. [Bunny DNS Goes Free, Challenges Cloudflare](#item-18) ⭐️ 7.0/10
19. [Nub: A Bun-like toolkit for Node.js](#item-19) ⭐️ 7.0/10
20. [Hobby OS Runs Windows Games via Wine](#item-20) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Carmack: Pushing Team Too Hard During Quake Ruined id Software](https://twitter.com/ID_AA_Carmack/status/2069799283369345247) ⭐️ 8.0/10

John Carmack admitted that he pushed his team too hard during the development of Quake, failing to recognize that maturing companies need more slack, and that constant startup intensity leads to burnout, which ultimately gutted id Software. This reflection offers high-value insights into the dangers of unsustainable work intensity in game development and startup culture, serving as a cautionary tale for leaders about long-term team health versus short-term success. Carmack's tweet references a quote from Sandy Petersen, a designer on Quake, and the discussion includes links to interviews where Petersen shares his side of the story. Despite Quake's success, the burnout led to long-term damage that some argue persisted through later titles like Doom 3.

hackernews · HN RSS · Jun 24, 15:56 · [Discussion](https://news.ycombinator.com/item?id=48661825)

**Background**: id Software was a pioneering game developer known for titles like Wolfenstein 3D, Doom, and Quake. John Carmack was the lead programmer and a co-founder. The company operated with a startup intensity that produced groundbreaking games but also led to high employee turnover and burnout.

**Discussion**: Commenters largely agree with Carmack's self-criticism, with some noting that Quake III Arena still showed energy but that by Doom 3 the company had lost its edge. Others share links to Sandy Petersen's interviews, providing additional context on the team's struggles.

**Tags**: `#game development`, `#management`, `#startup culture`, `#software engineering`, `#leadership`

---

<a id="item-2"></a>
## [Open-Source AI: The Only Path for Global Access](https://techstrong.ai/articles/for-most-of-the-world-open-source-ai-is-the-only-way-forward/) ⭐️ 8.0/10

An article argues that open-source AI is essential for most of the world to access AI technology, preventing dominance by a few nations and corporations. This matters because without open-source AI, global inequity in AI access could worsen, concentrating power in a few hands and stifling innovation in the Global South. The article highlights that AI models are trained on humanity's collective intellectual output, which should belong to everyone, not just a few corporations.

hackernews · HN RSS · Jun 24, 14:50 · [Discussion](https://news.ycombinator.com/item?id=48660839)

**Background**: Open-source AI refers to models whose code and weights are publicly available, allowing anyone to use, modify, and distribute them. This contrasts with proprietary AI, which is controlled by a single entity. The debate centers on whether AI should be a digital commons or a private good.

**Discussion**: Commenters largely agree with the article's stance, emphasizing that AI should be a digital commons. Some raise concerns about hardware costs limiting access, while others note the risk of geopolitical hegemony in AI.

**Tags**: `#open-source`, `#AI`, `#democratization`, `#geopolitics`, `#digital commons`

---

<a id="item-3"></a>
## [Krea 2: Open-weights 12B image model released](https://www.krea.ai/blog/krea-2-technical-report) ⭐️ 8.0/10

Krea has released Krea 2 (K2), an open-weights 12-billion-parameter text-to-image foundation model, along with a detailed technical report covering training, data curation, and infrastructure. Two variants are available: K2 Raw and K2 Turbo, the latter being distilled for faster inference. This release provides the community with a high-quality, open-weights image model that emphasizes aesthetic diversity and creative control, potentially advancing open-source image generation. The detailed technical report offers valuable insights into training large-scale models, benefiting researchers and practitioners. Krea 2 is a 12B dense Diffusion Transformer (DiT) using a Qwen Image VAE and Qwen3-VL text encoder with multi-layer feature aggregation. The Turbo variant is both guidance- and timestep-distilled for faster generation, and GGUF quantized versions are already available.

hackernews · HN RSS · Jun 23, 15:31 · [Discussion](https://news.ycombinator.com/item?id=48646659)

**Background**: Text-to-image models generate images from textual descriptions. Open-weights models allow the community to run, fine-tune, and study the model freely. Krea 2 is positioned as a model focused on aesthetics and creative exploration, trained from scratch rather than fine-tuned from existing models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.krea.ai/blog/krea-2-technical-report">Krea 2 Technical Report - Krea</a></li>
<li><a href="https://github.com/krea-ai/krea-2">GitHub - krea-ai/krea-2: Official inference code for Krea 2</a></li>
<li><a href="https://www.youtube.com/watch?v=k8-9qGbPfpM">Krea 2 Locally In ComfyUI - This 12B T2I Model Is A Beast ... Introducing Krea 2 GitHub - inferless/flux-1-krea-dev: 12B model distilled from ... Krea 2 Open-Source Models are now available in ComfyUI</a></li>

</ul>
</details>

**Discussion**: The community praised the in-depth technical report and the open release, with some noting the 'keep the manifold wide' approach to style diversity. However, some commenters felt the model may be 'fighting the past war' given the emergence of advanced image-to-image and agentic composition models.

**Tags**: `#AI`, `#image generation`, `#open source`, `#machine learning`, `#technical report`

---

<a id="item-4"></a>
## [Researcher claims Microsoft quantum breakthrough invalid due to Python errors](https://www.theregister.com/research/2026/06/24/boffin-claims-microsofts-supposed-quantum-leap-does-not-compute-due-to-basic-python-errors/5260489) ⭐️ 8.0/10

A researcher, identified as Legg, claims that Microsoft's quantum computing breakthrough is invalid due to basic Python errors in data processing, specifically in the asymmetry computation within the topological gap protocol (TGP) software. This challenge undermines the credibility of Microsoft's high-profile topological qubit claim, which was published in Nature and touted as a transformative leap toward practical quantum computing. The bug involves using Python array reversal (x[::-1]) based on index position rather than actual physical bias voltages, effectively ignoring the physical coordinates. Fixing this bug reportedly invalidates the research results.

hackernews · HN RSS · Jun 24, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48661535)

**Background**: Microsoft announced a quantum computing breakthrough in February 2025, claiming to have created the first topological qubits using a new class of materials called topoconductors. The topological gap protocol (TGP) is a key software tool used to analyze experimental data and demonstrate the existence of topological qubits. Python is commonly used in quantum computing research for data analysis and control.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theregister.com/research/2026/06/24/boffin-claims-microsofts-supposed-quantum-leap-does-not-compute-due-to-basic-python-errors/5260489">Boffin claims Microsoft's supposed quantum leap does not compute due to 'basic Python errors'</a></li>
<li><a href="https://azure.microsoft.com/en-us/blog/quantum/2025/02/19/microsoft-unveils-majorana-1-the-worlds-first-quantum-processor-powered-by-topological-qubits/">Microsoft unveils Majorana 1, the world’s first quantum processor powered by topological qubits - Microsoft Azure Quantum Blog</a></li>
<li><a href="https://www.nature.com/articles/d41586-025-00683-2">Microsoft quantum computing 'breakthrough' faces fresh ...</a></li>

</ul>
</details>

**Discussion**: Community comments on The Register and Hacker News confirm the bug, with users like jdw64 and frollogaston identifying the exact issue in the source code. Some express embarrassment for Microsoft, noting previous issues with Majorana fermion quantum computing, while others appreciate the technical depth of the article.

**Tags**: `#quantum computing`, `#Microsoft`, `#research integrity`, `#Python`, `#bug`

---

<a id="item-5"></a>
## [Founding a GmbH in Germany: 152 Days of Bureaucracy](https://paolino.me/founding-a-company-in-germany/) ⭐️ 8.0/10

The author chronicles a 152-day ordeal to incorporate a GmbH in Germany, costing €9,600, and still being unable to send an invoice due to missing tax IDs. This firsthand account highlights the severe bureaucratic hurdles and hidden costs that deter entrepreneurs from starting businesses in Germany, impacting the country's startup ecosystem. The author attempted to use a GmbH & Co. KG structure to reduce liability but faced delays at every step, including notarization, commercial register entry, and tax ID assignment.

hackernews · HN RSS · Jun 24, 12:31 · [Discussion](https://news.ycombinator.com/item?id=48658718)

**Background**: A GmbH (Gesellschaft mit beschränkter Haftung) is a German limited liability company requiring €25,000 share capital and notarized registration. The UG (Unternehmergesellschaft) is a cheaper alternative with lower capital but perceived as less reputable. The author chose a more complex structure to avoid double taxation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.firma.de/en/company-formation/how-to-set-up-a-gmbh-the-definitive-guide-to-starting-a-limited-liability-company-in-germany/">How to set up a GmbH in Germany: Ultimate checklist for your limited liability company</a></li>
<li><a href="https://se-legal.de/company-law-advice-germany/establishing-a-company-in-germany/gmbh-company-formation/?lang=en">GmbH Company Formation in Germany: Legal Advice</a></li>
<li><a href="https://mystartupgermany.com/german-tax-ids-for-freelancers/">German Tax IDs for Freelancers Explained | My Startup Germany</a></li>

</ul>
</details>

**Discussion**: Commenters debated the necessity of the €25,000 minimum capital for GmbH, with some arguing it protects creditors while others see it as an unnecessary barrier. Several noted that the author's chosen structure (GmbH & Co. KG) is unusual and added complexity.

**Tags**: `#startups`, `#Germany`, `#entrepreneurship`, `#bureaucracy`, `#company formation`

---

<a id="item-6"></a>
## [OpenAI and Broadcom Unveil Jalapeño Inference Chip](https://openai.com/index/openai-broadcom-jalapeno-inference-chip/) ⭐️ 8.0/10

OpenAI and Broadcom have unveiled Jalapeño, a custom AI chip designed specifically for LLM inference, with early testing showing substantially better performance per watt than current state-of-the-art chips. The chip was developed from design to production in nine months, accelerated by OpenAI's own models, and is expected to be deployed at gigawatt scale by the end of 2026. This marks OpenAI's first entry into custom AI silicon, signaling a strategic shift toward hardware-software co-design to optimize LLM inference at scale. By building its own inference chip, OpenAI can reduce reliance on general-purpose GPUs like NVIDIA's, potentially lowering costs and improving efficiency for serving models like GPT-4 and future LLMs. The chip is manufactured by TSMC, as confirmed by community comments, and is designed specifically for inference rather than training. OpenAI designed the chip from scratch based on its deep understanding of LLM fundamentals, with Broadcom handling chip implementation and Celestica handling board and rack system integration.

hackernews · OpenAI Blog · Jun 24, 13:14 · [Discussion](https://news.ycombinator.com/item?id=48659257)

**Background**: LLM inference is the process of running a trained large language model to generate responses, which requires significant computational resources and memory. Optimizing inference is critical for reducing latency and cost in production deployments. Custom AI chips like Google's TPUs and Cerebras's Wafer Scale Engine have been developed to accelerate specific workloads, and OpenAI's move follows this trend of vertical integration in AI hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html">OpenAI and Broadcom reveal Jalapeno, first AI chip in partnership</a></li>
<li><a href="https://investors.broadcom.com/news-releases/news-release-details/openai-and-broadcom-unveil-llm-optimized-intelligence-processor">OpenAI and Broadcom Unveil LLM-Optimized Intelligence Processor | Broadcom Inc.</a></li>

</ul>
</details>

**Discussion**: The community is generally positive but skeptical about the pre-IPO timing, with one commenter noting that the chip will be deployed after OpenAI's IPO and may be used as a future promise in the IPO brochure. Others draw comparisons to Google TPUs and Cerebras, and one commenter highlights the trend that 'if you care about software, build hardware.'

**Tags**: `#AI hardware`, `#LLM inference`, `#OpenAI`, `#Broadcom`, `#custom chip`

---

<a id="item-7"></a>
## [GPT-5 Pro Solves 3-Year Immunology Mystery](https://openai.com/index/gpt-5-immunology-mystery) ⭐️ 8.0/10

GPT-5 Pro, OpenAI's latest AI model, helped immunologist Derya Unutmaz solve a three-year-old mystery about T cell behavior, offering new insights into immune regulation. This breakthrough demonstrates GPT-5's potential to accelerate scientific discovery, with implications for developing treatments for cancer and autoimmune diseases. GPT-5 Pro uses more compute to think harder and provide consistently better answers, and is available via the OpenAI Responses API for advanced multi-turn interactions.

rss · OpenAI Blog · Jun 23, 17:00

**Background**: T cells are a type of white blood cell crucial for adaptive immunity, and their behavior determines the success of immunotherapies. Understanding T cell regulation is key to treating cancer and autoimmune disorders, but some mechanisms have remained elusive for years.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpt-5/">Introducing GPT‑5 - OpenAI</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-5-pro">GPT-5 Pro Model | OpenAI API</a></li>
<li><a href="https://news.cornell.edu/stories/2022/05/t-cell-behavior-determines-immunotherapy-success">T cell behavior determines immunotherapy success | Cornell Chronicle</a></li>

</ul>
</details>

**Tags**: `#GPT-5`, `#immunology`, `#AI in science`, `#cancer research`, `#breakthrough`

---

<a id="item-8"></a>
## [CAPTCHAs Have Failed for 20 Years](https://www.browserbase.com/blog/why-captchas-are-getting-harder) ⭐️ 8.0/10

A new article argues that CAPTCHAs have been ineffective for two decades, explaining why they are becoming increasingly difficult for users. This matters because CAPTCHAs are widely used for security, yet they degrade user experience and are often bypassed by bots, highlighting a fundamental flaw in web security. The article claims that CAPTCHAs have failed for 20 years, and their increasing difficulty is a symptom of this failure, not a solution.

rss · HN RSS · Jun 24, 16:02

**Background**: CAPTCHAs are tests designed to distinguish humans from bots, typically by asking users to identify distorted text or images. They have been a standard security measure since the early 2000s, but advances in AI have made them easier for bots to solve while frustrating human users.

**Tags**: `#CAPTCHA`, `#security`, `#usability`, `#web security`

---

<a id="item-9"></a>
## [Google Adds Computer Use to Gemini 3.5 Flash](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 8.0/10

Google has introduced built-in computer use capabilities in its Gemini 3.5 Flash model, enabling developers to build AI agents that can see, reason, and take actions across browser, mobile, and desktop environments. This advancement allows AI to directly interact with computer interfaces, significantly expanding automation possibilities for enterprises and developers, and positioning Gemini 3.5 Flash as a key player in the agentic AI era. Gemini 3.5 Flash is optimized for sub-agent deployment, multi-step workflows, and long-horizon tasks at scale, offering sustained frontier-level intelligence at higher speed and lower cost.

rss · HN RSS · Jun 24, 17:21

**Background**: Computer use refers to an AI model's ability to interact with graphical user interfaces (GUIs) like a human would, by seeing screen content and performing actions such as clicking or typing. This capability builds on earlier function calling and tool use, enabling more autonomous agents.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/">Introducing computer use in Gemini 3.5 Flash - The Keyword</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3.5 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://blockchain.news/news/google-computer-use-gemini-3-5-flash">Google Adds Computer Use to Gemini 3.5 Flash for Enterprise AI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Gemini`, `#computer use`, `#Google`, `#machine learning`

---

<a id="item-10"></a>
## [Dijkstra's Personal Library Archived in Leuven](https://www.dijkstrascry.com/inventory) ⭐️ 8.0/10

Edsger Dijkstra's personal library has been housed and archived in Leuven, Belgium, preserving his collection of books, papers, and notes for future generations. This archive ensures that the intellectual legacy of a foundational computer scientist is preserved, offering researchers and historians invaluable insight into the development of computing. The library includes Dijkstra's annotated books, manuscripts, and correspondence, providing a unique window into his thought process and the history of computer science.

rss · HN RSS · Jun 24, 15:10

**Background**: Edsger Dijkstra was a pioneering computer scientist known for his work on algorithms, structured programming, and the concept of semaphores. His personal library contains materials that document his career and the evolution of computer science from the 1950s onward.

**Tags**: `#computer science`, `#history`, `#Dijkstra`, `#archives`

---

<a id="item-11"></a>
## [Swiss Supreme Court Evaluates Abliterated Model Heretic](https://www.reddit.com/r/LocalLLaMA/comments/1ueeund/the_swiss_federal_supreme_court_is_evaluating/) ⭐️ 8.0/10

The Swiss Federal Supreme Court is evaluating the abliterated model Heretic to mitigate over-alignment in LLMs for legal applications, as detailed in a recent paper. This marks the first known instance of a real-world judicial body testing an abliterated model for official use. This development is significant because it demonstrates that over-alignment is a practical problem even in high-stakes domains like law, and that abliteration—a controversial technique—is being considered as a legitimate solution by a national supreme court. It could influence how other legal systems and regulated industries approach LLM safety and censorship. The paper "Measuring & Mitigating Over-Alignment for LLMs in Multilingual Criminal Law Courts" evaluates Heretic in Section 5.2 with a favorable conclusion. Heretic is an open-source tool that automates abliteration using Optuna-driven optimization, surgically removing refusal directions from model weights without retraining.

reddit · r/LocalLLaMA · /u/-p-e-w- · Jun 24, 14:19

**Background**: Over-alignment refers to LLMs refusing legitimate requests due to excessive safety training, which can hinder practical use in domains like law. Abliteration is a technique that removes these refusal behaviors by modifying model weights, often using mechanistic interpretability. Heretic is one such tool that automates this process.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/collections/DavidAU/heretic-abliterated-uncensored-unrestricted-power">Heretic - Abliterated, Uncensored, Unrestricted POWER. - a DavidAU Collection</a></li>
<li><a href="https://aithinkerlab.com/heretic-ai-abliteration-benchmarks-2026/">Heretic vs Abliterated LLMs: Refusal Rates & Benchmarks (2026)</a></li>
<li><a href="https://arxiv.org/html/2509.08833v1">Position: The Pitfalls of Over-Alignment: Overly Caution ...</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed surprise and amusement that a supreme court is evaluating an abliterated model, with many noting the irony that such models are often associated with malicious use. Commenters generally supported the court's pragmatic approach to solving over-alignment in legal contexts.

**Tags**: `#LLM`, `#over-alignment`, `#abliteration`, `#legal AI`, `#safety`

---

<a id="item-12"></a>
## [Unlimited-OCR 3.3B Model Released on ModelScope](https://www.reddit.com/r/LocalLLaMA/comments/1ue51uk/unlimitedocr_is_now_on_modelscope_a_33b/) ⭐️ 8.0/10

Unlimited-OCR, a 3.3B parameter multilingual OCR model with MIT license, is now available on ModelScope, supporting full-document parsing across single images, multi-page documents, and PDFs. This model offers a practical, open-source solution for end-to-end document parsing, reducing reliance on commercial OCR services and enabling local deployment for sensitive data. It features a 32K output length for long OCR sequences, supports both base and gundam image modes for different layouts, and integrates with Transformers inference and SGLang serving for OpenAI-compatible streaming requests.

reddit · r/LocalLLaMA · /u/Sporeboss · Jun 24, 05:53

**Background**: OCR (Optical Character Recognition) converts images of text into machine-readable text. Traditional OCR often processes cropped regions, while full-document parsing handles entire pages or documents at once. ModelScope is a platform that provides model-as-a-service for AI models.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.23050">Abstract page for arXiv paper 2606.23050: Unlimited OCR Works</a></li>
<li><a href="https://huggingface.co/baidu/Unlimited-OCR/blob/main/modeling_unlimitedocr.py">modeling _unlimitedocr.py · baidu/ Unlimited - OCR at main</a></li>
<li><a href="https://github.com/modelscope/modelscope">GitHub - modelscope/modelscope: ModelScope: bring the notion of Model-as-a-Service to life. · GitHub</a></li>

</ul>
</details>

**Discussion**: The Reddit community on r/LocalLLaMA expressed enthusiasm for the MIT license and the model's potential for local deployment, with some users discussing its performance compared to DeepSeek-OCR and commercial alternatives.

**Tags**: `#OCR`, `#multilingual`, `#document parsing`, `#open source`, `#AI model`

---

<a id="item-13"></a>
## [20x Speedup for GLM5.2 on GH200 via Model Hacks](https://www.reddit.com/r/LocalLLaMA/comments/1uedlas/i_did_some_model_hacks_and_got_glm52_from_about/) ⭐️ 8.0/10

A Reddit user merged the MTP head from Z.ai's GLM-5.2-FP8 repo with CyanKiwi's AWQ quantized weights and patched vLLM, achieving over 50 tok/s (up from 2.5 tok/s) on a dual-Grace-Hopper system. This demonstrates that significant inference speedups are possible through model-level optimizations like MTP grafting and quantization, enabling large 744B-parameter models to run efficiently on specialized hardware. The merged model uses AWQ quantization for the base weights and FP8 for the MTP head, with a custom vLLM patch to handle the modified architecture; best-case throughput reached ~55 tok/s at 4x concurrency.

reddit · r/LocalLLaMA · /u/Reddactor · Jun 24, 13:30

**Background**: GLM-5.2 is a 744B-parameter open-weight model with 40B active parameters and a 1M-token context window, developed by Z.ai. vLLM is a high-throughput inference engine for LLMs. Multi-Token Prediction (MTP) uses draft heads to predict multiple tokens ahead, improving inference speed.

<details><summary>References</summary>
<ul>
<li><a href="https://registry.ollama.ai/library/glm-5.2">GLM - 5 . 2 is Z.ai’s flagship model for the era of long-horizon tasks.</a></li>
<li><a href="https://github.com/vllm-project/vllm">GitHub - vllm-project/vllm: A high-throughput and memory ... vLLM vllm | A high-throughput and memory-efficient inference and ... Welcome to vLLM! — vLLM vllm-project/vllm | DeepWiki vLLM - Wikipedia</a></li>
<li><a href="https://xhinker.medium.com/the-new-mtp-merge-to-llama-cpp-6203518cb888">The New MTP Merge to llama.cpp has a bug, and Solution to walk around it</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#inference optimization`, `#vLLM`, `#model hacking`, `#GPU`

---

<a id="item-14"></a>
## [AMD Strix Halo NPU Now Usable with ROCm Hybrid Mode](https://www.reddit.com/r/LocalLLaMA/comments/1uegdu0/big_news_for_amd_strix_halo_owners/) ⭐️ 8.0/10

AMD Strix Halo NPU is now usable with ROCm, enabling a hybrid mode that combines the NPU and iGPU for faster LLM inference. This was made possible through the Lemonade app and AMD's updated ROCm software stack. This unlocks the full potential of Strix Halo hardware for LLM inference, addressing a long-standing gap where the NPU was largely unused. Owners can now achieve faster prompt processing and better overall performance by leveraging both the NPU and iGPU. The hybrid mode uses the NPU for prompt processing and the iGPU for token generation, leveraging each component's strengths. Users can test this via the Lemonade app, which provides a bare-bones GUI for sanity-checking hybrid models.

reddit · r/LocalLLaMA · /u/CSEliot · Jun 24, 15:16

**Background**: AMD Strix Halo (Ryzen AI MAX+ 395) is a powerful APU with an integrated NPU (XDNA2) and RDNA 3.5 iGPU. Previously, the NPU was not accessible via ROCm, limiting its use for LLM inference. ROCm is AMD's open-source GPU compute platform, and FastFlowLM is a framework that optimizes LLM inference for NPU accelerators.

<details><summary>References</summary>
<ul>
<li><a href="https://www.compute-market.com/blog/strix-halo-mini-pc-local-ai-2026">Strix Halo Mini PCs for AI — 128GB, 40 TOPS NPU 2026</a></li>
<li><a href="https://rocm.docs.amd.com/en/latest/how-to/rocm-for-ai/inference/llm-inference-frameworks.html">LLM inference frameworks — ROCm Documentation</a></li>
<li><a href="https://fastflowlm.com/docs/models/">Models · FastFlowLM</a></li>

</ul>
</details>

**Discussion**: The community is excited about this development, with users praising the progress in AMD's software ecosystem. Some express interest in MTP-supported hybrid models and hope for more community contributions on Hugging Face.

**Tags**: `#AMD`, `#NPU`, `#ROCm`, `#LLM`, `#hybrid inference`

---

<a id="item-15"></a>
## [Qwen Releases 35B MoE World Model for Agent Simulation](https://www.reddit.com/r/LocalLLaMA/comments/1ue5149/qwenagentworld35ba3b_a_3bactive_moe_trained_to/) ⭐️ 8.0/10

Qwen released Qwen-AgentWorld-35B-A3B, a 35-billion-parameter Mixture-of-Experts model with only 3 billion active parameters per token, trained as a language world model to simulate agent-environment interactions across seven domains including MCP, terminal, software engineering, Android, web, and OS GUI. This model enables efficient offline simulation of agent environments, reducing the need for costly real-time tool execution during training and evaluation, which could accelerate development of general-purpose AI agents. The model uses a Mixture-of-Experts architecture with 35B total parameters but only ~3B active per token, making it computationally efficient. It is designed to predict the next environment observation given action history, supporting domains like MCP tool calling, terminal commands, software engineering tasks, Android and web interactions, and OS GUI operations.

reddit · r/LocalLLaMA · /u/nikhilprasanth · Jun 24, 05:52

**Background**: A world model predicts how an environment will change in response to an agent's actions, enabling planning and reasoning without direct interaction. Mixture-of-Experts (MoE) models use multiple specialized sub-networks (experts) and activate only a subset per input, balancing high capacity with computational efficiency. The Model Context Protocol (MCP) is an open standard for connecting AI agents to external tools and data sources.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.24597">[2606.24597] Qwen-AgentWorld: Language World Models for ...</a></li>
<li><a href="https://github.com/QwenLM/Qwen-AgentWorld/tree/main">GitHub - QwenLM/Qwen-AgentWorld: Qwen-AgentWorld: Language ...</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion highlights the novelty of using a compact MoE for environment simulation, with some users debating the practical trade-offs between model size and simulation fidelity. Others express interest in using the model for synthetic data generation and offline agent evaluation.

**Tags**: `#MoE`, `#agent simulation`, `#world model`, `#Qwen`, `#tool use`

---

<a id="item-16"></a>
## [US Bill Mandates Location Tracking for Advanced AI Chips](https://www.reddit.com/r/LocalLLaMA/comments/1ue2fd7/seems_this_community_might_have_missed_it_bill/) ⭐️ 8.0/10

The Chip Security Act, which would require location-tracking mechanisms for America's most advanced AI chips, has gained support from half a dozen companies and passed the House Foreign Affairs Committee unanimously. This bill could restrict access to high-end AI chips for local LLM development and deployment, especially if chips are tracked and potentially blocked from reaching unauthorized users or regions. The bill mandates GPS-style location tracking on exported advanced AI chips to prevent smuggling to China, and has garnered support from tracking technology companies but faces opposition from semiconductor giants.

reddit · r/LocalLLaMA · /u/alex20_202020 · Jun 24, 03:35

**Background**: The US has been tightening export controls on advanced semiconductors to prevent China from acquiring chips used for AI and military applications. The Chip Security Act introduces a novel approach by requiring physical location tracking mechanisms embedded in the chips themselves, going beyond traditional export licensing.

<details><summary>References</summary>
<ul>
<li><a href="https://startupfortune.com/congress-wants-to-put-a-gps-tracker-on-every-nvidia-chip-that-leaves-the-country/">Congress wants to put a GPS tracker on every Nvidia chip that ...</a></li>
<li><a href="https://www.usindustrynews.com/en/articles/ai-chip-location-tracking-bill-semiconductor-export-control">AI Chip Location Tracking Act: The Industrial Logic and Game ...</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed concerns about the bill's impact on hardware availability for local LLM development, with some questioning the feasibility and privacy implications of mandatory chip tracking.

**Tags**: `#AI chips`, `#regulation`, `#hardware`, `#LLM deployment`, `#policy`

---

<a id="item-17"></a>
## [RubyLLM: Unified Ruby Framework for Major AI Providers](https://rubyllm.com/) ⭐️ 7.0/10

RubyLLM is a Ruby framework that provides a unified interface for major AI providers, enabling developers to build chatbots, AI agents, RAG applications, and more with a single, elegant API. This framework simplifies AI integration in Ruby, making it accessible to a broader developer community and reducing vendor lock-in. Its positive reception and production use indicate it fills a significant gap in the Ruby ecosystem. RubyLLM supports multiple AI providers including OpenAI, Anthropic, Google, and xAI, with features like streaming, tools, embeddings, and structured output. However, users have noted challenges with observability and cache reliability, particularly for providers like xAI that only support the completions API.

hackernews · HN RSS · Jun 24, 14:41 · [Discussion](https://news.ycombinator.com/item?id=48660711)

**Background**: RubyLLM is an open-source library that abstracts away the differences between various AI provider APIs, offering a Ruby-idiomatic interface. It includes a model registry that validates models and routes requests correctly. The framework aims to balance ease of use with flexibility, similar to Vercel's AI SDK for JavaScript.

<details><summary>References</summary>
<ul>
<li><a href="https://rubyllm.com/">RubyLLM | One beautiful Ruby framework for all major AI providers ...</a></li>
<li><a href="https://www.reddit.com/r/rails/comments/1j8lpnt/rubyllm_10/">RubyLLM 1.0 : r/rails - Reddit</a></li>
<li><a href="https://rubyllm.com/models/">Model Registry - RubyLLM</a></li>

</ul>
</details>

**Discussion**: Community feedback is largely positive, praising RubyLLM's elegance and ease of use, with several users reporting production use. However, some users highlight limitations in observability and caching, particularly for xAI, and note that retries can delete underlying model history, making traceability difficult.

**Tags**: `#Ruby`, `#AI framework`, `#LLM`, `#open source`, `#developer tools`

---

<a id="item-18"></a>
## [Bunny DNS Goes Free, Challenges Cloudflare](https://bunny.net/blog/were-making-bunny-dns-free/) ⭐️ 7.0/10

Bunny DNS has eliminated all query fees and now offers free DNS hosting for up to 500 domains per account, with no query limits or hidden charges. This move positions Bunny DNS as a compelling EU-based alternative to Cloudflare, especially for users concerned about data privacy and EU tech sovereignty. The free tier includes smart records and health monitoring, features typically reserved for enterprise plans elsewhere. Bunny.net is a private company with only a small $6 million funding round in 2022.

hackernews · HN RSS · Jun 24, 08:50 · [Discussion](https://news.ycombinator.com/item?id=48657030)

**Background**: DNS (Domain Name System) translates human-readable domain names into IP addresses. Most DNS providers charge based on the number of queries, which can become costly for high-traffic sites. Bunny DNS previously had query fees but has now removed them entirely.

<details><summary>References</summary>
<ul>
<li><a href="https://bunny.net/blog/were-making-bunny-dns-free/">We’re making Bunny DNS free</a></li>
<li><a href="https://bunny.net/dns/">Bunny DNS | The #1 Scriptable DNS Platform | bunny.net</a></li>

</ul>
</details>

**Discussion**: Commenters generally welcomed the move, with some praising it as a needed EU alternative to Cloudflare. However, others raised concerns about Bunny's privacy policy and lack of support for the Vary header, which limits its use as a Vercel alternative.

**Tags**: `#DNS`, `#cloud`, `#EU tech`, `#free service`, `#privacy`

---

<a id="item-19"></a>
## [Nub: A Bun-like toolkit for Node.js](https://github.com/nubjs/nub) ⭐️ 7.0/10

Nub is a new open-source toolkit that adds TypeScript transpilation, module resolution, and polyfills to Node.js via preload hooks, without forking the runtime. It offers a pragmatic alternative to Bun by enhancing stock Node.js with modern tooling, allowing developers to adopt features incrementally without migrating to a new runtime. Nub uses oxc-powered transpilation via a Node-API add-on and registers module resolution hooks, injecting polyfills for APIs like Worker and Temporal.

hackernews · HN RSS · Jun 24, 14:14 · [Discussion](https://news.ycombinator.com/item?id=48660267)

**Background**: Bun is an all-in-one JavaScript runtime that includes a bundler, test runner, and package manager, but requires switching from Node.js. Node.js supports preload hooks via --require, which allow injecting code before application startup. Nub leverages this mechanism to add Bun-like features without replacing Node.

<details><summary>References</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all - in - one JavaScript runtime</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/ bun : Incredibly fast JavaScript runtime, bundler, test...</a></li>

</ul>
</details>

**Discussion**: The community praised Nub's approach of building on existing Node APIs rather than rewriting from scratch. Users reported successful migrations with zero issues, and the author explained design choices like using oxc for transpilation.

**Tags**: `#Node.js`, `#TypeScript`, `#tooling`, `#JavaScript`, `#open source`

---

<a id="item-20"></a>
## [Hobby OS Runs Windows Games via Wine](https://astral-os.org/posts/2026/04/03/wine-on-astral.html) ⭐️ 7.0/10

The developer of Astral OS, a hobby operating system, successfully ported Wine to run Windows games on their OS, demonstrating the feasibility of legacy compatibility in a custom kernel environment. This achievement shows that hobby OSes can potentially run mainstream Windows software, but it also highlights the heavy burden of implementing legacy interfaces, which may limit innovation in new operating systems. The port required implementing Linux system call compatibility and GPU driver support for the hobby OS, though the blog post did not detail how GPU drivers were obtained, leaving a significant technical gap.

hackernews · HN RSS · Jun 24, 14:38 · [Discussion](https://news.ycombinator.com/item?id=48660671)

**Background**: Wine is a free and open-source compatibility layer that allows Windows applications to run on Unix-like operating systems by translating Windows API calls into POSIX calls. Hobby OSes are personal projects built for learning or experimentation, often lacking the extensive driver and application ecosystems of mainstream OSes like Linux or Windows.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wine_(software)">Wine (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hobbyist_operating_system">Hobbyist operating system - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed both admiration and concern: some praised the technical feat, while others noted the despair of having to implement legacy interfaces, and one questioned how GPU drivers were handled, as the blog omitted that detail.

**Tags**: `#hobby OS`, `#Wine`, `#gaming`, `#compatibility`, `#systems programming`

---