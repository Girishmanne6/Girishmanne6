<div align="center">

<svg width="100%" viewBox="0 0 1200 340" xmlns="http://www.w3.org/2000/svg" style="display:block">
  <defs>
    <radialGradient id="bg" cx="50%" cy="60%" r="70%">
      <stop offset="0%" stop-color="#0d0520"/>
      <stop offset="100%" stop-color="#050510"/>
    </radialGradient>
    <radialGradient id="orb1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#7c3aed" stop-opacity="0.55"/>
      <stop offset="60%" stop-color="#4c1d95" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#4c1d95" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orb2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#06b6d4" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#06b6d4" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orb3" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#a78bfa" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#a78bfa" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#e2e8f0"/>
      <stop offset="45%" stop-color="#ffffff"/>
      <stop offset="75%" stop-color="#c4b5fd"/>
      <stop offset="100%" stop-color="#7c3aed"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed" stop-opacity="0"/>
      <stop offset="30%" stop-color="#7c3aed" stop-opacity="0.8"/>
      <stop offset="70%" stop-color="#06b6d4" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#06b6d4" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="gridFade" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.07"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <clipPath id="clip">
      <rect width="1200" height="340"/>
    </clipPath>
  </defs>
  <g clip-path="url(#clip)">
    <rect width="1200" height="340" fill="url(#bg)"/>
    <!-- Stars -->
    <circle cx="45" cy="28" r="1" fill="#fff" opacity="0.6"/>
    <circle cx="120" cy="60" r="0.8" fill="#fff" opacity="0.4"/>
    <circle cx="200" cy="18" r="1.2" fill="#fff" opacity="0.7"/>
    <circle cx="310" cy="42" r="0.7" fill="#fff" opacity="0.5"/>
    <circle cx="420" cy="12" r="1" fill="#fff" opacity="0.6"/>
    <circle cx="550" cy="35" r="0.8" fill="#fff" opacity="0.3"/>
    <circle cx="680" cy="20" r="1.1" fill="#fff" opacity="0.5"/>
    <circle cx="790" cy="50" r="0.7" fill="#fff" opacity="0.6"/>
    <circle cx="900" cy="14" r="1" fill="#fff" opacity="0.4"/>
    <circle cx="1020" cy="38" r="0.9" fill="#fff" opacity="0.7"/>
    <circle cx="1140" cy="22" r="1" fill="#fff" opacity="0.5"/>
    <circle cx="80" cy="90" r="0.8" fill="#c4b5fd" opacity="0.5"/>
    <circle cx="980" cy="80" r="0.9" fill="#c4b5fd" opacity="0.4"/>
    <circle cx="1100" cy="100" r="0.7" fill="#fff" opacity="0.4"/>
    <circle cx="30" cy="160" r="0.6" fill="#fff" opacity="0.3"/>
    <circle cx="1170" cy="140" r="0.8" fill="#fff" opacity="0.3"/>
    <!-- Perspective grid -->
    <line x1="600" y1="248" x2="0" y2="340" stroke="#7c3aed" stroke-width="0.5" opacity="0.12"/>
    <line x1="600" y1="248" x2="240" y2="340" stroke="#7c3aed" stroke-width="0.5" opacity="0.12"/>
    <line x1="600" y1="248" x2="480" y2="340" stroke="#7c3aed" stroke-width="0.5" opacity="0.10"/>
    <line x1="600" y1="248" x2="720" y2="340" stroke="#7c3aed" stroke-width="0.5" opacity="0.10"/>
    <line x1="600" y1="248" x2="960" y2="340" stroke="#7c3aed" stroke-width="0.5" opacity="0.12"/>
    <line x1="600" y1="248" x2="1200" y2="340" stroke="#7c3aed" stroke-width="0.5" opacity="0.12"/>
    <line x1="600" y1="248" x2="1200" y2="320" stroke="#7c3aed" stroke-width="0.4" opacity="0.07"/>
    <line x1="600" y1="248" x2="0" y2="315" stroke="#7c3aed" stroke-width="0.4" opacity="0.07"/>
    <line x1="600" y1="248" x2="350" y2="340" stroke="#6d28d9" stroke-width="0.4" opacity="0.08"/>
    <line x1="600" y1="248" x2="850" y2="340" stroke="#6d28d9" stroke-width="0.4" opacity="0.08"/>
    <line x1="100" y1="310" x2="1100" y2="310" stroke="#ffffff" stroke-width="0.4" opacity="0.05"/>
    <line x1="200" y1="290" x2="1000" y2="290" stroke="#ffffff" stroke-width="0.4" opacity="0.05"/>
    <line x1="280" y1="275" x2="920" y2="275" stroke="#ffffff" stroke-width="0.3" opacity="0.05"/>
    <line x1="350" y1="263" x2="850" y2="263" stroke="#ffffff" stroke-width="0.3" opacity="0.04"/>
    <!-- Glow orbs -->
    <ellipse cx="600" cy="200" rx="380" ry="240" fill="url(#orb1)"/>
    <ellipse cx="160" cy="180" rx="200" ry="160" fill="url(#orb2)"/>
    <ellipse cx="1050" cy="160" rx="200" ry="140" fill="url(#orb3)"/>
    <!-- Horizon line -->
    <rect x="0" y="247" width="1200" height="1" fill="url(#lineGrad)" opacity="0.7"/>
    <!-- Code fragments -->
    <text x="64" y="200" font-family="monospace" font-size="11" fill="#7c3aed" opacity="0.35">multi_agent</text>
    <text x="1020" y="210" font-family="monospace" font-size="11" fill="#06b6d4" opacity="0.3">RAG_pipeline</text>
    <text x="80" y="238" font-family="monospace" font-size="10" fill="#a78bfa" opacity="0.22">→ 8.5s</text>
    <text x="1060" y="238" font-family="monospace" font-size="10" fill="#a78bfa" opacity="0.22">−65%</text>
    <!-- Bracket decor -->
    <text x="200" y="178" font-family="monospace" font-size="48" fill="#4c1d95" opacity="0.18">{</text>
    <text x="948" y="178" font-family="monospace" font-size="48" fill="#4c1d95" opacity="0.18">}</text>
    <!-- Corner accents -->
    <line x1="0" y1="0" x2="60" y2="0" stroke="#7c3aed" stroke-width="1.5" opacity="0.7"/>
    <line x1="0" y1="0" x2="0" y2="50" stroke="#7c3aed" stroke-width="1.5" opacity="0.7"/>
    <line x1="1200" y1="0" x2="1140" y2="0" stroke="#06b6d4" stroke-width="1.5" opacity="0.5"/>
    <line x1="1200" y1="0" x2="1200" y2="50" stroke="#06b6d4" stroke-width="1.5" opacity="0.5"/>
    <!-- Name -->
    <text x="600" y="152" font-family="system-ui,sans-serif" font-size="88" font-weight="800" text-anchor="middle" letter-spacing="-2" fill="url(#nameGrad)">GIRISH MANNE</text>
    <!-- Subtitle -->
    <text x="600" y="192" font-family="monospace" font-size="13" font-weight="400" text-anchor="middle" letter-spacing="3" fill="#94a3b8">MS ARTIFICIAL INTELLIGENCE  ·  SAN JOSE STATE UNIVERSITY</text>
    <!-- Underline -->
    <rect x="430" y="203" width="340" height="0.8" fill="url(#lineGrad)" opacity="0.6"/>
    <!-- Status pill -->
    <rect x="490" y="216" width="220" height="22" rx="11" fill="#1a0030" stroke="#7c3aed" stroke-width="0.8" opacity="0.9"/>
    <circle cx="508" cy="227" r="3.5" fill="#a78bfa" opacity="0.9"/>
    <text x="520" y="231" font-family="monospace" font-size="10.5" fill="#c4b5fd" letter-spacing="1">open to ai/ml roles</text>
  </g>
</svg>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=15&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&repeat=true&width=560&lines=building+AI+systems+that+ship+to+production;multi-agent+RAG+%C2%B7+voice+AI+%C2%B7+MLOps;Graduate+Research+Assistant+%40+SJSU;open+to+AI%2FML+internships+%E2%80%94+Summer+2026" alt="typing"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%237c3aed.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/girish-manne-555978255/)
[![Gmail](https://img.shields.io/badge/Gmail-%237c3aed.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:girishmanne6@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23a78bfa.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Girishmanne6/Portfolio)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=4c1d95&height=1.5" width="100%"/>

<br/>

```python
class GirishManne:
    role        = "AI Engineer · Graduate Research Assistant @ SJSU"
    focus       = ["Multi-Agent Systems", "RAG Pipelines", "MLOps", "Voice AI"]
    shipped     = {"voice_latency": "−65%", "query_time": "27s → 8.5s", "drift_recovery": "+18–27pp"}
    currently   = "building AI that works in real classrooms"
    open_to     = "AI/ML internship roles — Summer 2026"
```

<br/>

## ⚡ featured work

<table>
<tr>
<td width="50%" valign="top">

**[WhyCode](https://github.com/Girishmanne6/whycode)** &nbsp;`RAG` `LangGraph` `ChromaDB`

Four specialized agents over 1,100+ repo embeddings — hybrid retrieval across dependency graphs + semantic search + LLM reasoning.

`27s → 8.5s` query time

</td>
<td width="50%" valign="top">

**[DriftShield](https://github.com/Girishmanne6/DriftShield)** &nbsp;`MLOps` `PyTorch` `WebSockets`

KS test + PSI + rolling accuracy with live WebSocket alerts. TENT adaptation implemented from scratch — no retraining needed.

`+18–27pp` accuracy recovered under domain shift

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[RankLab](https://github.com/Girishmanne6/RankLab)** &nbsp;`RecSys` `LightGCN` `Python`

LightGCN + contrastive regularization on 50K-user EB-NeRD. A/B dashboard tracking Recall, NDCG, and diversity simultaneously.

</td>
<td width="50%" valign="top">

**[shift-left-compliance](https://github.com/Girishmanne6/shift-left-compliance)** &nbsp;`OPA` `DevSecOps`

Policy-as-code: compliance gates embedded directly into CI — violations caught before they ever reach production.

</td>
</tr>
</table>

<details>
<summary>&nbsp;<b>more projects</b></summary>

<br/>

| project | what it does |
|---------|-------------|
| [Truthseeker](https://github.com/Girishmanne6/Truthseeker) | multimodal deepfake detection — visual + audio fusion |
| [compliance-agent](https://github.com/Girishmanne6/compliance-agent) | LLM agent for regulatory document review |
| [Sukhibava-Medical-Chatbot](https://github.com/Girishmanne6/Sukhibava-Medical-Chatbot) | domain-specific medical Q&A agent |
| [tomasulo-simulator](https://github.com/Girishmanne6/tomasulo-simulator) | out-of-order CPU execution simulator |
| [Curbrules](https://github.com/Girishmanne6/Curbrules) | Cursor AI rules configuration |

</details>

<br/>

## 🛠 stack

<div align="center">

![Python](https://img.shields.io/badge/Python-1a0033?style=flat-square&logo=python&logoColor=a78bfa)
![PyTorch](https://img.shields.io/badge/PyTorch-1a0033?style=flat-square&logo=pytorch&logoColor=a78bfa)
![LangChain](https://img.shields.io/badge/LangChain-1a0033?style=flat-square&logo=chainlink&logoColor=a78bfa)
![FastAPI](https://img.shields.io/badge/FastAPI-1a0033?style=flat-square&logo=fastapi&logoColor=a78bfa)
![Docker](https://img.shields.io/badge/Docker-1a0033?style=flat-square&logo=docker&logoColor=a78bfa)
![AWS](https://img.shields.io/badge/AWS-1a0033?style=flat-square&logo=amazonaws&logoColor=a78bfa)
![Next.js](https://img.shields.io/badge/Next.js-1a0033?style=flat-square&logo=nextdotjs&logoColor=a78bfa)
![TypeScript](https://img.shields.io/badge/TypeScript-1a0033?style=flat-square&logo=typescript&logoColor=a78bfa)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a0033?style=flat-square&logo=postgresql&logoColor=a78bfa)
![Git](https://img.shields.io/badge/Git-1a0033?style=flat-square&logo=git&logoColor=a78bfa)

</div>

<br/>

## 📊 activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Girishmanne6&show_icons=true&theme=transparent&hide_border=true&title_color=a78bfa&icon_color=7c3aed&text_color=c4b5fd&ring_color=7c3aed&bg_color=00000000" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Girishmanne6&layout=compact&theme=transparent&hide_border=true&title_color=a78bfa&text_color=c4b5fd&bg_color=00000000&langs_count=6" height="160"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Girishmanne6&theme=transparent&hide_border=true&ring=7c3aed&fire=a78bfa&currStreakLabel=a78bfa&sideLabels=c4b5fd&dates=6b7280&currStreakNum=e2e8f0&sideNums=e2e8f0" height="150"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Girishmanne6&bg_color=000000&color=7c3aed&line=4c1d95&point=a78bfa&area=true&area_color=1a0033&hide_border=true&radius=6" width="96%"/>

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=soft&height=56&color=0:000000,100:0d0020&section=footer&text=systems+that+think+in+layers&fontSize=13&fontColor=7c3aed&animation=fadeIn" width="100%"/>
</div>
