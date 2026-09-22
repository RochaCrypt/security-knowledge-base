# 🌡️ CVSS — Common Vulnerability Scoring System

[🏠 Profile](https://github.com/RochaCrypt) · [📚 Catalog](../README.md) · <img src="https://img.shields.io/badge/🧭_Framework-0d1117?style=flat-square&labelColor=0d1117" alt="framework"/>

> FIRST · a standard way to score vulnerability severity.

## 🔎 What it is

An open standard for rating the severity of vulnerabilities on a 0–10 scale. It provides a consistent, comparable score so teams can prioritise remediation across many findings.

## 🎯 What it validates

- Scores vulnerability severity 0–10
- Breaks severity into measurable metrics
- Enables consistent prioritisation
- Underlies most vulnerability reports

## 🧠 Key concepts & definitions

| Term | Definition |
| :--- | :--- |
| **Base score** | Intrinsic severity independent of environment |
| **Temporal/Threat** | Adjusts for exploit maturity over time |
| **Environmental** | Adjusts for your specific context |
| **Attack vector** | How the flaw is reached (network, local, physical) |
| **Severity rating** | None, Low, Medium, High, Critical bands |

## 🗺️ Mind map

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#3a0008','primaryTextColor':'#ffffff','primaryBorderColor':'#ff2e4c','lineColor':'#ff2e4c','fontSize':'15px','cScale0':'#ff2e4c','cScale1':'#8b1a2b','cScale2':'#c9243a','cScale3':'#5c0a18','cScale4':'#e0213d','cScale5':'#3a0008','cScale6':'#a3162e','cScale7':'#6e0f1f','cScale8':'#ff5c73','cScale9':'#4a0d17','cScale10':'#b81f36','cScale11':'#2a0006','cScaleLabel0':'#ffffff','cScaleLabel1':'#ffffff','cScaleLabel2':'#ffffff','cScaleLabel3':'#ffffff','cScaleLabel4':'#ffffff','cScaleLabel5':'#ffffff','cScaleLabel6':'#ffffff','cScaleLabel7':'#ffffff','cScaleLabel8':'#ffffff','cScaleLabel9':'#ffffff','cScaleLabel10':'#ffffff','cScaleLabel11':'#ffffff'}}}%%
mindmap
  root((CVSS))
    Base
      Exploitability
      Impact
    Threat
      Exploit maturity
    Environmental
      Context
    Score
      0 to 10
      Severity bands
```

## 📌 Fast facts

| | |
| :--- | :--- |
| Maintained by | FIRST |
| Version | 4.0 |
| Range | 0.0–10.0 |
| Use | Prioritising remediation |

## 🔥 In the field

- A raw CVSS score isn't priority: a 9.8 no one can reach may matter less than a 6 that's exposed.
- Environmental metrics are underused — they make the score fit *your* risk.

## 🔗 Official

- [FIRST CVSS](https://www.first.org/cvss/)

---

<div align="center">

<a href="../README.md"><img src="https://img.shields.io/badge/📚_Full_catalog-0d1117?style=for-the-badge&logoColor=white" alt="Catalog"/></a>
<a href="https://github.com/RochaCrypt"><img src="https://img.shields.io/badge/🏠_Back_to_profile-ff2e4c?style=for-the-badge&logo=github&logoColor=white" alt="Profile"/></a>

</div>
