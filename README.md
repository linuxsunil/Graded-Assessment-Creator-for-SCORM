<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=Graded+Assessment+Creator;for+SCORM+%F0%9F%8E%AF;Raw+text+%E2%86%92+SCORM+.zip+in+seconds;100%25+Offline.+Zero+API+Keys." alt="Typing SVG" />

<br/>

[![Live Tool](https://img.shields.io/badge/▶%20LAUNCH%20LIVE%20TOOL-00FF41?style=for-the-badge&logoColor=black)](https://linuxsunil.github.io/Graded-Assessment-Creator-for-SCORM/)
[![GitHub](https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/linuxsunil/Graded-Assessment-Creator-for-SCORM)

<br/>

![Offline](https://img.shields.io/badge/🔒_OFFLINE-100%25-brightgreen?style=flat-square&labelColor=0a0a0a)
![SCORM](https://img.shields.io/badge/📦_SCORM-1.2_&_2004-orange?style=flat-square&labelColor=0a0a0a)
![API Keys](https://img.shields.io/badge/⚡_API_KEYS-ZERO-blue?style=flat-square&labelColor=0a0a0a)
![Single File](https://img.shields.io/badge/📄_SINGLE_FILE-YES-purple?style=flat-square&labelColor=0a0a0a)
![QA Mode](https://img.shields.io/badge/🧪_QA_MODE-BUILT--IN-red?style=flat-square&labelColor=0a0a0a)
![License](https://img.shields.io/badge/📄_LICENSE-MIT-yellow?style=flat-square&labelColor=0a0a0a)

<br/>

> **A browser-based, single-file tool that transforms raw question text into production-ready SCORM packages.**  
> No authoring software. No subscriptions. No data leaving your machine. Ever.

</div>

---

## `$ ./assessment-creator --boot`

```
╔══════════════════════════════════════════════════════╗
║  Graded Assessment Creator for SCORM  v1.0           ║
╠══════════════════════════════════════════════════════╣
║  ✔  Parser loaded        MCQ + MMCQ                  ║
║  ✔  Difficulty pools     Easy | Medium | Hard | Gen  ║
║  ✔  SCORM wrapper        1.2 / 2004                  ║
║  ✔  QA toolbar           per-question reset          ║
║  ✔  Branding engine      real-time colour sync       ║
║  ✔  Privacy mode         ZERO server calls           ║
║                                                      ║
║  → STATUS: READY.  Zero data leaks.                  ║
╚══════════════════════════════════════════════════════╝
```

---

## ⚡ Why This Exists

Every L&D professional knows this pain:

```
The Old Way                        The New Way
─────────────────────────          ──────────────────────────
💸 Expensive authoring software    🆓 One HTML file. Free forever.
☁️  Cloud-dependent tools          🔒 100% browser-local. No cloud.
⏳ Hours of manual QA              🧪 Built-in QA mode with reset
🎨 Generic LMS styling             🎨 Real-time brand colour picker
🔑 API keys everywhere             ⚡ Zero API keys. Zero accounts.
📦 Complex export workflows        📥 Paste → Configure → Export. Done.
```

---

## 🛠️ Feature Matrix

| Feature | Description |
|:--------|:------------|
| 🧠 **Intelligent Text Parser** | Paste plain-text MCQ + MMCQ banks using simple syntax — no markdown gymnastics |
| 🎲 **Difficulty Pool Logic** | Multi-tier randomisation across Easy · Medium · Hard · General with configurable draw counts |
| 📦 **Dual-Output Export** | **LMS Build** (production .zip) + **QA Build** with per-question reset toolbar |
| 🔒 **100% Local & Private** | Runs entirely in your browser — no server, no account, no tracking |
| 📡 **Universal LMS Tracking** | Accurate Pass/Fail + completion data to any SCORM LMS (Moodle, Cornerstone, Docebo…) |
| 🎨 **Real-Time Branding** | Live primary + accent colour pickers sync the learner UI as you pick |
| 🔀 **Option Shuffling** | Randomises both question order AND answer options on every attempt |
| 🔁 **Configurable Attempts** | Set pass mark, max attempts, and pool draw counts per difficulty tier |

---

## ✍️ Question Syntax

Write questions in plain text — no code, no special tools required:

```
# ── MCQ — Single Correct Answer ──────────────────────────
Q: Which SCORM version introduced Tin Can foundations?
A) SCORM 1.2
B) SCORM 2004 4th Ed
*C) xAPI (Tin Can)        ← prefix * marks the correct answer
D) AICC
POOL: Medium

# ── MMCQ — Multiple Correct Answers ──────────────────────
Q: Which are valid Bloom's Taxonomy levels? [multi]
*A) Apply
*B) Analyse
C) Absorb
*D) Evaluate
POOL: Hard
```

---

## 🔄 The Workflow

```
  ┌──────────┐     ┌─────────────┐     ┌──────────┐     ┌──────────┐
  │  📝 PASTE│────▶│ ⚙️ CONFIGURE│────▶│  🔬 QA  │────▶│📥 EXPORT │
  │          │     │             │     │          │     │          │
  │ Drop your│     │ Pass marks  │     │ Preview  │     │ Download │
  │ question │     │ Attempts    │     │ Reset    │     │ SCORM    │
  │ bank     │     │ Pool counts │     │ questions│     │ .zip →   │
  │          │     │             │     │ per tier │     │ LMS ✓    │
  └──────────┘     └─────────────┘     └──────────┘     └──────────┘
```

**Four steps. That's the entire workflow.**

---

## 📊 By The Numbers

```
┌─────────────────────────────────────────────────────┐
│   1 file     →  entire tool. zero dependencies      │
│   0 API keys →  zero required. ever.                │
│   2 modes    →  LMS build + QA build                │
│   4 pools    →  Easy · Medium · Hard · General      │
│   2 versions →  SCORM 1.2 and SCORM 2004            │
│   ∞ questions→  unlimited bank depth                │
└─────────────────────────────────────────────────────┘
```

---

## 🗺️ Roadmap — v1.1

> Community feedback shapes what gets built next. [Open an issue](https://github.com/linuxsunil/Graded-Assessment-Creator-for-SCORM/issues) to vote or suggest.

- [ ] **⚖️ Weighted Scoring** — assign point values in question syntax (5pts for "Critical" vs 1pt for "Basic")
- [ ] **🧩 New Interaction Types** — matching interactions and true/false logic
- [ ] **🖼️ Local Media Support** — image embedding to keep packages fully offline and portable

---

## 👤 The Architect

**[Sunil Iyer](https://www.linkedin.com/in/sunil-iyer-b545964/)** — Senior Instructional Designer with 10+ years building eLearning across AI/ML (Coursera, Udemy), compliance training, and enterprise LMS deployments.

This tool was born from real production frustration — and built to prove that "non-coders" can ship sophisticated, high-impact tooling by leveraging browser-native capabilities and AI.

---

## 🤝 Credits

Huge thanks to **[NRZ Malik](https://www.linkedin.com/in/nrzmalik/)** for his invaluable [SCORM Tester](https://www.ai4id.community/track-lab-lms-download/) — essential in validating tracking and session compliance across LMS platforms.

---

## 📄 License

MIT — free to use, fork, and build upon.

---

<div align="center">

**If this saved you hours of authoring tool frustration — drop a ⭐**

`built in the browser · for the browser · zero install required`

</div>