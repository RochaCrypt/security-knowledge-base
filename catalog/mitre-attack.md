# 🎛️ MITRE ATT&CK

[🏠 Profile](https://github.com/RochaCrypt) · [📚 Catalog](../README.md) · <img src="https://img.shields.io/badge/🧭_Framework-0d1117?style=flat-square&labelColor=0d1117" alt="framework"/>

> A knowledge base of real-world adversary tactics and techniques.

## 🔎 What it is

A free, globally used matrix that catalogues how attackers behave — organised as tactics (their goals) and techniques (how they achieve them), based on observed real-world activity.

## 🎯 What it validates

- Maps attacker behaviour across 14 enterprise tactics
- Gives every technique a shared ID (e.g. T1059)
- Powers detection engineering and threat hunting
- Enables red/blue teams to speak the same language

## 🧠 Key concepts & definitions

| Term | Definition |
| :--- | :--- |
| **Tactic** | The attacker's goal in a phase (e.g. Persistence) |
| **Technique** | How the goal is achieved (e.g. Scheduled Task) |
| **Sub-technique** | A more specific variation of a technique |
| **Procedure** | A specific real-world implementation by a group |
| **Coverage mapping** | Checking which techniques your detections actually catch |

## 🗺️ Mind map

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#3a0008','primaryTextColor':'#ffffff','primaryBorderColor':'#ff2e4c','lineColor':'#ff2e4c','fontSize':'15px','cScale0':'#ff2e4c','cScale1':'#8b1a2b','cScale2':'#c9243a','cScale3':'#5c0a18','cScale4':'#e0213d','cScale5':'#3a0008','cScale6':'#a3162e','cScale7':'#6e0f1f','cScale8':'#ff5c73','cScale9':'#4a0d17','cScale10':'#b81f36','cScale11':'#2a0006','cScaleLabel0':'#ffffff','cScaleLabel1':'#ffffff','cScaleLabel2':'#ffffff','cScaleLabel3':'#ffffff','cScaleLabel4':'#ffffff','cScaleLabel5':'#ffffff','cScaleLabel6':'#ffffff','cScaleLabel7':'#ffffff','cScaleLabel8':'#ffffff','cScaleLabel9':'#ffffff','cScaleLabel10':'#ffffff','cScaleLabel11':'#ffffff'}}}%%
mindmap
  root((ATT&CK))
    Initial Access
    Execution
    Persistence
    Privilege Escalation
    Defense Evasion
    Credential Access
    Discovery
    Lateral Movement
    Collection
    Command and Control
    Exfiltration
    Impact
```

## 📌 Fast facts

| | |
| :--- | :--- |
| Maintained by | MITRE |
| Type | Free knowledge base |
| Enterprise tactics | 14 |
| Use | Detection, hunting, red/blue teaming |

## 🔥 In the field

- Mapping detections to ATT&CK turns 'we have alerts' into 'we cover these behaviours'.
- The shared IDs make red-team reports directly actionable for the blue team.

## 🔗 Official

- [MITRE ATT&CK](https://attack.mitre.org/)

---

<div align="center">

<a href="../README.md"><img src="https://img.shields.io/badge/📚_Full_catalog-0d1117?style=for-the-badge&logoColor=white" alt="Catalog"/></a>
<a href="https://github.com/RochaCrypt"><img src="https://img.shields.io/badge/🏠_Back_to_profile-ff2e4c?style=for-the-badge&logo=github&logoColor=white" alt="Profile"/></a>

</div>
