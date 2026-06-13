<div align="center">

# Nazmus Sakib

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=6F42C1&center=true&vCenter=true&width=780&lines=ML+Security+Researcher;Adversarial+ML+for+Network+Intrusion+Detection;The+attack+must+work+on+a+real+network%2C+not+just+on+paper)](https://github.com/sakib2588)

[![Papers](https://img.shields.io/badge/Papers-ICCIT_2026_+_IEEE_Access-6f42c1?style=for-the-badge)](#research)
[![Focus](https://img.shields.io/badge/Focus-Adversarial_ML_for_NIDS-c0392b?style=for-the-badge)](#research)
[![Open to](https://img.shields.io/badge/Open_to-Security_/_ML_Internship-2ecc71?style=for-the-badge)](#lets-connect)

</div>

---

## Research

**Adversarial robustness in ML-based Network Intrusion Detection Systems.**

Most published ML-NIDS robustness numbers are tested against feature-space attacks that cannot survive a real network stack. I build reproducible evaluation frameworks using realistic gray-box adversary models and problem-space constraints — so a claimed "attack" must prove it could actually happen on the wire.

```mermaid
flowchart LR
    accTitle: The Realizability Gap in Adversarial NIDS
    accDescr: Feature-space attacks succeed mathematically, but most fail when forced through real TCP/IP constraints. This research measures and closes that gap.

    attack["🧮 Feature-space attack"] --> gate{"Survives real TCP/IP stack?"}
    gate -->|"most do not"| gap["❌ Realizability gap"]
    gate -->|"few do"| real["✅ Real threat"]
    gap --> work["🔬 Measure + close the gap"]
    real --> work

    classDef q fill:#fef9c3,stroke:#ca8a04,stroke-width:2px,color:#713f12
    classDef bad fill:#fde2e2,stroke:#c0392b,stroke-width:2px,color:#5a1212
    classDef good fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d
    classDef focus fill:#ede9fe,stroke:#6f42c1,stroke-width:2px,color:#3b1f6b

    class gate q
    class gap bad
    class real good
    class attack,work focus
```

- **Datasets:** UNSW-NB15 · CICIDS2017 · NSL-KDD
- **Core idea:** the *realizability gap* between math-space and packet-space attacks
- **Method:** gray-box threat taxonomy + problem-space validation + adaptive co-evolution benchmark

---

## Featured Work

| Project | What it is | Status |
|---|---|---|
| **Wazuh SOC Home Lab** | 5-node SIEM with real attack simulation, custom detection rules, incident playbooks. | Building |
| **IDS Edge Compression** | Knowledge distillation + pruning + INT8 quantization for ML intrusion detection on edge. NF-UQ-NIDS-v2, 72.7M flows. | IEEE Access — under review |
| **ML-Based IDS** | Conference work on ML intrusion detection. | ICCIT 2026 — submitting |

```mermaid
flowchart LR
    accTitle: Wazuh SOC Home Lab Architecture
    accDescr: A five-node security monitoring lab. A Raspberry Pi runs Suricata network detection while agents on Linux and Windows hosts report to a central Wazuh SIEM server.

    net["🌐 Home Network"] --> rpi["🛡️ Raspberry Pi 4 · Suricata NIDS"]
    rpi --> sw["🔀 Switch"]
    sw --> linux["🐧 PC · Linux Agent"]
    sw --> win["🪟 PC · Windows Agent"]
    rpi -. "network alerts" .-> siem["📊 Laptop · Wazuh SIEM"]
    linux --> siem
    win --> siem

    classDef sensor fill:#fde2e2,stroke:#c0392b,stroke-width:2px,color:#5a1212
    classDef agent fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a5f
    classDef core fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d
    classDef infra fill:#f3f4f6,stroke:#6b7280,stroke-width:1px,color:#1f2937

    class rpi sensor
    class linux,win agent
    class siem core
    class net,sw infra
```

---

## Toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Wazuh](https://img.shields.io/badge/Wazuh-3A7AFE?style=flat-square&logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF4136?style=flat-square&logo=suricata&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Domains:** Adversarial ML · SIEM & Log Analysis · Network Intrusion Detection · Threat Detection Engineering · Model Compression

---

## Certifications

- Google Cybersecurity Professional Certificate
- EC-Council Network Defense Essentials
- Linux for LFCA (LearnQuest)
- Stanford / DeepLearning.AI — Supervised Machine Learning

---

## Currently

- Building out the Wazuh SOC lab to a full detection-engineering portfolio
- Writing my thesis framework on problem-space adversarial NIDS evaluation
- Polishing two papers toward submission
- Final-year BSc CSE @ American International University-Bangladesh

---

<div align="center">

### Contribution Snake

![Contribution snake](https://raw.githubusercontent.com/sakib2588/sakib2588/output/github-snake-dark.svg)

### GitHub Activity

![Stats](https://github-readme-stats.vercel.app/api?username=sakib2588&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Streak](https://streak-stats.demolab.com?user=sakib2588&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sakib2588&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

## Let's Connect

I'm looking for an **IT / Security / ML internship** (Dhaka, Bangladesh). If you work on detection, threat intel, or applied ML — let's talk.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nazmus-sakib-2bb1522a6/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nazmussakib2858@gmail.com)

<div align="center">
<sub>Adversarial ML for NIDS · The attack has to work on a real network, not just on paper.</sub>
</div>
