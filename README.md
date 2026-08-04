# Hi, I’m Aaron Chakraborty

**AI/ML Engineer · Security Researcher · B.Tech CSE @ KIIT**

I build AI systems from first principles and test how they fail in the real world. My work sits at the intersection of model architecture, distributed training, AI-agent security, and offensive security.

[Portfolio](https://aaron-631.github.io) · [Resume](https://aaron-631.github.io/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/aaron-chakraborty-309197287) · [Email](mailto:aaronchakraborty631@gmail.com)

## What I work on

- **AI/ML systems:** transformer architecture, Mixture-of-Experts, distributed training, tokenizer design, inference, and adversarial evaluation.
- **AI security:** prompt injection, jailbreaks, data extraction, agent permissions, MCP security, runtime policy enforcement, and reproducible risk reports.
- **Offensive security:** web application testing, reconnaissance, exploitation, traffic analysis, responsible disclosure, and CVSS-based reporting.

## Selected proof

| Area | Evidence |
| --- | --- |
| AI/ML | Designed and trained a **567,068,416-parameter MoE LLM from scratch** on a single 20 GB A100 · 30,000 steps · 86/86 tests passing |
| Security | 20+ live-application VAPTs · responsibly disclosed and remediated a reflected XSS in Yatra’s production Diya AI chatbot |
| Competition | **AIR 45** at Pentathon 2025 · top 0.90% globally · 48-hour national CTF |
| Leadership | IoT Lab Coordinator at KIIT · 30+ member technical community · CTF organiser and mentor |
| Credentials | eJPTv2 — 91% · SAP Certified Backend Developer · SSB TES-51 — AIR 83 |

## Featured projects

### [Project Argus](https://github.com/aaron-631/PROJECT-ARGUS)

An AI-agent security platform with a local-first release gate and a runtime enforcement gateway.

- 27 canonical rules covering code, tools, permissions, secrets, MCP servers, and network configuration.
- Read-only MCP probing, reproducible JSON/Markdown reports, prompt-injection blocking, approval gates, response redaction, and hash-chained audit logs.
- 53 tests plus formatting, lint, type, and schema checks enforced in CI.

### VantaLLM

**Private repository · technical walkthrough available on request**

An end-to-end decoder-only Mixture-of-Experts training and serving system built during my AI/ML research internship at SwiftSafe.

- 567M parameters, 16 experts with top-2 routing, GQA, RoPE, RMSNorm, SwiGLU, and batched grouped-GEMM.
- PyTorch, DDP, DeepSpeed ZeRO-2/3, FastAPI, SSE, and a custom 151,003-token BPE tokenizer trained on security corpora.
- Bit-identical KV-cache decoding, live inference tests, and a real 30,000-step run on a 20 GB A100.

### [ReconForge](https://github.com/aaron-631/ReconForge)

Recon automation combining Nmap, Rustscan, FFUF, Amass, and `jq`, with wildcard-DNS detection, FFUF calibration, and structured HTML/Markdown reporting.

### [Search Arena](https://search-arena.vercel.app) · [source](https://github.com/aaron-631/search-arena)

A live visual playground for six classical AI search algorithms, with D3.js search-tree playback, Firebase-backed leaderboards, CI/CD deployment, and an Android build through Capacitor.

## Experience

- **Technology Apprentice · DBS Tech India SEED** — Jun 2026–present
- **AI/ML Research Intern · SwiftSafe** — Mar 2026–Jun 2026
- **Lab Coordinator · IoT Lab, KIIT** — Sep 2024–Aug 2026
- **Security Testing Intern · Panacea Infosec** — May 2024–Jul 2024
- **Cyber Security & AI/ML Intern · The Red Users** — Dec 2024–Jan 2025

## Core stack

`Python` `PyTorch` `DeepSpeed` `Transformers` `FastAPI` `C/C++` `Java` `TypeScript` `React` `D3.js` `SQL` `Bash/Linux` `Docker` `GitHub Actions` `MCP` `Firebase` `Burp Suite` `Nmap` `FFUF` `Wireshark`

## Currently

- Working in the DBS Tech India SEED apprenticeship programme.
- Moving VantaLLM toward a releasable cybersecurity-focused base model.
- Building and validating Argus as a practical AI-agent security control plane.
- Open to AI/ML engineering, security engineering, and AI security research opportunities for the 2026–27 placement cycle.

## Education

**B.Tech in Computer Science and Engineering** — Kalinga Institute of Industrial Technology, Bhubaneswar · 2023–2027 · **CGPA 9.42**

## Let’s connect

If you are working on AI infrastructure, model evaluation, application security, or AI-agent safety, I’d be glad to talk.

[Email Aaron](mailto:aaronchakraborty631@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aaron-chakraborty-309197287) · [Portfolio](https://aaron-631.github.io)
