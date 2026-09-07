# Warit Yuvaniyama (Note)

<p align="center">
  <img src="assets/portrait.png" width="140" alt="Warit Yuvaniyama"/>
</p>

**Fourth-year Computer Engineering Student** · Sirindhorn International Institute of Technology (SIIT), Thammasat University
CGPA 3.92 · Academic Outstanding Student Scholarship

I work at the intersection of **embedded systems, robotics, and machine learning** — building the software that lets robots perceive and act, and doing research that pushes those same ideas forward. Currently President of the SIIT Robotic Club (**OrcaBOT**), preparing to compete in **RoboCup Japan Open**, and contributing to peer-reviewed research in sensor fusion, Thai NLP, and reinforcement learning.

[![Build CVs](https://github.com/Warit-Yuv/Warit_CV/actions/workflows/build.yml/badge.svg)](https://github.com/Warit-Yuv/Warit_CV/actions/workflows/build.yml)

---

## 📄 Curriculum Vitae

Full details of my education, experience, publications, and awards are in the documents below — compiled fresh from LaTeX on every push.

| Document | First page | Download |
|---|---|---|
| **CV** (extended, complete record) | ![](assets/Warit_CV_p1.png) | [Warit_CV.pdf](Warit_CV.pdf) |
| **Resume** (1–2 pages) | ![](assets/Resume_p1.png) | [Resume.pdf](Resume.pdf) |

## 🔬 Research

My research sits where perception, learning, and language meet real-world constraints:

- **Multimodal perception for degraded environments** — During a research internship at the Measurement & Intelligence Systems Lab (Kansai University, Japan), I built a **mmWave radar + thermal imaging fusion pipeline** on ROS2, enabling a TurtleBot3 to navigate in smoke-filled conditions where cameras and LiDAR fail — including real-time depth-colored radar point clouds and hardware-accelerated 16-bit radiometric thermal streaming.
- **Thai natural language processing** — First author of a hybrid rule-based rhyme verification system for classical Thai poetry (*Klon*), merged into [PyThaiNLP](https://github.com/PyThaiNLP/PyThaiNLP) and evaluated on 36,475 stanzas; it also serves as a deterministic reward signal for GenAI-based poetry generation (iSAI-NLP 2026, in review).
- **Reinforcement learning for control** — Physics-informed reward shaping for fuel-efficient orbital transfer (~10% fuel reduction, IEICE Trans. Communications) and online recursive least-squares refinement of legged-locomotion controllers on a Unitree Go2 (IEEE/SICE SII 2027).
- **Computer vision for environmental monitoring** — Applied the Fast Segment Anything Model to water surface level estimation for coastal erosion monitoring; published in Springer LNCS vol. 15585 (IUKM 2025) and presented in Vietnam and Bangkok.

A full publication list is in the [CV](Warit_CV.pdf).

## 🤖 Robotics & Leadership

As **President & Embedded Systems Lead of OrcaBOT** (SIIT Robotic Club), I lead a 30-member team building automatic soccer robots for the **Small Size League**, managing a 100,000+ THB procurement budget along the way. On the technical side, I've written custom C++ motor-control libraries, holonomic drive algorithms, and redesigned our serial and wireless nRF communication stack for responsiveness and stability — and I was primary author of the software architecture section of our [RoboCup 2024 Team Description Paper](https://ssl.robocup.org/wp-content/uploads/2024/04/2024_TDP_OrcaBOT.pdf).

## 🚀 Startups & Projects

- **[FlashLight](https://flashlight.in.th)** — Co-founded a study-planning platform that breaks 368+ A-Level topics into personalized daily missions for Thai students preparing for the TCAS admission exam. Reached **Top 5** of 80+ teams in the Startup Thailand League and ranked **#7 in Education** on the Thai App Store with our iOS MVP.
- **CrystalEyes** — A low-cost CNC-based digital microscope system (10k–15k THB) automating crystallization screening, replicating functionality of commercial systems costing 1M+ THB. Built and iterated from high school through university; demonstrated on lysozyme and MOF studies.
- **Autolocate** — A condo parking-management backend in SQL and Express.js with a three-tier connection pool, role-based access control, and JWT/HttpOnly-cookie authentication. [Source on GitHub](https://github.com/Warit-Yuv/Autolocate_Backend).
- **CareAir** — 1st Place (Physical Wellness Track), Thammasat Hackathon: Future Wellness 2024 — a proof-of-concept carbon capture machine for classrooms and workplaces.

## 🌏 International Experience

Research and workshops have taken me to Japan (Kansai University internship, OIT-SIIT iPBL workshops), Taiwan (PBL Workshop, Taipei Tech), Vietnam (IUKM 2025), and Singapore (Sustainability Startathon finalist) — experiences that taught me to collaborate across languages, disciplines, and time zones.

## 📬 Contact

- **Email:** [6622770459@g.siit.tu.ac.th](mailto:6622770459@g.siit.tu.ac.th)
- **LinkedIn:** [warit-yuvaniyama](https://www.linkedin.com/in/warit-yuvaniyama/)
- **GitHub:** [@Warit-Yuv](https://github.com/Warit-Yuv)

---

## 🛠️ How this repository works

- `Warit_CV.tex` / `Resume.tex` — LaTeX sources, built on the custom [`resume.cls`](resume.cls) (based on Trey Hunner's resume class)
- `.github/workflows/build.yml` — CI pipeline: compiles both documents, then commits the updated PDFs and the preview images in [`assets/`](assets) back to the repository automatically
- Every push to a `.tex` or `.cls` file keeps the previews and PDFs above up to date — no manual rebuilds needed

To build locally:

```
pdflatex -interaction=nonstopmode Warit_CV.tex
```

## LICENSE

The contents of this repository are provided under the [MIT License](LICENSE). The `resume.cls` template retains its original notice (© Trey Hunner).