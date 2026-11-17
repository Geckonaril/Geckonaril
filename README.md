<!-- Profile README — Geckonaril -->

# Serhat Burak

**Computer Engineering · Ankara University**  

AI Security / LLM Security / Security Research

I work on the security of language-model systems, with a particular interest in indirect prompt injection, trust boundaries, and empirical security evaluation. My current research focuses on building reproducible datasets and evaluation workflows that test how models respond to adversarial instructions embedded in otherwise legitimate content.

[LinkedIn](https://linkedin.com/in/serhatburakozbakir) · [itch.io](https://geckonaril.itch.io)

---

### Current research

#### [TR–EN Indirect Prompt Injection Dataset](https://github.com/meryem-ciftci/LLM-Prompt-Injection-Dataset)

*A bilingual benchmark for studying indirect prompt injection detection and attack success.*

The project creates labeled Turkish/English examples from real source text, then evaluates whether language models follow unauthorized instructions hidden in untrusted material such as retrieved passages and documents. Its design separates **what the text says** from **where the instruction comes from**.

| Pilot v1 (0.2.0) | Research setup |
| :--- | :--- |
| **600 records** | 150 matched, four-member families |
| **2 languages** | Turkish and English |
| **7 attack goals** | Including task hijacking, content manipulation, and prompt leakage |
| **3,750 model responses** | Five local models evaluated in EXP-004b |

**What the research examines**

- **Trust-boundary reasoning:** comparing injected untrusted content with authorized versions of the same instructions.
- **Dataset engineering:** reproducible generation, injection-span labels, provenance tracking, and source-disjoint splits.
- **Security evaluation:** deterministic attack-success checks, paired controls, false positives, and task utility.
- **Experimental factors:** attack goals, obfuscation, language, context length, and injection position.

[Explore the repository](https://github.com/meryem-ciftci/LLM-Prompt-Injection-Dataset) · [Dataset documentation](https://github.com/meryem-ciftci/LLM-Prompt-Injection-Dataset/blob/main/docs/DATA_CARD.md) · [Pilot evaluation report](https://github.com/meryem-ciftci/LLM-Prompt-Injection-Dataset/blob/main/evaluation/reports/EXP-004b.md)

<sub>Pilot figures refer to the repository's v1 release and EXP-004b, not a continually updated live benchmark. Results are exploratory and specific to the evaluated models and conditions.</sub>

---

### Research interests

| Primary | Adjacent areas |
| :--- | :--- |
| LLM security and prompt injection | Multi-agent authorization and delegation |
| Adversarial evaluation and benchmarks | Secure software and system design |
| Dataset generation and data quality | Reverse engineering and low-level systems |
| Trust boundaries and instruction provenance | Local model infrastructure and experimentation |

### Technical work

**Languages:** Python · C · C++ · Assembly (x86-64 / RISC-V)  
**Research workflows:** dataset pipelines · JSONL / structured data · automated validation · experiment tracking · local LLM evaluation (Ollama)  
**Other experience:** networking · AWS (Lambda, S3, RDS, EC2) · game development and pixel art

I also explore how **authorization drift and prompt injection** can interact in multi-agent systems. This is an ongoing research direction rather than a completed benchmark.

### GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Geckonaril&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a9c7f2&text_color=c4cedc&icon_color=8faed8&ring_color=8faed8&include_all_commits=true&rank_icon=github">
    <img height="165" alt="GitHub statistics" src="https://github-readme-stats.vercel.app/api?username=Geckonaril&show_icons=true&hide_border=true&bg_color=ffffff&title_color=274b75&text_color=334155&icon_color=527aaa&include_all_commits=true&rank_icon=github">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Geckonaril&layout=compact&langs_count=6&hide_border=true&bg_color=0d1117&title_color=a9c7f2&text_color=c4cedc">
    <img height="165" alt="Most-used languages across public GitHub repositories" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Geckonaril&layout=compact&langs_count=6&hide_border=true&bg_color=ffffff&title_color=274b75&text_color=334155">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Geckonaril&bg_color=0d1117&color=a9c7f2&line=7297c8&point=c8daef&area=true&area_color=7297c8&hide_border=true&custom_title=Contribution%20activity">
    <img width="100%" alt="Recent contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=Geckonaril&bg_color=ffffff&color=274b75&line=527aaa&point=274b75&area=true&area_color=527aaa&hide_border=true&custom_title=Contribution%20activity">
  </picture>
</p>

<sub>Statistics are generated by third-party services and reflect the repositories and events available to them. Language percentages are based on repository code, not proficiency.</sub>

---

<sub>Interested in systems engineering, security, or research? Connect via <a href="https://linkedin.com/in/serhatburakozbakir">LinkedIn</a>.</sub>
