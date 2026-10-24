---
layout: single
author_profile: false
title: "Junkai Chen's Homepage"
---

{% capture intro %}
I am a Ph.D. student at [Singapore Management University](https://www.smu.edu.sg/), advised by [Prof. David Lo](http://www.mysmu.edu/faculty/davidlo/).

I build, enhance, and evaluate LLMs and agents for their efficacy, reliability, and security. My work has received wide recognition, including two [ACM SIGSOFT Distinguished Paper Awards](https://www2.sigsoft.org/awards/distinguishedpaper/) and one [ACL SAC Highlight Award](https://lnkd.in/p/gU7ucP4z), and has attracted interest from various entities like [新智元](https://mp.weixin.qq.com/s/zHVWchAOONC2Y75PvYNDBg), [alphaXiv](https://x.com/junkaichen2000/status/2047932312353124392), and [JetBrains](https://huggingface.co/datasets/JetBrains-Research/REval).
{% endcapture %}
{% include profile-header.html intro=intro %}

***

# News

- <span class="news-date">2026-09</span> Our paper received an <button type="button" class="photo-link" data-photo-full="{{ '/assets/images/award-ase2026.jpg' | relative_url }}" data-photo-size="1800x1200" data-photo-alt="Receiving the ACM SIGSOFT Distinguished Paper Award at ASE 2026" data-photo-caption="Second from left: my advisor David Lo. Third from left: me." aria-haspopup="dialog">ACM SIGSOFT Distinguished Paper Award</button> at ASE 2026.
- <span class="news-date">Pinned</span> We released [the first benchmark](https://github.com/iCSawyer/SecureVibeBench) for security in vibe coding of LLM agents. 

{% comment %} Older news (only the latest three are shown):
- [2026-04-07] Two papers about AI and cybersecurity were accepted by ACL 2026.
- 📌 Check latest SE conference papers at [**SEConfPaperList**](https://github.com/iCSawyer/SEConfPaperList)~.
{% endcomment %}


***

# Awards
- <span class="award-highlight">ACM SIGSOFT Distinguished Paper Award</span> at ASE 2026, ACM SIGSOFT, 2026
- <span class="award-highlight">ACM SIGSOFT Distinguished Paper Award</span> at ICSE 2024, ACM SIGSOFT, 2024
- <span class="award-highlight">SAC Highlight Award</span> at ACL 2026, ACL, 2026
- National Scholarship, Ministry of Education of P.R.C., 2024
- SMU SCIS Research Excellence Award, SMU, 2025, 2026
- ACM SIGSOFT CAPS Travel Grant, 2025

***

# Publications

{% comment %}26.07{% endcomment %}
- [**SecureVibeBench: Benchmarking Secure Vibe Coding of AI Agents via Reconstructing Vulnerability-Introducing Scenarios**](https://aclanthology.org/2026.acl-long.1107/)<br/>
  <strong>Junkai Chen<span class="eq-contrib">*</span></strong>, Huihui Huang<span class="eq-contrib">*</span>, Yunbo Lyu, Junwen An, Jieke Shi, Chengran Yang, Ting Zhang, Haoye Tian, Yikun Li, Zhenhao Li, Xin Zhou, Xing Hu, and David Lo.<br/>
  <span class="pub-venue">ACL 2026</span> <span class="pub-venue-full">The 64th Annual Meeting of the Association for Computational Linguistics</span><br/>
  <a class="pub-link" href="https://www.arxiv.org/pdf/2509.22097" target="_blank">PDF</a><a class="pub-link" href="https://github.com/iCSawyer/SecureVibeBench" target="_blank">Code</a><a class="pub-link" href="https://huggingface.co/datasets/iCSawyer/SecureVibeBench" target="_blank">Dataset</a>
  {% comment %} <span class="pub-note">SecureVibeBench is the first SWE-bench-level benchmark for secure vibe coding.</span> {% endcomment %}

{% comment %}25.09?{% endcomment %}
- [**Reasoning Runtime Behavior of a Program with LLM: How Far Are We?**](https://dl.acm.org/doi/10.1109/ICSE55347.2025.00012)<br/>
  <strong>Junkai Chen<span class="eq-contrib">*</span></strong>, Zhiyuan Pan<span class="eq-contrib">*</span>, Xing Hu, Zhenhao Li, Ge Li, and Xin Xia.<br/>
  <span class="pub-venue">ICSE 2025</span> <span class="pub-venue-full">The 47th IEEE/ACM International Conference on Software Engineering</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2403.16437.pdf" target="_blank">PDF</a><a class="pub-link" href="https://github.com/r-eval/r-eval.github.io" target="_blank">Code</a><a class="pub-link" href="https://huggingface.co/datasets/JetBrains-Research/REval" target="_blank">Dataset</a><br/>
  {% comment %} <span class="pub-note">Number 60 in <a href="https://jiekeshi.tech/topnotchse/se_ntop100.html" target="_blank">Normalized Top-100 Software Engineering Conference Papers</a> of all time.<br/>🤗 Included by <a href="https://huggingface.co/datasets/JetBrains-Research/REval">JetBrains-Research</a>.</span> {% endcomment %}
  <span class="pub-note">Adopted by <a href="https://huggingface.co/datasets/JetBrains-Research/REval">JetBrains-Research</a>.</span>

{% comment %}24.04{% endcomment %}
- [**Code Search is All You Need? Improving Code Suggestions with Code Search**](https://dl.acm.org/doi/10.1145/3597503.3639085)<br/>
  **Junkai Chen**, Xing Hu, Zhenhao Li, Cuiyun Gao, Xin Xia, and David Lo.<br/>
  <span class="pub-venue">ICSE 2024</span> <span class="pub-venue-full">The 46th IEEE/ACM International Conference on Software Engineering</span><br/>
  <a class="pub-link" href="https://ginolzh.github.io/papers/ICSE2024_Code_Suggestion.pdf" target="_blank">PDF</a><a class="pub-link" href="https://github.com/iCSawyer/CodeSuggestion" target="_blank">Code</a><br/>
  <span class="pub-note"><a href="https://www2.sigsoft.org/awards/distinguishedpaper/" target="_blank">ACM SIGSOFT Distinguished Paper Award</a>.</span>
  {% comment %} acm showcase on kudos??? {% endcomment %}

{% comment %}26.10?{% endcomment %}
- [**AgentExecutor: Partial Code Execution via Agentic Context Generation**](https://arxiv.org/abs/2608.05959)<br/>
  <strong>Junkai Chen</strong>, Chengran Yang, Xing Hu, Zhenhao Li, Xin Xia, and David Lo.<br/>
  <span class="pub-venue">ASE 2026</span> <span class="pub-venue-full">The 41st IEEE/ACM International Conference on Automated Software Engineering</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2608.05959" target="_blank">PDF</a><a class="pub-link" href="https://github.com/iCSawyer/AgentExecutor" target="_blank">Code</a>
  <span class="pub-note"><a href="https://www2.sigsoft.org/awards/distinguishedpaper/" target="_blank">ACM SIGSOFT Distinguished Paper Award</a>.</span>

{% comment %}26.07{% endcomment %}
- [**SeCuRepair: Semantics-Aligned, Curriculum-Driven, and Reasoning-Enhanced Vulnerability Repair Framework**](https://arxiv.org/abs/2510.01002)<br/>
  Chengran Yang, Ting Zhang, Jinfeng Jiang, Xin Zhou, Haoye Tian, Mingzhe Du, Jieke Shi, **Junkai Chen**, Yikun Li, Eng Lieh Ouh, Lwin Khin Shar, and David Lo.<br/>
  <span class="pub-venue">ACL 2026</span> <span class="pub-venue-full">The 64th Annual Meeting of the Association for Computational Linguistics</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2510.01002" target="_blank">PDF</a>
  <span class="pub-note">Oral; <a href="https://lnkd.in/p/gU7ucP4z" target="_blank">SAC Highlight Award</a>.</span>

{% comment %}?{% endcomment %}
- [**R2Vul: Learning to Reason about Software Vulnerabilities with Reinforcement Learning and Structured Reasoning Distillation**](https://arxiv.org/abs/2504.04699)<br/>
  Martin Weyssow, Chengran Yang, <strong>Junkai Chen</strong>, Ratnadira Widyasari, Ting Zhang, Huihui Huang, Huu Hung Nguyen, Yan Naing Tun, Tan Bui, Yikun Li, Ang Han Wei, Frank Liauw, Eng Lieh Ouh, Lwin Khin Shar, and David Lo.<br/>
  {% comment %} Martin Weyssow, Chengran Yang, <strong>Junkai Chen<span class="corresp">📧</span></strong>, Ratnadira Widyasari, Ting Zhang, Huihui Huang, Huu Hung Nguyen, Yan Naing Tun, Tan Bui, Yikun Li, Ang Han Wei, Frank Liauw, Eng Lieh Ouh, Lwin Khin Shar, and David Lo.<br/> {% endcomment %}
  <span class="pub-venue">Preprint</span> <span class="pub-venue-full"></span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2504.04699" target="_blank">PDF</a><a class="pub-link" href="https://github.com/martin-wey/R2Vul" target="_blank">Code</a>
  <span class="pub-note">Top-liked in software engineering at <a href="https://www.alphaxiv.org/?subcategories=%5B%22software-engineering%22%5D&sort=Likes">alphaXiv</a>.</span>

{% comment %}25.12{% endcomment %}
- [**Assessing and Advancing Benchmarks for Evaluating Large Language Models in Software Engineering Tasks**](https://dl.acm.org/doi/10.1145/3786771)<br/>
  Xing Hu, Feifei Niu, **Junkai Chen**, Xin Zhou, Junwei Zhang, Junda He, Xin Xia, and David Lo.<br/>
  <span class="pub-venue">TOSEM 2026</span> <span class="pub-venue-full">ACM Transactions on Software Engineering and Methodology</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2505.08903" target="_blank">PDF</a><a class="pub-link" href="https://github.com/LLM4SE-Benchmarks/LLM4SE-Benchmarks" target="_blank">Code</a><br/>
  <span class="pub-note">Featured by <a href="https://mp.weixin.qq.com/s/zHVWchAOONC2Y75PvYNDBg">新智元</a> (in Chinese).</span>

<details class="pub-section" markdown="block">
  <summary class="pub-toggle"><span class="pub-toggle__more">Show all publications</span><span class="pub-toggle__less">Show less</span></summary>

{% comment %}25.06{% endcomment %}
- [**Understanding Practitioners' Expectations on Clear Code Review Comments**](https://dl.acm.org/doi/10.1145/3728931)<br/>
  <strong>Junkai Chen<span class="eq-contrib">*</span></strong>, Zhenhao Li<span class="eq-contrib">*</span>, Qiheng Mao, Xing Hu, Kui Liu, and Xin Xia.<br/>
  <span class="pub-venue">ISSTA 2025</span> <span class="pub-venue-full">The 34th ACM SIGSOFT International Symposium on Software Testing and Analysis</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2410.06515" target="_blank">PDF</a><a class="pub-link" href="https://github.com/iCSawyer/ClearCRC" target="_blank">Code</a>

{% comment %}26.03{% endcomment %}
- [**NLPerturbator: Studying the Robustness of Code LLMs to Natural Language Variations**](https://dl.acm.org/doi/10.1145/3745764)<br/>
  <strong>Junkai Chen<span class="eq-contrib">*</span></strong>, Zhenhao Li<span class="eq-contrib">*</span>, Xing Hu, and Xin Xia.<br/>
  <span class="pub-venue">TOSEM 2025</span> <span class="pub-venue-full">ACM Transactions on Software Engineering and Methodology</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2406.19783" target="_blank">PDF</a><a class="pub-link" href="https://github.com/iCSawyer/NLPerturbator" target="_blank">Code</a>

- [**SWE-NFI: Studying and Benchmarking Coding Agents for Non-Functional Improvements**](https://arxiv.org/abs/2607.27409)<br/>
  Pengyu Xue, He Yang Yuan, Xin Wang, **Junkai Chen**, Haonan Zhang, Boyuan Chen, Zishuo Ding, Zhenhao Li, and Weiyi Shang.<br/>
  <span class="pub-venue">Preprint</span> <span class="pub-venue-full"></span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2607.27409" target="_blank">PDF</a>

- [**Trustworthy Runtime Error Healing in Real-World Repositories: A Benchmark and Guardrail**](https://arxiv.org/abs/2609.39086)<br/>
  Gou Tan, Pengfei Chen, Zhensu Sun, Jieke Shi, **Junkai Chen**, Ting Zhang, Weifeng Sun, Junda He, Shuai Liang, Chuanfu Zhang, Lwin Khin Shar, and David Lo.<br/>
  <span class="pub-venue">Preprint</span> <span class="pub-venue-full"></span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2609.39086" target="_blank">PDF</a>

- [**Debt Behind the AI Boom: A Large-Scale Empirical Study of AI-Generated Code in the Wild**](https://arxiv.org/abs/2603.28592)<br/>
  Yue Liu, Ratnadira Widyasari, Yanjie Zhao, Ivana Clairine Irsan, **Junkai Chen**, and David Lo.<br/>
  <span class="pub-venue">Preprint</span> <span class="pub-venue-full"></span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2603.28592" target="_blank">PDF</a>

- [**AgentSZZ: Teaching the LLM Agent to Play Detective with Bug-Inducing Commits**](https://arxiv.org/abs/2604.02665)<br/>
  Yunbo Lyu, Jieke Shi, Hong Jin Kang, Ratnadira Widyasari, Junda He, Yuqing Niu, Chengran Yang, **Junkai Chen**, Zhou Yang, Julia Lawall, and David Lo.<br/>
  <span class="pub-venue">Preprint</span> <span class="pub-venue-full"></span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2604.02665" target="_blank">PDF</a>

{% comment %}26.10?{% endcomment %}
- [**An Empirical Study of Speculative Decoding on Software Engineering Tasks**](https://www.arxiv.org/abs/2604.26469)<br/>
  Yijia Li, **Junkai Chen**, Xing Hu, and Xin Xia.<br/>
  <span class="pub-venue">ISSTA 2026</span> <span class="pub-venue-full">The 35th ACM SIGSOFT International Symposium on Software Testing and Analysis</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2604.26469" target="_blank">PDF</a>

{% comment %}26.07{% endcomment %}
- [**PenForge: On-the-Fly Expert Agent Construction for Automated Penetration Testing**](https://dl.acm.org/doi/10.1145/3786582.3786814)<br/>
  Huihui Huang, Jieke Shi, **Junkai Chen**, Ting Zhang, Yikun Li, Chengran Yang, Eng Lieh Ouh, Lwin Khin Shar, and David Lo.<br/>
  <span class="pub-venue">ICSE 2026 (NIER)</span> <span class="pub-venue-full">The 48th IEEE/ACM International Conference on Software Engineering, New Ideas and Emerging Results</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2601.06910" target="_blank">PDF</a><a class="pub-link" href="https://github.com/huanghuihui0904/PenForge" target="_blank">Code</a>

- [**Out of Distribution, Out of Luck: How Well Can LLMs Trained on Vulnerability Datasets Detect Top 25 CWE Weaknesses?**](https://arxiv.org/abs/2507.21817)<br/>
  Yikun Li, Ngoc Tan Bui, Ting Zhang, Chengran Yang, Xin Zhou, Martin Weyssow, Jinfeng Jiang, **Junkai Chen**, Huihui Huang, Huu Hung Nguyen, Chiok Yew Ho, Jie Tan, Ruiyin Li, Yide Yin, Han Wei Ang, Frank Liauw, Eng Lieh Ouh, Lwin Khin Shar, and David Lo.<br/>
  <span class="pub-venue">ICSE 2026</span> <span class="pub-venue-full">The 48th IEEE/ACM International Conference on Software Engineering</span><br/>
  <a class="pub-link" href="https://arxiv.org/pdf/2507.21817" target="_blank">PDF</a><a class="pub-link" href="https://github.com/yikun-li/TitanVul-BenchVul" target="_blank">Code</a>

</details>

***


# Services
### Program Committee / Journal Reviewer
- 2026: TSE, NeurIPS, TOSEM, IST, ICSE (Shadow PC), MSR (Junior PC), DL4C@NeurIPS, EASE (AI Models / Data Track), Communications AI & Computing
- 2025: MSR (Junior PC), DL4C@ICLR, LTB@ICPE

### Others
- External Reviewer: ICSE, FSE, ASE, TOSEM, MSR, FCS, JoS (Chinese), etc.
- Student Volunteer: Internetware 2023


{% comment %} ***/

# Experiences
- Ph.D. Student, Singapore Management University, Aug. 2025 - present
- Research Engineer, Singapore Management University, Jan. 2025 - present
    - Advisor: [David Lo](http://www.mysmu.edu/faculty/davidlo/)
- M.E. in Software Engineering, Zhejiang University, Sep. 2022 - Jun. 2025
    - Supervisor: [Xing Hu](https://xing-hu.github.io/), Advisor: [Xin Xia](https://xin-xia.github.io/)
- B.E. in Computer Science, Southwest Jiaotong University, Sep. 2018 - Jun. 2022 {% endcomment %}
