# Zachary Ryan – Portfolio Website

This repository contains my personal cybersecurity portfolio website. The site introduces my background and highlights work in security operations, AI security, research, governance, risk, and compliance.

## **About the Website**

This is a single-page portfolio site that presents my background, education, experience, publications, projects, achievements, and contact information in one place.

The website highlights my transition from serving as a U.S. Navy Machinist's Mate in the Nuclear Reactor Department to studying cybersecurity at Robert Morris University and gaining experience in cybersecurity operations, vulnerability management, third-party risk management, and cybersecurity research.

## **Features**

- **Single-page portfolio layout:** Organized sections for About, Education, Skills, Experience, Publications, Projects, Achievements, and Contact.
- **Fixed navigation bar:** Allows visitors to quickly jump between major sections of the site.
- **Light-first theme:** Starts in light mode on every visit, with an optional dark-mode toggle for the current visit.
- **Responsive design:** Works across desktop and mobile screen sizes.
- **Scroll reveal animations:** Sections animate into view as the user scrolls.
- **Back-to-top button:** Allows quick navigation back to the top of the page.
- **Interactive portfolio terminal:** Fallout-style shell with structured commands for profile content, projects, research, contact links, theme control, simulated directories, command history, Tab completion, and clearly labeled fictional demos.
- **Publication section:** Highlights cybersecurity research on AI phishing evasion and auditable evidence in AI cybersecurity compliance.
- **Project cards:** Six cybersecurity and programming projects include expandable, native details with verified highlights, technology tags, and GitHub source links.
- **Featured project previews:** AI Network Anomaly Lab, AI-Powered Phishing Email Detector, and ThreatSequence are visibly marked Featured and include authentic interface previews; ThreatSequence is clearly identified as simulated data.
- **Research citations:** The presented NEDSI conference proceedings card offers an in-page citation view and a copy control with a safe fallback for restricted browser contexts.
- **Résumé actions:** The navigation provides separate View Résumé and Download PDF actions.
- **Skills hover halo:** Skills use a subtle circular accent halo that preserves icon clarity and reduced-motion support.
- **Contact icons:** Quick links to LinkedIn, GitHub, and email.

## **Portfolio Terminal**

The terminal is a keyboard-friendly alternate way to explore the same verified information shown on the page. Commands are case-insensitive, tolerate extra spacing, and use safe clickable links for the résumé, project repositories, GitHub, LinkedIn, publications, and email.

- **Profile and work:** `about`, `experience [--latest]`, `skills [--security|--development|--top]`, `education`, `achievements`, and `status`.
- **Projects and research:** `projects [--featured]`, `project <name>`, `research`, `analyze threatsequence`, `risk --summary`, and `trace experience`.
- **Connections:** `resume`, `github`, `linkedin`, and `contact`.
- **Shell-style navigation:** `ls`, `cat`, `cd`, `open`, `whoami`, `pwd`, `date`, `uname -a`, `grep`, `man zachary`, and `sudo hire zachary`.
- **Terminal controls:** `help [command]`, `history`, `clear`, `reboot`, and `theme <light|dark>`. Up/Down Arrow navigate visit history, Tab completes commands and contextual arguments, and Ctrl/Command+L clears the display.
- **Fictional demonstrations:** `scan portfolio`, `scan skills`, `soc --demo`, `decrypt resume`, and `clearance` are explicitly labeled simulations and do not scan live systems, access real telemetry, decrypt a file, or claim a government security clearance.

## **Main Sections**

- **About Me**
  - Introduces my background as a cybersecurity student at RMU and U.S. Navy veteran.
  - Emphasizes my interest in technical security, governance, risk, policy, accountability, and evidence-based security.

- **Education**
  - Highlights my B.S. Cybersecurity at Robert Morris University (Aug 2024–Dec 2026, GPA 3.91/4.0).
  - Includes academic recognition such as the Outstanding Cybersecurity Student Award and Dean’s List.

- **Skills**
  - Uses a focused 18-item grid to highlight security operations, scripting, cloud and container tooling, networking, governance and risk, and technologies used across current projects.

- **Experience**
  - Cybersecurity internship experience at Brixmor Property Group.
  - U.S. Navy experience in the Nuclear Reactor Department.
  - Focuses on cybersecurity operations, vulnerability management, risk analysis, documentation, access control, and mission-critical systems.

- **Publications**
  - Includes my NEDSI Annual Conference proceedings paper, presented Apr 9, 2026, on AI vs. human phishing evasion across emulated email security filters and SpamAssassin.
  - Includes my submitted Computers & Security research on auditable evidence in AI cybersecurity compliance.
  - Highlights research interests in AI security, cybersecurity policy, governance, compliance, and assurance.

- **Projects**
  - Showcases hands-on cybersecurity and development projects, including:
    - AI Network Anomaly Lab
    - AI-Powered Phishing Email Detector
    - Docker Network Segmentation & Attack Lab
    - Port Scanner
    - Password Cracker
    - ThreatSequence

- **Achievements & Activities**
  - Includes academic honors, cybersecurity club involvement, CTF participation, certifications, and scholarships.

- **Contact**
  - Provides quick links to LinkedIn, GitHub, and email.

## **Tech Stack**

The site is intentionally lightweight and built with core web technologies:

- **HTML** – Page structure and content.
- **CSS** – Layout, responsive design, typography, theme colors, cards, hover effects, dark mode styling, and animations.
- **JavaScript** – Per-visit dark mode toggle, scroll reveal animations, back-to-top behavior, citation copying with fallback support, synchronized project-detail behavior, and interactive terminal commands.
- **Google Fonts** – Typography for headings, body text, and terminal styling.
- **Devicon + Custom Icons** – Technology icons, security icons, and contact icons.
- **GitHub Pages** – Hosting for the live portfolio site.

## **File Structure**

```text
.
├── assets/
│   ├── *.png / *.svg              # Skill icons, profile image, logos, and custom assets
│   ├── project-screenshots/
│   │   └── *.webp                  # Authentic previews for the three featured projects
│   ├── Zachary-Ryan-Resume.pdf    # Resume linked from the navigation bar
│   └── ...                        # Other static assets
├── index.html                     # Main portfolio page with embedded CSS and JavaScript
└── Readme.md                      # Project documentation
```

## **How to View**

You can view the live site at:

```text
https://zachary200114.github.io/
```

Or run it locally:

```bash
git clone https://github.com/Zachary200114/Zachary200114.github.io.git
cd Zachary200114.github.io
```

Then open `index.html` in a web browser.

## **Current Research Focus**

My current cybersecurity interests center on security operations, AI security, research, governance, risk management, and compliance. In particular, I am interested in how organizations evaluate security controls, document evidence, manage AI-related cybersecurity risks, and prove that security requirements are being met.

This research direction is reflected in my publications and project work, including:

- AI phishing-evasion analysis and auditable evidence for AI cybersecurity compliance.
- Vulnerability management, third-party risk management, and security operations.
- Network segmentation and SOC-style anomaly detection.
- Secure system design and risk-informed security decision-making.

## **Future Improvements**

Some improvements I may add later include:

- Additional cybersecurity research write-ups.
- More detailed project case studies.
- Additional authentic previews for projects beyond the three featured projects.
- A dedicated blog or lab notes section.
- Additional performance optimization.
- An expanded research page.

## **Contact**

If you would like to connect or talk cybersecurity:

- **Email:** [Zxrst175@mail.rmu.edu](mailto:Zxrst175@mail.rmu.edu)
- **LinkedIn:** Zachary Ryan
- **GitHub:** Zachary200114

© 2026 Zachary Ryan. All rights reserved.
