<div align="center">

<img src="https://img.shields.io/badge/AUB-7A003C?style=for-the-badge&labelColor=5C002D&color=7A003C" alt="AUB" />
<img src="https://img.shields.io/badge/Course-%2332480-C8A951?style=for-the-badge&labelColor=1C1A19" alt="Course 32480" />
<img src="https://img.shields.io/badge/License-MIT-3B6B47?style=for-the-badge" alt="MIT License" />

# AI in Education

### *Literacy &amp; Applications*

**A 15-topic AI literacy program for educators**
*American University of Beirut · Faculty of Arts &amp; Sciences*

> *"That they may have life, and have it more abundantly"*

---

[![Topics](https://img.shields.io/badge/Topics-15-7A003C?style=flat-square)](#course-structure)
[![Lectures](https://img.shields.io/badge/Lectures-2_published-3B6B47?style=flat-square)](#whats-inside)
[![Status](https://img.shields.io/badge/Status-In_Progress-C8A951?style=flat-square)](#progress)
[![LMS](https://img.shields.io/badge/AUB_LMS-Course_32480-5C002D?style=flat-square)](https://lms.aub.edu.lb/course/view.php?id=32480)

</div>

---

## 📖 About This Repository

This repository is the companion learning archive for **AI in Education: Literacy &amp; Applications**, a 15-topic course delivered through the AUB Learning Management System (Course #32480). It mirrors the official AUB LMS course portal and serves as a public, version-controlled record of:

- 📚 Lecture decks and concept maps
- 📝 Practice assignments and submitted reports
- 🤖 AI prompts used (for reproducibility)
- 🎯 Reflections on what AI did well, what it missed
- 🌐 An interactive HTML dashboard for navigating the entire course

Built in the spirit of *open educational resources* — every artifact here can be cloned, adapted, or used as a reference template for similar AI-literacy programs at other institutions.

---

## 🎯 Why This Course Exists

Education sits at a hinge moment. In 2024, **78% of organizations worldwide adopted AI**, up from 55% the year before *(Stanford HAI Report, 2025)*. **77% of educators believe AI is useful** in education *(UNESCO, 2024)*. AI-driven EdTech usage rose **400% between 2016 and 2023**.

But adoption without literacy is dangerous. AI hallucinates fluent fiction. It inherits bias. It tempts students into superficial learning. It raises FERPA and GDPR concerns the moment a real student name is pasted into a public chat.

This course exists to give educators the conceptual frame, the practical prompting skills, and the ethical guardrails to use AI well — and to teach their students to do the same.

> *"AI will not replace educators — but educators who use AI will lead the future."*
> &mdash; closing slide, Lecture 2

---

## 🗂️ Course Structure

The course is organized into **15 topics**, mirroring the AUB LMS folder hierarchy exactly. Each topic has its own folder containing lectures, readings, assignments, and (where relevant) submitted reports.

| # | Topic | Status | Materials |
|---|-------|--------|-----------|
| 01 | **Syllabus &amp; References** | ✅ Complete | Course Syllabus · 5 reference PDFs · Meeting link |
| 02 | **Introduction** | ✅ Complete | Lecture 1 *(Foundations of AI in Education, 35 slides)* |
| 03 | **Generative AI in Education** | 🟡 In Progress | Lecture 2 *(42 slides)* · Practice Assignment · Recording |
| 04 | *AI Literacy for Educators* | ⏳ Upcoming | — |
| 05 | *Prompt Engineering for Teaching* | ⏳ Upcoming | — |
| 06 | *AI-Augmented Lesson Design* | ⏳ Upcoming | — |
| 07 | *AI in Assessment* | ⏳ Upcoming | — |
| 08 | *Feedback &amp; Formative Assessment* | ⏳ Upcoming | — |
| 09 | *Personalization &amp; Differentiation* | ⏳ Upcoming | — |
| 10 | *Data &amp; Learning Analytics* | ⏳ Upcoming | — |
| 11 | *Ethics &amp; Bias in Educational AI* | ⏳ Upcoming | — |
| 12 | *Academic Integrity in the Age of AI* | ⏳ Upcoming | — |
| 13 | *Policy &amp; Governance* | ⏳ Upcoming | — |
| 14 | *Capstone Design* | ⏳ Upcoming | — |
| 15 | *Final Showcase* | ⏳ Upcoming | — |

---

## 📂 Repository Layout

```
aub-ai-education-literacy-applications/
│
├── 📜 README.md                              ← you are here
├── 📜 LICENSE                                ← MIT
├── 🌐 index.html                             ← interactive course dashboard
│
├── 📁 topic-01-syllabus-and-references/
│   ├── course-syllabus.pdf
│   ├── ai-adoption-in-the-education-system.pdf
│   ├── ai-and-the-future-of-teaching-and-learning.pdf
│   ├── impact-of-ai.pdf
│   ├── artificial-intelligence-impact-on-education.pdf
│   └── guide-to-ai-in-schools.pdf
│
├── 📁 topic-02-introduction/
│   └── lecture-1-foundations-of-ai-in-education.pptx
│
├── 📁 topic-03-generative-ai-in-education/
│   ├── lecture-2-concepts-capabilities-educational-use.pptx
│   ├── practice-assignment.pdf
│   └── submissions/
│       ├── practice-assignment-report.pdf      ← my submitted report
│       ├── prompts-used.md                     ← AI prompts (verbatim)
│       └── reflection.md                       ← 3-question reflection
│
├── 📁 topic-04-ai-literacy/                  ← provisioned, awaiting content
├── 📁 topic-05-prompt-engineering/
├── 📁 topic-06-lesson-design/
├── 📁 topic-07-assessment/
├── 📁 topic-08-feedback/
├── 📁 topic-09-personalization/
├── 📁 topic-10-data-analytics/
├── 📁 topic-11-ethics-and-bias/
├── 📁 topic-12-academic-integrity/
├── 📁 topic-13-policy-and-governance/
├── 📁 topic-14-capstone-design/
└── 📁 topic-15-final-showcase/
```

---

## 🌐 Interactive Dashboard

This repository ships with `index.html` — a single-file, AUB-themed dashboard that lets you navigate every topic, every lecture, and every assignment without leaving your browser. No build step, no dependencies, just open the file.

### Highlights

| Feature | What it does |
|---------|--------------|
| 🎨 **AUB heritage palette** | Maroon `#7A003C`, gold `#C8A951`, cedar `#3B6B47`, on a charcoal canvas — mirrors aub.edu.lb |
| 🗺️ **15 topic tabs** | Status dots (✓ complete · ◉ in progress · ○ upcoming) match the LMS exactly |
| 🧠 **Concept maps** | Mermaid-rendered diagrams for Lecture 1 and Lecture 2 |
| 🏗️ **AI architectures** | The 5 generative architectures (Transformers, Diffusion, GANs, VAEs, Multimodal) as cards |
| 🔄 **Training pipeline** | 5-stage flowchart: Data → Pre-Training → Fine-Tuning → RLHF → Inference |
| ✏️ **Prompt framework** | The 5-element framework (Role · Audience · Task · Format · Constraint) with weak-vs-strong examples |
| 📊 **Assignment dashboard** | Full Topic 3 practice assignment: dataset, AI-assisted analysis, AUB-styled bar chart, teacher report, reflection |

### Open it locally

```bash
git clone https://github.com/<your-handle>/aub-ai-education-literacy-applications.git
cd aub-ai-education-literacy-applications
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

---

## 📚 What's Inside — Topic by Topic

### Topic 02 · Introduction *(Lecture 1, 35 slides)*

The foundations: what AI is and isn't, how it works, and why it matters for educators today.

- **The opening question:** *Have you used AI today?* (Search, Netflix recommendations, autocomplete, GPS, ChatGPT — yes, yes, yes, yes, yes.)
- **AI by the numbers:** McKinsey, Stanford HAI, UNESCO 2024/25 statistics
- **Three core distinctions:**
  1. **Narrow AI vs. Generative AI vs. AGI** — what's actually shipping vs. what's hypothetical
  2. **Prediction, not understanding** — confidence ≠ correctness
  3. **Tool, not teacher** — the educator owns accuracy, judgment, guidance
- **Activity:** 6 discussion questions for evaluating an AI response

### Topic 03 · Generative AI in Education *(Lecture 2, 42 slides)*

The substance of the course. Lecture 2 covers four pillars:

#### 🧱 What GenAI is
- Traditional AI (analytical) vs. Generative AI (creative) — the core distinction
- Output types: text, image, audio, video, code, 3D

#### 🏗️ How GenAI is built
- **5 architectures:** Transformers · Diffusion Models · GANs · VAEs · Multimodal
- **5-stage training pipeline:** Data Collection → Pre-Training → Fine-Tuning → RLHF → Inference
- **Tokens &amp; context windows:** GPT-4o (128K) · Claude 3.5 (200K) · why prompt length matters

#### 🎯 How to use GenAI well
- **5-element prompt framework:** Role · Audience · Task · Format · Constraint
- **Tool landscape:** ChatGPT · Claude · Gemini · DALL·E · Gamma — when to use which
- **Decision rubric:** 5 classroom scenarios with use/don't-use guidance

#### ⚠️ What GenAI cannot do — the 5 limitations every educator must internalize
1. **Hallucinations** — fluent fiction with no warning
2. **Inherited bias** — race, gender, geography, class
3. **Over-reliance** — the struggle *is* the learning
4. **Academic integrity** — detection tools are unreliable
5. **Data privacy** — never paste real student data into public AI

> 🧪 **Live example included:** GPT-4 was asked for "three peer-reviewed studies on AI-assisted learning published in 2022." It returned three confidently-formatted citations. **All three were fabricated.** Author names, journals, page numbers, DOIs — invented.

#### 📝 Practice Assignment (Topic 3)

A teacher-perspective exercise: 8 students, 4 quizzes, build a 1–2 page brief for the Head of the Educational Unit using AI to assist the analysis.

The submission in this repo includes:

- **Dataset analysis** — class average, per-student trajectories, polarization patterns
- **AUB-styled bar chart** (8 students × 4 quizzes, AUB palette)
- **Teacher report** addressed to the Head of the Educational Unit
- **Verbatim AI prompt** used to generate the analysis
- **3-question reflection** — What did the AI do well? What did it miss? Would you rely on it as-is?

---

## 🛠️ How This Repo Is Used

**For students taking the course:**
- Use this repo as a parallel reference to the AUB LMS — same materials, navigable in one place
- Read submitted reports (where authorized) to see how peers approached assignments
- Reuse the concept-map diagrams as study aids

**For educators adapting the course:**
- Fork the repo
- Replace the LMS course number and AUB branding with your institution's
- Reuse the topic structure, the prompt frameworks, the assignment template

**For researchers:**
- The verbatim AI prompts are saved alongside outputs — useful for reproducibility
- Reflection notes capture *what AI got wrong* — a small but growing corpus

---

## 🎓 Course Information

| | |
|---|---|
| **Institution** | American University of Beirut |
| **Faculty** | Faculty of Arts &amp; Sciences |
| **Course Title** | AI in Education: Literacy &amp; Applications |
| **LMS Course #** | 32480 |
| **Course Portal** | [lms.aub.edu.lb/course/view.php?id=32480](https://lms.aub.edu.lb/course/view.php?id=32480) |
| **Format** | 15 topics · Hybrid (in-person + online) |
| **Maintainer** | Mohammad Alrashed |

---

## 🤖 Note on AI-Assisted Authorship

In the spirit of the course itself: **this README, the dashboard's HTML, the assignment analyses, and the concept maps were drafted with AI assistance** (primarily Claude). The maintainer reviewed, restructured, fact-checked, and edited every artifact before committing it.

Following the course's own principle:

> *AI as a fast first draft, the educator as the final author.*

Where AI was used for analysis (e.g., the Topic 3 practice assignment), the **verbatim prompt is included alongside the output** so the work is reproducible and the reader can judge for themselves where the AI's contribution begins and ends.

---

## 📜 License

Released under the [MIT License](LICENSE) — free to clone, fork, adapt, and reuse for educational purposes. If you build on this work, an attribution back to the AUB course or this repository is appreciated but not required.

---

## 🤝 Contributing

This is primarily a personal learning archive, but pull requests are welcome for:

- 🐛 Typo fixes in any document
- 📖 Additional reading suggestions in `topic-01-syllabus-and-references/`
- 🎨 Dashboard UI improvements that respect the AUB palette
- 🔗 Broken-link fixes

For substantive content additions, please open an issue first to discuss scope.

---

<div align="center">

### *"That they may have life, and have it more abundantly"*

**American University of Beirut · Founded 1866**

Made with ☕ in Beirut · Built with the very tools the course teaches

[⬆ back to top](#ai-in-education)

</div>
