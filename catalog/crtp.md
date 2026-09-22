# 🏰 CRTP — Certified Red Team Professional

[🏠 Profile](https://github.com/RochaCrypt) · [📚 Catalog](../README.md) · <img src="https://img.shields.io/badge/🔴_Offensive-0d1117?style=flat-square&labelColor=0d1117" alt="offensive"/>

> Altered Security · deep, practical Active Directory attack skills.

## 🔎 What it is

A hands-on certification focused entirely on attacking Active Directory environments using PowerShell and built-in tooling. Highly respected for AD-heavy red-team work.

## 🎯 What it validates

- AD enumeration with PowerShell and BloodHound
- Privilege escalation inside a domain
- Lateral movement and credential theft
- Domain and forest persistence and trust abuse

## 🧠 Key concepts & definitions

| Term | Definition |
| :--- | :--- |
| **Kerberos delegation** | A feature that, when misconfigured, lets attackers impersonate users |
| **Golden Ticket** | A forged Kerberos ticket granting near-unlimited domain access |
| **DCSync** | Abusing replication rights to pull password hashes from a DC |
| **Domain trust** | A relationship between domains that can be abused to cross boundaries |
| **BloodHound** | Tool that maps AD attack paths as a graph |

## 🗺️ Mind map

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#3a0008','primaryTextColor':'#ffffff','primaryBorderColor':'#ff2e4c','lineColor':'#ff2e4c','fontSize':'15px','cScale0':'#ff2e4c','cScale1':'#8b1a2b','cScale2':'#c9243a','cScale3':'#5c0a18','cScale4':'#e0213d','cScale5':'#3a0008','cScale6':'#a3162e','cScale7':'#6e0f1f','cScale8':'#ff5c73','cScale9':'#4a0d17','cScale10':'#b81f36','cScale11':'#2a0006','cScaleLabel0':'#ffffff','cScaleLabel1':'#ffffff','cScaleLabel2':'#ffffff','cScaleLabel3':'#ffffff','cScaleLabel4':'#ffffff','cScaleLabel5':'#ffffff','cScaleLabel6':'#ffffff','cScaleLabel7':'#ffffff','cScaleLabel8':'#ffffff','cScaleLabel9':'#ffffff','cScaleLabel10':'#ffffff','cScaleLabel11':'#ffffff'}}}%%
mindmap
  root((CRTP))
    Enumeration
      PowerShell
      BloodHound
    Privesc
      Local to domain
    Lateral Movement
      PtH
      Delegation abuse
    Persistence
      Golden Ticket
      DCSync
    Trusts
      Cross-domain
      Cross-forest```

## 📌 Fast facts

| | |
| :--- | :--- |
| Issuer | Altered Security |
| Level | Intermediate ⭐⭐⭐ |
| Format | 24h practical + report |
| Focus | Active Directory |

## 🔥 In the field

- AD misconfigurations — not zero-days — are how most internal compromises actually happen.
- Complements OSCP: OSCP is broad, CRTP goes deep on the domain.

## 🔗 Official

- [Altered Security CRTP](https://www.alteredsecurity.com/adlab)

---

<div align="center">

<a href="../README.md"><img src="https://img.shields.io/badge/📚_Full_catalog-0d1117?style=for-the-badge&logoColor=white" alt="Catalog"/></a>
<a href="https://github.com/RochaCrypt"><img src="https://img.shields.io/badge/🏠_Back_to_profile-ff2e4c?style=for-the-badge&logo=github&logoColor=white" alt="Profile"/></a>

</div>
