# 🤖 CLLMSP — LLM Security Professional

[🏠 Profile](https://github.com/RochaCrypt) · [📚 Catalog](../README.md) · <img src="https://img.shields.io/badge/📊_Grc-0d1117?style=flat-square&labelColor=0d1117" alt="grc"/>

> Securing LLM applications, mapped to the OWASP LLM Top 10. <img src="https://img.shields.io/badge/✔_I_hold_this-ff2e4c?style=flat-square&labelColor=0d1117" alt="held"/>

## 🔎 What it is

A certification focused on the security of applications built on large language models — the new attack surface created by AI features, agents and RAG pipelines.

## 🎯 What it validates

- Prompt injection, direct and indirect
- Data leakage and system-prompt leakage
- Insecure output handling
- Agent risks and excessive agency

## 🧠 Key concepts & definitions

| Term | Definition |
| :--- | :--- |
| **Prompt injection** | Malicious instructions in input that hijack the model's behaviour |
| **Indirect injection** | Injection hidden in documents, emails or web pages the model reads |
| **Excessive agency** | Giving an agent too many tools or permissions |
| **RAG** | Retrieval-Augmented Generation — feeding external data into prompts |
| **System prompt leakage** | Exposing hidden instructions, sometimes containing secrets |

## 🗺️ Mind map

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#3a0008','primaryTextColor':'#ffffff','primaryBorderColor':'#ff2e4c','lineColor':'#ff2e4c','fontSize':'15px','cScale0':'#ff2e4c','cScale1':'#8b1a2b','cScale2':'#c9243a','cScale3':'#5c0a18','cScale4':'#e0213d','cScale5':'#3a0008','cScale6':'#a3162e','cScale7':'#6e0f1f','cScale8':'#ff5c73','cScale9':'#4a0d17','cScale10':'#b81f36','cScale11':'#2a0006','cScaleLabel0':'#ffffff','cScaleLabel1':'#ffffff','cScaleLabel2':'#ffffff','cScaleLabel3':'#ffffff','cScaleLabel4':'#ffffff','cScaleLabel5':'#ffffff','cScaleLabel6':'#ffffff','cScaleLabel7':'#ffffff','cScaleLabel8':'#ffffff','cScaleLabel9':'#ffffff','cScaleLabel10':'#ffffff','cScaleLabel11':'#ffffff'}}}%%
mindmap
  root((LLM Security))
    Input Attacks
      Prompt injection
      System prompt leak
    Data Risks
      Disclosure
      Poisoning
    Output Risks
      Improper handling
      Misinformation
    Agent Risks
      Excessive agency
    Platform
      Supply chain
      Unbounded consumption```

## 📌 Fast facts

| | |
| :--- | :--- |
| Focus | OWASP Top 10 for LLM Applications |
| Level | Intermediate ⭐⭐ |
| Format | Knowledge exam |
| Relevance | Fast-growing attack surface |

## 🔥 In the field

- An LLM app is still a web app — classic testing applies before AI-specific tests.
- Indirect prompt injection is the sleeper risk when apps read untrusted content.

## 🔗 Official

- [OWASP GenAI Security Project](https://genai.owasp.org/)

---

<div align="center">

<a href="../README.md"><img src="https://img.shields.io/badge/📚_Full_catalog-0d1117?style=for-the-badge&logoColor=white" alt="Catalog"/></a>
<a href="https://github.com/RochaCrypt"><img src="https://img.shields.io/badge/🏠_Back_to_profile-ff2e4c?style=for-the-badge&logo=github&logoColor=white" alt="Profile"/></a>

</div>
