<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║   ██╗  ██╗ █████╗ ██████╗ ███████╗██╗  ██╗                  ║
║   ██║  ██║██╔══██╗██╔══██╗██╔════╝██║  ██║                  ║
║   ███████║███████║██████╔╝███████╗███████║                  ║
║   ██╔══██║██╔══██║██╔══██╗╚════██║██╔══██║                  ║
║   ██║  ██║██║  ██║██║  ██║███████║██║  ██║                  ║
║   ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝                  ║
║                                                               ║
║             G U L R A J A N I                                 ║
║      Computer Engineer  |  Cyber Security                     ║
╚═══════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=Zero+Trust+%7C+Never+Trust%2C+Always+Verify;Network+Security+%7C+Penetration+Testing;Docker+%7C+Micro-Segmentation+%7C+IAM;Ethical+Hacker+in+Training+%F0%9F%94%90;Building+Secure+Systems+from+Scratch)](https://git.io/typing-svg)

</div>

---

<img align="right" width="380" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="contribution snake"/>

## `whoami`

```bash
$ cat /etc/profile.d/harsh.sh

NAME="Harsh Gulrajani"
DEGREE="B.E. Computer Engineering"
SPECIALIZATION="Cyber Security"
LOCATION="India"
STATUS="Final Year Student"
CURRENTLY_BUILDING="Zero-Trust Security Architecture"
LEARNING=["Red Team", "Cloud Security", "DevSecOps"]
OPEN_TO="Internships & Collaborations"
```

<br clear="right"/>

---

## `cat skills.txt`

<div align="center">

### 🛡️ Security
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)

### 🐳 DevSecOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### 📊 Monitoring & Analysis
![Grafana](https://img.shields.io/badge/Grafana-F2F4F9?style=for-the-badge&logo=grafana&logoColor=orange)
![Prometheus](https://img.shields.io/badge/Prometheus-000000?style=for-the-badge&logo=prometheus&labelColor=000000)

</div>

---

## `ls -la projects/`

<div align="center">

| Project | Description | Tech Stack | Status |
|--------|-------------|------------|--------|
| 🎰 **[Zero-Trust-Cage](https://github.com/MR-harshgulrajani/zero-trust-cage)** | Casino-themed Zero Trust Architecture with micro-segmentation, Keycloak MFA, dynamic quarantine | Docker · Flask · Keycloak · PostgreSQL · Grafana | ✅ Live |
| 🔍 **[IDS-Python](https://github.com/MR-harshgulrajani/idsPython)** | Network Intrusion Detection System — real-time packet analysis & anomaly detection | Python · Scapy · ML | ✅ Complete |
| 🌐 **[Phishing-URL-Detection](https://github.com/MR-harshgulrajani/phishing-url-detection)** | ML-based system to detect malicious URLs with feature extraction pipeline | Python · Scikit-learn · NLP | ✅ Complete |
| 🔀 **[Network-Routing](https://github.com/MR-harshgulrajani/networkRouting)** | Network routing algorithms implementation — Dijkstra, Bellman-Ford | C · Data Structures | ✅ Complete |

</div>

---

## `cat zero-trust-architecture.md` ⭐ Featured Project

```
┌─────────────────────────────────────────────────────────────┐
│              ZERO-TRUST CAGE ARCHITECTURE                   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  [INTERNET] → [DMZ 172.20.0.0/24]                          │
│                    │                                        │
│              web-server  attacker-box                       │
│                    │          ✗ BLOCKED                     │
│              [APP 172.21.0.0/24]                            │
│                    │                                        │
│              gaming-app (Flask + Zero Trust)                │
│                    │                                        │
│        [THE CAGE 172.22.0.0/24] ← internal:true            │
│                    │                                        │
│              gaming-database (PostgreSQL)                   │
│              ⚠️  NO EXTERNAL ROUTE EXISTS                   │
│                                                             │
│  ✓  Identity Verification via Keycloak (every request)     │
│  ✓  Micro-Segmentation (6 isolated Docker networks)        │
│  ✓  Audit Logging (every access logged to DB)              │
│  ✓  Fail Closed Policy (deny all when IdP is down)         │
│  ✓  Dynamic Quarantine (real-time container isolation)      │
└─────────────────────────────────────────────────────────────┘
```

---

## `netstat -stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=MR-harshgulrajani&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00FF41&icon_color=00FF41&text_color=ffffff"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MR-harshgulrajani&layout=compact&langs_count=8&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00FF41&text_color=ffffff"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=MR-harshgulrajani&theme=matrix&hide_border=true&background=0D1117&stroke=00FF41&ring=00FF41&fire=FF6600&currStreakLabel=00FF41&sideLabels=00FF41&dates=FFFFFF)](https://git.io/streak-stats)

</div>

---

## `grep -r "certifications" ./`

```python
certifications = {
    "pursuing": [
        "CEH - Certified Ethical Hacker",
        "CompTIA Security+",
    ],
    "completed": [
        "B.E. Computer Engineering - Cyber Security Specialization",
    ],
    "concepts_mastered": [
        "Zero Trust Architecture",
        "Network Intrusion Detection",
        "Phishing Detection (ML)",
        "Docker Micro-Segmentation",
        "Identity & Access Management (Keycloak)",
        "SIEM / Security Monitoring (Grafana + Prometheus)",
    ]
}
```

---

## `ping connect.sh`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MR-harshgulrajani)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshgulrajani)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshgulrajani@email.com)

</div>

---

<div align="center">

```bash
$ echo "Thanks for visiting — stay secure out there 🔐"
Thanks for visiting — stay secure out there 🔐

$ logout
Connection closed.
```

![Visitor Count](https://komarev.com/ghpvc/?username=MR-harshgulrajani&color=00ff41&style=flat-square&label=PROFILE+VIEWS)

</div>
