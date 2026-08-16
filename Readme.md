# Zachary Ryan — Cybersecurity Portfolio

> U.S. Navy veteran and Robert Morris University cybersecurity student focused on security operations, AI security, research, governance, risk, and compliance.

[**View the live portfolio**](https://zachary200114.github.io/) · [View résumé](assets/Zachary-Ryan-Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/zachary-ryan01/) · [GitHub](https://github.com/Zachary200114)

## Overview

This repository contains the source for my personal cybersecurity portfolio. The site presents my education, professional experience, research, technical skills, and hands-on projects in one lightweight, responsive page.

The portfolio connects my operational background in the U.S. Navy’s Nuclear Reactor Department with my current work in cybersecurity. It emphasizes evidence-driven security decisions, clear documentation, practical technical work, and the relationship between security operations and governance, risk, and compliance.

## Portfolio highlights

- **Unified introduction** — A continuous hero and About section brings together my headshot, professional identity, background, and current areas of focus.
- **Career timeline** — A most-recent-first timeline covers my Brixmor Property Group cybersecurity internship and U.S. Navy experience.
- **Research** — Current work includes AI phishing evasion research and a cross-framework analysis of auditable evidence in AI cybersecurity compliance.
- **Project showcase** — Six projects include concise summaries, expandable technical details, technology tags, repository links, and authentic previews for featured work.
- **Interactive terminal** — A collapsed-by-default Fallout-inspired portfolio shell provides commands for exploring my background, experience, skills, projects, research, résumé, and contact information.
- **Responsive experience** — The layout, navigation, project cards, timeline, and terminal adapt for desktop, tablet, and phone screens.
- **Accessible interaction** — Semantic HTML, keyboard support, visible focus states, reduced-motion handling, descriptive labels, and safe external links are built into the page.

## Featured projects

| Project | Focus | Technology |
| --- | --- | --- |
| [AI Network Anomaly Lab](https://github.com/Zachary200114/ai-network-anomaly-lab) | Simulated network flows, Isolation Forest anomaly scoring, and dashboard visualization | FastAPI, React, SQLite, Docker |
| [AI-Powered Phishing Email Detector](https://github.com/Zachary200114/ai-phishing-detector) | Heuristic and header analysis, safe rewriting, and scan history | FastAPI, React, SQLite |
| [ThreatSequence](https://github.com/Zachary200114/ThreatSequence) | Simulated telemetry, incident timelines, and MITRE ATT&CK mapping | Next.js, React, TypeScript, Tailwind |

[Launch the ThreatSequence live demo](https://threat-sequence.vercel.app/)

Additional projects presented on the site:

- [Docker Network Segmentation & Attack Lab](https://github.com/Zachary200114/container-network-seg-lab)
- [Port Scanner](https://github.com/Zachary200114/Ports)
- [Password Cracker](https://github.com/Zachary200114/PasswordCracker)

## Research

### Evaluating AI vs Human Phishing Evasion Across Emulated Email Security Filters and SpamAssassin

Presented at the NEDSI Annual Conference on April 9, 2026, and published in the conference proceedings on pages 189–202.

[Read the NEDSI proceedings](https://nedsi.decisionsciences.org/wp-content/uploads/sites/5/2026/06/NEDSI-2026-Proceedings.pdf)

### Auditable Evidence in AI Cybersecurity Compliance: A Cross-Framework Analysis

Submitted to *Computers & Security* in June 2026. The research examines how governance, regulatory, and vendor frameworks define or imply the evidence needed to support cybersecurity assurance, compliance, and independent audits.

## Interactive portfolio terminal

The optional terminal expands from the About section and behaves like a small portfolio-focused shell. It includes:

- Profile, education, experience, skills, projects, research, achievements, résumé, and contact commands
- Shell-style navigation such as `ls`, `cd`, `cat`, `pwd`, `whoami`, `grep`, and `man zachary`
- Command history with the arrow keys and Tab completion
- Clickable, allowlisted links to professional profiles, repositories, publications, and the résumé
- Clearly labeled simulated sequences for portfolio scanning, skill analysis, SOC investigation, career tracing, and résumé decryption
- Reduced-motion-aware boot and simulation sequences

The terminal is a portfolio interface only. It does not execute operating-system commands or scan a live system.

## Visual system

- **Typography:** Playfair Display for the name and section headings, Montserrat for body copy and interface elements, and Share Tech Mono inside the terminal
- **Light mode:** Paper white and warm cream with forest, sage, and restrained moss accents
- **Dark mode:** Deep pine surfaces, warm off-white text, muted sage metadata, and calm moss controls
- **Theme behavior:** Light mode loads by default; visitors can switch themes during the current visit
- **Motion:** Subtle reveal effects and smooth expandable panels, with reduced-motion preferences respected

## Built with

- Semantic HTML5
- Modern CSS, including responsive layouts, custom properties, Grid, and Subgrid
- Vanilla JavaScript
- Google Fonts
- Devicon, Simple Icons, Lucide, and Bootstrap Icons assets
- GitHub Pages

The site intentionally remains framework-free. Its structure, styling, and behavior live primarily in `index.html`, while local media and documents are stored in `assets/`.

## Run locally

```bash
git clone https://github.com/Zachary200114/Zachary200114.github.io.git
cd Zachary200114.github.io
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

## Repository structure

```text
.
├── assets/
│   ├── project-screenshots/     # Authentic previews for featured projects
│   ├── Zachary-Ryan-Resume.pdf  # Current résumé
│   └── ...                      # Profile, skill, and contact assets
├── index.html                   # Portfolio content, styling, and interactions
└── Readme.md                    # Project overview and local setup
```

## Connect

- [Portfolio](https://zachary200114.github.io/)
- [LinkedIn](https://www.linkedin.com/in/zachary-ryan01/)
- [GitHub](https://github.com/Zachary200114)
- [Email](mailto:Zxrst175@mail.rmu.edu)

© 2026 Zachary Ryan. All rights reserved.
