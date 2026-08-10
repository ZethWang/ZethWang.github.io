---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# About Me

I am **Zihan Wang** (王子涵), an incoming **M.S. student** in Artificial Intelligence at <a href="https://www.sigs.tsinghua.edu.cn/en/"><em class="entity-mention" style="--entity-color: #7B61C9"><img class="entity-logo" src="/images/logos/thu.png" alt="">Tsinghua University</em></a> (Shenzhen), advised by [Prof. Yujiu Yang](https://www.sigs.tsinghua.edu.cn/yyj_en/main.psp). I received my B.Eng. in Computer Science and Technology from <a href="https://en.xjtu.edu.cn/"><em class="entity-mention" style="--entity-color: #D45A5A"><img class="entity-logo" src="/images/logos/xjtu.svg" alt="">Xi'an Jiaotong University</em></a>.

My research centers on **NLP / Large Language Models (LLMs)**, with a focus on building **intrinsically motivated, self-evolving, and reasoning-capable agents** — particularly around **agentic reinforcement learning, self-evolving agents, coding / GUI agents, and environment scaling**.

🐈 I am always open to discussion and collaboration, and I am currently looking for internship opportunities. Feel free to reach out via email or WeChat: <span class="wechat-id">wishme25</span>

<span class='anchor' id='news'></span>

# 🔥 News

<div class="scrollable-area">
  <ul>
    <li class="news-item"><span class="news-date">2026.09</span><span class="news-body">🎓 Incoming M.S. student in AI at <b>Tsinghua University</b> (Shenzhen).</span></li>
    <li class="news-item"><span class="news-date">2026.08</span><span class="news-body">🚀 Released <a href="https://arxiv.org/abs/2608.05987">AgentOPSD</a>, a recursive self-distillation method for agentic RL, featured as 🤗 HF Daily Paper #1!</span></li>
    <li class="news-item"><span class="news-date">2026.07</span><span class="news-body">🚀 Released <a href="https://arxiv.org/abs/2607.26784">SkillRise</a> on cross-task skill evolution for agentic RL.</span></li>
    <li class="news-item"><span class="news-date">2026.05</span><span class="news-body">🎉 <a href="https://arxiv.org/abs/2603.11863">CreativeBench</a> was accepted to <b>ACL 2026</b>!</span></li>
    <li class="news-item"><span class="news-date">2026.05</span><span class="news-body">🔥🔥 Our new work <a href="https://arxiv.org/abs/2605.15155">SDAR</a> was released, featured as 🤗 HF Daily Paper #2!</span></li>
    <li class="news-item"><span class="news-date">2025.05</span><span class="news-body">🎉 <a href="https://arxiv.org/abs/2503.06708">Alignment for Efficient Tool Calling</a> was accepted to <b>EMNLP 2025 (Main)</b>!</span></li>
    <li class="news-item"><span class="news-date">2025.05</span><span class="news-body">🎉 <a href="https://arxiv.org/abs/2412.04141">Reducing Tool Hallucination via Reliability Alignment</a> was accepted to <b>ICML 2025</b>!</span></li>
  </ul>
</div>

<span class='anchor' id='publications'></span>

# 📝 Selected Publications

<small>* Equal contribution. † Corresponding author. See my [full list](https://scholar.google.com/citations?user=eToPcFsAAAAJ&hl=en) on Google Scholar.</small>

## 🤖 Agentic RL & Skill Evolution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-preprint">Preprint</div><img src='pub_images/agentopsd.png' alt="AgentOPSD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AgentOPSD: Recursive Self-Distillation for Agentic Reinforcement Learning](https://arxiv.org/abs/2608.05987)

**<u>Zi-Han Wang</u>**, Zhengxi Lu, Zhiyuan Yao, Jinyang Wu, Jie Wu, Zhengzhou Cai, Yueqing Sun, Ziang Ye, Linji Hao, Qi Gu, Xunliang Cai, Yongliang Shen, Yujiu Yang

[Paper](https://arxiv.org/abs/2608.05987){:.btn-link .btn-paper} [<img src='./images/svgs/huggingface_logo.svg' alt="">HF](https://huggingface.co/papers/2608.05987){:.btn-link .btn-hf} [Code](https://github.com/ZethWang/AgentOPSD){:.btn-link .btn-code} <a href="#" class="btn-link btn-bib" data-bib-key="wang2026agentopsd">BIB</a>
<span class="paper-note">🤗 HuggingFace Daily Paper #1</span>
- A critic-free, recursive self-distillation method that provides turn-level credit assignment for long-horizon, multi-turn agentic reinforcement learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-preprint">Preprint</div><img src='pub_images/skillrise.png' alt="SkillRise" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SkillRise: Agentic Reinforcement Learning for Cross-Task Skill Evolution](https://arxiv.org/abs/2607.26784)

Zhiyuan Yao, Yuxin Chen, Zhengxi Lu, Zishan Xu, Yueqing Sun, Yifu Guo, Yuquan Lu, Zhengzhou Cai, Kangning Zhang, Zhuowen Han, **<u>Zi-Han Wang</u>**, Ziang Ye, Qi Gu, Xunliang Cai, Weiwen Liu, Yongliang Shen

[Paper](https://arxiv.org/abs/2607.26784){:.btn-link .btn-paper} [<img src='./images/svgs/huggingface_logo.svg' alt="">HF](https://huggingface.co/papers/2607.26784){:.btn-link .btn-hf} <a href="#" class="btn-link btn-bib" data-bib-key="yao2026skillrise">BIB</a>
- A unified RL framework that learns reusable skills across related tasks by organizing instances into progressively challenging sequences.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-preprint">Preprint</div><img src='pub_images/sdar.png' alt="SDAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SDAR: Self-Distilled Agentic Reinforcement Learning](https://arxiv.org/abs/2605.15155)

Zhengxi Lu, Zhiyuan Yao, Zhuowen Han, **<u>Zi-Han Wang</u>**, Jinyang Wu, Qi Gu, Xunliang Cai, Weiming Lu, Jun Xiao, Yueting Zhuang, Yongliang Shen

[Paper](https://arxiv.org/abs/2605.15155){:.btn-link .btn-paper} [<img src='./images/svgs/huggingface_logo.svg' alt="">HF](https://huggingface.co/papers/2605.15155){:.btn-link .btn-hf} [Code](https://github.com/ZJU-REAL/SDAR){:.btn-link .btn-code} <a href="#" class="btn-link btn-bib" data-bib-key="lu2026sdar">BIB</a>
<span class="paper-note">🤗 HuggingFace Daily Paper #2</span>
- Extends on-policy self-distillation to multi-turn agents, delivering dense token-level guidance on top of coarse trajectory-level rewards.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-preprint">Preprint</div><img src='pub_images/memento.png' alt="Memento" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Memento: Fine-tuning LLM Agents without Fine-tuning LLMs](https://arxiv.org/abs/2508.16153)

Huichi Zhou\*, Yihang Chen\*, Siyuan Guo, Xue Yan, Kin Hei Lee, **<u>Zihan Wang</u>**, Ka Yiu Lee, Guchun Zhang, Kun Shao, Linyi Yang†, Jun Wang†

[Paper](https://arxiv.org/abs/2508.16153){:.btn-link .btn-paper} [<img src='./images/svgs/huggingface_logo.svg' alt="">HF](https://huggingface.co/papers/2508.16153){:.btn-link .btn-hf} [Code](https://github.com/Agent-on-the-Fly/Memento){:.btn-link .btn-code} <a href="#" class="btn-link btn-bib" data-bib-key="zhou2025memento">BIB</a>
- Memory-based online reinforcement learning that lets LLM agents continually adapt from experience without updating the underlying model weights.
</div>
</div>

## 🎨 Machine Creativity & Tool Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-acl">ACL 2026</div><img src='pub_images/creativebench.png' alt="CreativeBench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CreativeBench: Benchmarking and Enhancing Machine Creativity via Self-Evolving Challenges](https://arxiv.org/abs/2603.11863)

**<u>Zi-Han Wang</u>**, Lam Nguyen, Zhengyang Zhao, Mengyue Yang, Chengwei Qin, Yujiu Yang, Linyi Yang

[Paper](https://arxiv.org/abs/2603.11863){:.btn-link .btn-paper} [Homepage](https://zethwang.github.io/creativebench.github.io/){:.btn-link .btn-home} [Code](https://github.com/ZethWang/CreativeBench){:.btn-link .btn-code} <a href="#" class="btn-link btn-bib" data-bib-key="wang2026creativebench">BIB</a>
- A benchmark for machine creativity in code generation — covering combinatorial and exploratory creativity with executable evaluation and the inference-time enhancement strategy EvoRePE.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-acl">EMNLP 2025</div><img src='pub_images/alignment.png' alt="Alignment for Efficient Tool Calling" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Alignment for Efficient Tool Calling of Large Language Models](https://arxiv.org/abs/2503.06708)

Hongshen Xu\*, **<u>Zihan Wang</u>**\*, Zichen Zhu, Lei Pan, Xingyu Chen, Lu Chen, Kai Yu

[Paper](https://arxiv.org/abs/2503.06708){:.btn-link .btn-paper} <a href="#" class="btn-link btn-bib" data-bib-key="xu2025alignment">BIB</a>
- A multi-objective alignment framework that combines probabilistic knowledge-boundary estimation with dynamic decision making to reduce unnecessary tool calls while preserving performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge badge-acl">ICML 2025</div><img src='pub_images/reducing.png' alt="Reducing Tool Hallucination" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reducing Tool Hallucination via Reliability Alignment](https://arxiv.org/abs/2412.04141)

Hongshen Xu, Zichen Zhu, Lei Pan, **<u>Zihan Wang</u>**, Su Zhu, Da Ma, Ruisheng Cao, Lu Chen, Kai Yu

[Paper](https://arxiv.org/abs/2412.04141){:.btn-link .btn-paper} <a href="#" class="btn-link btn-bib" data-bib-key="xu2025reducing">BIB</a>
- Defines and categorizes tool hallucinations (tool selection vs. tool usage) and introduces reliability-oriented alignment for more robust and efficient tool interaction.
</div>
</div>

<span class='anchor' id='internships'></span>

# 💼 Internships
- *Mar. 2026 – Present*: Research Intern at <a href="https://github.com/meituan-longcat"><em class="entity-mention" style="--entity-color: #16A34A"><img class="entity-logo" src="/images/logos/longcat-icon.png" alt="">LongCat Team, Meituan</em></a>, advised by [Qi Gu](https://scholar.google.com/citations?hl=zh-CN&user=s_5-ctUAAAAJ), [Chengcheng Han](https://scholar.google.com/citations?hl=zh-CN&user=kGlQ56YAAAAJ), and [Yueqing Sun](https://scholar.google.com/citations?hl=zh-CN&user=6GyAX-MAAAAJ). Agentic RL, multimodal productivity agents, and environment scaling ([LongCat 2.0](https://longcat.chat/blog/longcat-2.0/)).
- *Aug. 2025 – Feb. 2026*: Research Intern at **Southern University of Science and Technology (SUSTech)**, advised by [Linyi Yang](https://scholar.google.com/citations?user=go3sFxcAAAAJ&hl=zh-CN). AutoResearch / AI Scientist.
- *Feb. 2025 – May 2025*: Research Intern, **Peking University**. LLM pre-training, data selection and mixing.
- *Aug. 2024 – Feb. 2025*: Research Intern, **Shanghai Jiao Tong University**. LLM alignment, tool learning, and tool-use agents.

<span class='anchor' id='honors'></span>

# 🎖 Honors and Awards
- *2024–2025*: Baidu Artificial Intelligence and Big Data Elite Class.
- *2023–2024*: Outstanding Award (Meritorious Winner), Mathematical Contest in Modeling (MCM/ICM).
- *2023–2024*: Provincial First Prize, National College Students' Mathematics Competition.
- *2023–2024*: Outstanding Volunteer Award.
- *2022–2023*: National Scholarship.

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2026.09 - now* (incoming): M.S. in Artificial Intelligence, Tsinghua University (Shenzhen).
- *2022.09 - 2026.07*: B.Eng. in Computer Science and Technology, Xi'an Jiaotong University. GPA **3.97/4.30**, Rank **5/193**.

<span class='anchor' id='services'></span>

# 🧑‍⚖️ Academic Services

### Conference Reviewer
- AAAI 2026.
- ACL Rolling Review (ARR), 2025–2026.
