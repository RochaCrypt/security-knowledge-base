<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:3a0008,100:ff2e4c&height=180&section=header&text=Security%20Knowledge%20Base&fontSize=36&fontColor=ffffff&desc=Mind%20maps%20%26%20study%20notes%20from%20real-world%20offensive%20security&descSize=15&descAlignY=66" width="100%" alt="Security Knowledge Base"/>

<img src="https://img.shields.io/github/stars/RochaCrypt/security-knowledge-base?style=flat-square&color=ff2e4c&labelColor=0d1117" alt="Stars"/>
<img src="https://img.shields.io/github/last-commit/RochaCrypt/security-knowledge-base?style=flat-square&color=ff2e4c&labelColor=0d1117" alt="Last commit"/>
<img src="https://img.shields.io/badge/license-CC_BY--SA_4.0-ff2e4c?style=flat-square&labelColor=0d1117" alt="License"/>

</div>

```console
root@rochacrypt:~# ls ~/knowledge-base
certs/     ceh  ccfa  cllmsp  fortinet-fca  ehe-nde
roadmaps/  oscp  security-plus  pentest-plus  cissp  cism
```

Visual mind maps and condensed notes for the certifications I hold — built to be **studied, not just read**. Each map links the exam topics to how they show up in real engagements.

## 🗺️ The Big Picture

```mermaid
mindmap
  root((Offensive Security))
    Attack
      CEH
        Recon and Scanning
        System Hacking
        Web and Cloud
      EHE
        Hacking Fundamentals
    Defend
      CCFA
        Falcon EDR
        Policies and RTR
      NDE
        Network Defence
      Fortinet FCA
        Firewall Fundamentals
    AI Security
      CLLMSP
        OWASP LLM Top 10
        Prompt Injection
```

## 🧭 Certification Roadmap

```mermaid
flowchart LR
    A[🛡️ Security+<br/>foundation] --> B[🎯 PenTest+]
    A --> C[⚔️ CEH ✅]
    B --> D[🗡️ OSCP]
    C --> D
    A --> E[🏛️ CISSP]
    E --> F[📊 CISM]
    style C fill:#3a0008,stroke:#ff2e4c,color:#ffffff
    style D fill:#3a0008,stroke:#ff2e4c,color:#ffffff
    style A fill:#0d1117,stroke:#8b949e,color:#ffffff
    style B fill:#0d1117,stroke:#8b949e,color:#ffffff
    style E fill:#0d1117,stroke:#8b949e,color:#ffffff
    style F fill:#0d1117,stroke:#8b949e,color:#ffffff
```

<sub>Technical track on top, management track below. ✅ = certification I hold.</sub>

## ✅ My Certifications — study maps from experience

| Map | Focus | Level |
| :--- | :--- | :--- |
| [**CEH** — Certified Ethical Hacker](./certs/ceh.md) | Full offensive lifecycle, 20 modules | ⭐⭐⭐ |
| [**CCFA** — CrowdStrike Falcon Administrator](./certs/ccfa.md) | EDR administration, policies, RTR | ⭐⭐⭐ |
| [**CLLMSP** — LLM Security](./certs/cllmsp.md) | OWASP Top 10 for LLM Applications | ⭐⭐ |
| [**Fortinet FCA**](./certs/fortinet-fca.md) | Security fundamentals & FortiGate basics | ⭐ |
| [**EHE & NDE** — EC-Council Essentials](./certs/ehe-nde.md) | Attack & defence foundations | ⭐ |

## 📖 Industry Roadmaps — popular certifications mapped

| Map | Track | Format |
| :--- | :--- | :--- |
| [**OSCP**](./roadmaps/oscp.md) — OffSec Certified Professional | 🔴 Offensive | 24h practical + report |
| [**PenTest+**](./roadmaps/pentest-plus.md) — CompTIA | 🔴 Offensive | Multiple choice + PBQs |
| [**Security+**](./roadmaps/security-plus.md) — CompTIA | ⚪ Foundation | Multiple choice + PBQs |
| [**CISSP**](./roadmaps/cissp.md) — ISC2 | 🔵 Management | Adaptive, 8 domains |
| [**CISM**](./roadmaps/cism.md) — ISACA | 🔵 Management | Multiple choice, 4 domains |

> Industry roadmaps are study maps built from each certification's public outline — not certifications I claim to hold.

## 🧭 How to Use

1. **Start with the mind map** — get the shape of the domain before the details.
2. **Read the "In the field" notes** — see how each topic appears in real work.
3. **Tick the checklist** — fork the repo and track your own progress.

## 💬 Engage

- ⭐ **Star** the repo if it helped you study.
- 💡 Spotted a gap or error? Open an [issue](../../issues) or a pull request.
- 🗣️ Questions about a topic or exam? Start a [discussion](../../discussions).

> ⚠️ For education and **authorised testing only**. These notes are my own study material and are not official exam content.
