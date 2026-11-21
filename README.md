<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=0F172A&center=true&vCenter=true&width=700&lines=Graded+Assessment+Creator;for+SCORM+%F0%9F%8E%AF;Raw+text+%E2%86%92+SCORM+.zip+in+seconds;100%25+Offline.+Zero+API+Keys." alt="Typing SVG" />

<br/>

[![Live Tool](https://img.shields.io/badge/▶%20LAUNCH%20LIVE%20TOOL-2563EB?style=for-the-badge&logoColor=white)](https://linuxsunil.github.io/Graded-Assessment-Creator-for-SCORM/)
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

## The Number That Changes Everything

> A skilled Storyline 360 developer takes **6–8 hours** to build a 10-question graded assessment — designing slides, programming variables, wiring pass/fail logic, QA-ing interactions, and packaging it for Rise 360 or standalone LMS delivery.
>
> **This tool does it in under 60 seconds.**
>
> Same output. SCORM-compliant. LMS-ready. Embeds directly in Rise 360 as a block, or deploys standalone in any LMS.

---

## Boot Sequence

```
Graded Assessment Creator for SCORM  v1.0
------------------------------------------
  Parser loaded      MCQ + MMCQ
  Difficulty pools   Easy | Medium | Hard | General
  SCORM wrapper      1.2 / 2004
  QA toolbar         per-question reset
  Branding engine    real-time colour sync
  Privacy mode       ZERO server calls

  STATUS: READY. Zero data leaks.
```

---

## Why This Exists

| | Storyline 360 (Traditional) | This Tool |
|:--|:--|:--|
| ⏱️ Time for 10 questions | 6–8 hours (skilled dev) | **Under 60 seconds** |
| 💸 Cost | Subscription required | **Free forever** |
| ☁️ Data privacy | Cloud-dependent | **100% local** |
| 🔑 Setup | Software install + licence | **Open in browser** |
| 🧪 QA process | Re-run full quiz each time | **Reset per question** |
| 📦 Output | SCORM package | **SCORM package** |
| 🔗 Rise 360 | Embeds as block | **Embeds as block** |
| 🎨 Branding | Slide-by-slide edits | **Live colour picker** |

---

## Feature Matrix

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

## Question Syntax

Write questions in plain text — no code, no special tools required:

```
# MCQ — Single Correct Answer
Q: Which SCORM version introduced Tin Can foundations?
A) SCORM 1.2
B) SCORM 2004 4th Ed
*C) xAPI (Tin Can)
D) AICC
POOL: Medium

# MMCQ — Multiple Correct Answers
Q: Which are valid Bloom's Taxonomy levels? [multi]
*A) Apply
*B) Analyse
C) Absorb
*D) Evaluate
POOL: Hard
```

> Prefix `*` marks correct answers. Add `[multi]` for multiple-select questions. That's the entire syntax.

---

## The Workflow

**Step 1 — Paste**
Drop your raw question bank into the editor.

**Step 2 — Configure**
Set pass mark, number of attempts, and draw counts per difficulty pool.

**Step 3 — QA**
Use the interactive preview. The QA build lets you reset individual questions without replaying the full pool — a first in browser-based SCORM tooling.

**Step 4 — Export**
Download the production SCORM `.zip`. Upload to your LMS, or embed as a Rise 360 block. Done.

---

## By The Numbers

| Metric | Value |
|:-------|:------|
| Files in the tool | 1 |
| API keys required | 0 |
| Export modes | 2 (LMS Build + QA Build) |
| Difficulty pools | 4 (Easy · Medium · Hard · General) |
| SCORM versions supported | 2 (1.2 and 2004) |
| Time for 10 questions | Under 60 seconds |
| Traditional Storyline equivalent | 6–8 hours |

---

## Roadmap — v1.1

> Community feedback shapes what gets built next. [Open an issue](https://github.com/linuxsunil/Graded-Assessment-Creator-for-SCORM/issues) to vote or suggest.

- [ ] **⚖️ Weighted Scoring** — assign point values in question syntax (5pts for "Critical" vs 1pt for "Basic")
- [ ] **🧩 New Interaction Types** — matching interactions and true/false logic
- [ ] **🖼️ Local Media Support** — image embedding to keep packages fully offline and portable

---

## The Architect

**[Sunil Iyer](https://www.linkedin.com/in/sunil-iyer-b545964/)** — Senior Instructional Designer with 10+ years building eLearning across AI/ML (Coursera, Udemy), compliance training, and enterprise LMS deployments.

This tool was born from real production frustration — built to prove that "non-coders" can ship sophisticated, high-impact tooling by leveraging browser-native capabilities and AI.

---

## Credits

Huge thanks to **[NRZ Malik](https://www.linkedin.com/in/nrzmalik/)** for his invaluable [SCORM Tester](https://www.ai4id.community/track-lab-lms-download/) — essential in validating tracking and session compliance across LMS platforms.

---

## License

MIT — free to use, fork, and build upon.

---

<div align="center">

**If this saved you hours of authoring tool frustration — drop a ⭐**

`built in the browser · for the browser · zero install required`

</div>