<p align="center">
  <img src="./assets/profile-header.svg" alt="Mathew Joseph. Software, applied ML and accessibility. Building useful tools, from APIs to interfaces." width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/0xmathew/">LinkedIn</a> ·
  <a href="mailto:mathewjosephparakka@gmail.com">Email</a> ·
  <a href="https://github.com/mathew1046?tab=repositories">Repositories</a> ·
  <a href="https://twitter.com/0_xMatty">X</a>
</p>

## Hi, I'm Mathew

I'm a **Software Developer Trainee at ALLTechSoft** and a **B.Tech CSE (Data Science) student at MACE**, graduating in **2028**.

I build backend systems, full-stack applications and tools that use speech, computer vision and embedded hardware. A lot of my projects explore accessibility: understanding signs, making announcements visible, or helping people interact with software through voice.

**Open to software engineering and applied ML internships**, including remote work alongside college.

## Selected work

### [Brightloop](https://github.com/mathew1046/subscription-management-system)
**Self-hosted subscription management · Go / PostgreSQL / Next.js**

My work covers the Go backend, PostgreSQL, shared contracts, infrastructure and integration. The system manages subscription lifecycles, recurring invoices, manual payment records and a transactional email outbox. Billing safety uses database transactions, row locks and unique constraints.

[Code & architecture](https://github.com/mathew1046/subscription-management-system#architecture-and-billing-rules) · [Run locally](https://github.com/mathew1046/subscription-management-system#quick-start-docker)

### [CueBell](https://github.com/mathew1046/CueBell)
**Spoken announcements to personal alerts · React Native / Kotlin / FastAPI**

An Android accessibility prototype that listens for a requested announcement and produces a visual, vibration or sound alert. A native microphone service streams audio to a separate backend; structured events are checked against source speech before alerting.

[Code](https://github.com/mathew1046/CueBell) · [Android preview](https://github.com/mathew1046/CueBell/releases/tag/v1.3.0-preview) · [Demo guide](https://github.com/mathew1046/CueBell/blob/main/DEMO.md)

<sub>Internet-connected prototype. Calls can be missed; real-world reliability is still being evaluated.</sub>

### [GloveTalk](https://github.com/mathew1046/Sign2Sound_Kaizen)
**Sign recognition and speech output · Python / PyTorch / ESP32**

Team Kaizen's Sign2Sound project combines camera-based pose recognition with wearable glove sensing. The repository documents a multi-stream pose transformer, sensor-based classifiers and the hardware-to-inference pipeline.

[Code & models](https://github.com/mathew1046/Sign2Sound_Kaizen) · [System design](https://github.com/mathew1046/Sign2Sound_Kaizen#-system-architecture)

### [JobSathi](https://github.com/mathew1046/jobsathi)
**Voice-driven resume building · React / FastAPI / Speech recognition**

A multilingual workflow that turns spoken answers into structured profile information and a downloadable resume, with job-search integration. It brings together audio capture, transcription, translation and document generation.

[Code & setup](https://github.com/mathew1046/jobsathi) · [API overview](https://github.com/mathew1046/jobsathi#-api-endpoints)

### [KaiSign](https://github.com/mathew1046/KaiSign)
**Accessible restaurant-ordering prototype · FastAPI / MediaPipe / Embedded hardware**

Team Kaizen's kiosk explores keypad, voice and camera-based ordering. The sign-recognition experiment supports ten preference words, with confidence gates before an action is accepted.

[Code](https://github.com/mathew1046/KaiSign) · [Build & demonstration](https://www.hackster.io/kaizen/kaisign-accessible-dining-reimagined-e8b724) · [Seeed Studio contest results](https://www.seeedstudio.com/blog/2026/10/09/who-won-the-2026-interactive-signage-contest/)

## Tools I work with

| Area | Technologies |
| :--- | :--- |
| Backend & data | Python, Go, FastAPI, PostgreSQL, SQL |
| Web & mobile | TypeScript, JavaScript, React, Next.js, React Native, Kotlin |
| Applied ML | PyTorch, OpenCV, MediaPipe, scikit-learn |
| Hardware & development | ESP32, Git, Docker, Linux, Playwright, Vitest |

## Open-source work

I've submitted LLVM/Clang patches around compiler diagnostics, DWARF emission and module behavior. The pull requests include the reproducer, proposed fix and regression tests:

- [Clang: GNU-inline body emission in global module fragments](https://github.com/llvm/llvm-project/pull/228962)
- [LLVM MC: negative CFI address deltas](https://github.com/llvm/llvm-project/pull/228663)
- [LLVM MC: DWARF emission after inline assembly errors](https://github.com/llvm/llvm-project/pull/228707)

These links show the current review status; submission does not imply a patch has been merged.

---

**Want to discuss a project or internship?** [Find me on LinkedIn](https://www.linkedin.com/in/0xmathew/) or [send me an email](mailto:mathewjosephparakka@gmail.com).
