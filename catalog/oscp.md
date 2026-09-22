# 🗡️ OSCP — OffSec Certified Professional

[🏠 Profile](https://github.com/RochaCrypt) · [📚 Catalog](../README.md) · <img src="https://img.shields.io/badge/🔴_Offensive-0d1117?style=flat-square&labelColor=0d1117" alt="offensive"/>

> OffSec · the hands-on benchmark for penetration testers.

## 🔎 What it is

A fully practical, proctored certification (course PEN-200). You compromise real machines in a 24h exam and write a professional report. Widely regarded as the credibility bar for pentest roles.

## 🎯 What it validates

- Manual exploitation without automated tools
- Linux and Windows privilege escalation
- Active Directory attacks (mandatory since 2024)
- Pivoting, tunneling and reporting

## 🧠 Key concepts & definitions

| Term | Definition |
| :--- | :--- |
| **Assumed breach** | AD set starts with a valid domain user, simulating an initial foothold |
| **Kerberoasting** | Requesting service tickets to crack service-account passwords offline |
| **Pass-the-Hash** | Authenticating with an NTLM hash instead of a plaintext password |
| **Pivoting** | Using a compromised host to reach networks you can't touch directly |
| **proof.txt / local.txt** | Flag files proving user and admin/root access |

## 🗺️ Mind map

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#3a0008','primaryTextColor':'#ffffff','primaryBorderColor':'#ff2e4c','lineColor':'#ff2e4c','fontSize':'15px','cScale0':'#ff2e4c','cScale1':'#8b1a2b','cScale2':'#c9243a','cScale3':'#5c0a18','cScale4':'#e0213d','cScale5':'#3a0008','cScale6':'#a3162e','cScale7':'#6e0f1f','cScale8':'#ff5c73','cScale9':'#4a0d17','cScale10':'#b81f36','cScale11':'#2a0006','cScaleLabel0':'#ffffff','cScaleLabel1':'#ffffff','cScaleLabel2':'#ffffff','cScaleLabel3':'#ffffff','cScaleLabel4':'#ffffff','cScaleLabel5':'#ffffff','cScaleLabel6':'#ffffff','cScaleLabel7':'#ffffff','cScaleLabel8':'#ffffff','cScaleLabel9':'#ffffff','cScaleLabel10':'#ffffff','cScaleLabel11':'#ffffff'}}}%%
mindmap
  root((OSCP))
    Recon
      Nmap
      Web enum
    Foothold
      Web attacks
      Public exploits
    Privesc
      Linux
      Windows
    Active Directory
      BloodHound
      Kerberoast
      Lateral movement
    Pivoting
    Report```

## 📌 Fast facts

| | |
| :--- | :--- |
| Issuer | OffSec |
| Level | Advanced ⭐⭐⭐⭐ |
| Format | ~24h practical + 24h report · 70/100 to pass |
| Rules | Metasploit on 1 target · no AI tools |

## 🔥 In the field

- Enumeration is the whole game; being stuck almost always means something wasn't looked at closely.
- AD is 40% of the exam and most of real internal engagements.

## 🔗 Official

- [OffSec OSCP / PEN-200](https://www.offsec.com/courses/pen-200/)

---

<div align="center">

<a href="../README.md"><img src="https://img.shields.io/badge/📚_Full_catalog-0d1117?style=for-the-badge&logoColor=white" alt="Catalog"/></a>
<a href="https://github.com/RochaCrypt"><img src="https://img.shields.io/badge/🏠_Back_to_profile-ff2e4c?style=for-the-badge&logo=github&logoColor=white" alt="Profile"/></a>

</div>
