# Ibrahim Sulyman – Cloud & DevOps Engineer 

![Build Resume PDF](https://github.com/Thcosmonaut77/RESUME-SITE/actions/workflows/pdf.yaml/badge.svg)
[![Latest Resume](https://img.shields.io/github/release/Thcosmonaut77/RESUME-SITE.svg?label=Download%20Resume)](https://github.com/Thcosmonaut77/RESUME-SITE/releases/tag/resume-latest)
[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-brightgreen)](https://thcosmonaut77.github.io/RESUME-SITE/)

A static resume website with automated PDF generation using GitHub Actions, Node.js, and Puppeteer.


This repository contains my **resume website** built with HTML & CSS, hosted on **GitHub Pages**, and automatically exported to **PDF** for easy sharing.

---

## 🌐 Live Resume
🔗 [View Resume Online](https://thcosmonaut77.github.io/RESUME-SITE/)

---

## 📄 Download Resume (PDF)
The latest version of my resume is always available here:  
🔗 [Download Resume (PDF)](https://thcosmonaut77.github.io/RESUME-SITE/resume.pdf)

---

## ⚡ Features
- Responsive, clean **HTML/CSS** layout
- Hosted for free on **GitHub Pages**
- Auto-generated **resume.pdf** using **GitHub Actions + Puppeteer**
- Print-optimized styles for professional PDF export

---

## 🧑‍💻 Skills Demonstrated
- CI/CD pipeline automation with **GitHub Actions**
- Artifact generation and management (**resume.pdf**)
- Static site hosting on **GitHub Pages**
- **Idempotent automation** (avoiding redundant commits)

---

## 🛠 Repo Structure
```bash
resume-site/
│
├── index.html # Resume (main entry point)
├── css/
│ └── style.css # Stylesheet
│
├── export-pdf.js # Puppeteer script (for PDF generation)
│
├── .github/
│ └── workflows/
│ └── pdf.yml # GitHub Action workflow
│
└── resume.pdf # Auto-generated PDF (not committed manually)
```


---

## 🔄 PDF Automation
- On every push to `main`, GitHub Actions runs:
  - Uses **Puppeteer** to render `index.html` → `resume.pdf`
  - Commits `resume.pdf` back to the repo
- Ensures that **online resume** and **downloadable PDF** are always in sync.

---

## 📬 Contact
- 📧 Email: [ibrahim.sulyman777@gmail.com](mailto:ibrahim.sulyman777@gmail.com)  
- 💼 LinkedIn: [linkedin.com/in/ibrahim-sulyman-897a5b382](https://www.linkedin.com/in/ibrahim-sulyman-897a5b382)  
- 🖥 GitHub: [github.com/Thcosmonaut77](https://github.com/Thcosmonaut77)  

---

© 2025 Ibrahim Sulyman
