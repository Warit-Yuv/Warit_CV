# Warit Yuvaniyama (Note)

Fourth-year Computer Engineering student at Sirindhorn International Institute of Technology (SIIT), Thammasat University, specializing in embedded systems and robotics (ROS2), with research experience in machine learning and sensor fusion.

[![Build CVs](https://github.com/Warit-Yuv/Warit_CV/actions/workflows/build.yml/badge.svg)](https://github.com/Warit-Yuv/Warit_CV/actions/workflows/build.yml)

---

## Curriculum Vitae

| Document | Preview | Download |
|---|---|---|
| CV (extended) | ![](assets/Warit_CV_p1.png) | [Warit_CV.pdf](Warit_CV.pdf) |
| Resume (1–2 pages) | ![](assets/Resume_p1.png) | [Resume.pdf](Resume.pdf) |

Clicking a preview opens the full-size image. The PDFs are recompiled automatically on every push via GitHub Actions, so the committed versions always reflect the current LaTeX sources.

## Contact

- **Email:** [6622770459@g.siit.tu.ac.th](mailto:6622770459@g.siit.tu.ac.th)
- **LinkedIn:** [warit-yuvaniyama](https://www.linkedin.com/in/warit-yuvaniyama/)
- **GitHub:** [@Warit-Yuv](https://github.com/Warit-Yuv)

## Selected Experience

- **Research Intern**, Measurement & Intelligence Systems Lab, Kansai University, Japan — mmWave radar and thermal imaging sensor fusion for autonomous navigation in degraded-visibility environments.
- **Intern**, NECTEC, NSTDA — Water surface level estimation using the Fast Segment Anything Model; published in Springer LNCS (IUKM 2025).
- **President & Embedded Systems Lead**, SIIT Robotic Club (OrcaBOT) — leading 30 members and competing in RoboCup Japan Open 2025.

## Repository Structure

- `Warit_CV.tex`, `Resume.tex`, `resume.cls` — LaTeX sources (class based on Trey Hunner's resume class)
- `.github/workflows/build.yml` — CI: compiles both documents and regenerates the PDFs and preview images in `assets/`

To build locally:

```
pdflatex -interaction=nonstopmode Warit_CV.tex
```

## License

The code and documents in this repository are provided under the [MIT License](LICENSE). The `resume.cls` template retains its original notice (© Trey Hunner).