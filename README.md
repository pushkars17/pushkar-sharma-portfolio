<div align="center">

# Pushkar Sharma — Personal Developer & AI/ML Portfolio

**AI & Machine Learning Developer • Data Analytics Undergraduate • Published Research Author**

[![Live Portfolio](https://img.shields.io/badge/Live_Portfolio-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://pushkar-sharma-portfolio.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-pushkars17-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pushkars17)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pushkar_Sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pushkar-sharma-80b587415)
[![Kaggle](https://img.shields.io/badge/Kaggle-pushkars17-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/pushkars17)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--6257--3094-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-6257-3094)

---

### 🌐 Live Deployment: [pushkar-sharma-portfolio.vercel.app](https://pushkar-sharma-portfolio.vercel.app)

</div>

## Overview

This repository hosts the source code and assets for my personal developer portfolio. Engineered as a zero-dependency, ultra-fast static web application, it serves as a unified showcase for my **machine learning systems, open-source Python packages, large-scale datasets, peer-reviewed research publications, intellectual property registrations, academic milestones, and verified industry specializations**.

Instead of relying on heavy frontend frameworks, the site is crafted with **pure Semantic HTML5, Modern CSS3, and Vanilla JavaScript**—delivering sub-second load times, smooth GPU-accelerated micro-interactions, and automatic continuous deployment via GitHub and Vercel.

---

## Key Features & Engineering Highlights

- **Zero-Build, High-Performance Architecture:** Single-file modular architecture (`index.html` + static assets) with zero npm bloat, zero bundler overhead, and instant edge caching on Vercel CDN.
- **Adaptive Dark & Light Mode Engine:** Persistent theme switching backed by CSS custom properties (`--bg`, `--card`, `--accent`, `--accent2`) and `localStorage` state synchronization.
- **Data-Driven Content Rendering:** Structured `DATA` configuration object dynamically renders metrics, project cards, research metadata, SGPA progress bars, and credential cards with built-in XSS escaping.
- **Interactive Micro-Animations & Accessibility:**
  - Real-time role typewriter effect and top scroll-progress bar
  - `IntersectionObserver`-triggered viewport reveals and animated metric counters
  - 3D cursor-reactive card tilt and radial spotlight hover effects
  - Full keyboard focus indicators and `prefers-reduced-motion` media query support

---

## Featured Projects & Open-Source Work

| Project / Artifact | Domain | Core Stack | Links |
| :--- | :--- | :--- | :--- |
| **SmartHire ML System** | Predictive Recruitment Analytics | `R`, `Random Forest`, `Tidymodels`, `Tidyverse` | [GitHub Repo ↗](https://github.com/pushkars17/SmartHire-ML-System) |
| **Multimodal Academic Intelligence Pipeline** | Deep Learning & Citation Graph Mining (`136K+` papers) | `Python`, `PyTorch`, `NetworkX`, `NLP`, `TF-IDF` | [GitHub Repo ↗](https://github.com/pushkars17/arxiv-dl-visualizer) |
| **ExplainViz (`v1.0.0`)** | Rule-Based Statistical Visualization & Bias Explanation Library | `Python 3.10+`, `Matplotlib`, `Statistics`, `PyPI` | [PyPI Package ↗](https://pypi.org/project/explainviz/) |
| **Indian Student Intelligence Dataset (`ISID-53K`)** | Synthetic Educational & Placement Dataset (`53,428` rows × `40` cols) | `Dataset`, `Pandas`, `ML Benchmarking`, `CC BY-SA 4.0` | [Kaggle Dataset ↗](https://www.kaggle.com/dsv/16989078) |

---

## Research & Intellectual Property

- **Peer-Reviewed Journal Publication:**  
  *Road Accident Risk Intelligence and Forecasting (RARIF) Framework using Machine Learning*  
  Published in **International Journal of Multidisciplinary and Scientific Emerging Research (IJMSERH)**, Vol. 13, Issue 3 (Jul–Sep 2025) | ISSN: `2349-6037` | Impact Factor: `9.274`  
  **DOI:** [`10.15662/IJMSERH.2025.1303073`](https://doi.org/10.15662/IJMSERH.2025.1303073)

- **Registered Software Copyright (Government of India):**  
  *Road Accident Risk Intelligence and Forecasting RARIF using Machine Learning*  
  **Certificate No:** `SW-2026022241` | **Application No:** `SW-35788/2025-CO` (Filed: 05 Sep 2025)

---

## Verified Specializations

| Specialization | Issuing Organization | Credential ID | Verification |
| :--- | :--- | :--- | :--- |
| **Applied Data Science with Python Specialization** *(5 Courses)* | University of Michigan (Coursera) | `4TUR3XYKM28P` | [Verify Credential ↗](https://coursera.org/verify/specialization/4TUR3XYKM28P) |
| **Meta Web Development Fundamentals Specialization** | Meta (Coursera) | `LZB2AGCOJC4C` | [Verify Credential ↗](https://coursera.org/verify/specialization/LZB2AGCOJC4C) |
| **AI Infrastructure Specialization** | NVIDIA (Coursera) | `VL3GH57TDMDR` | [Verify Credential ↗](https://coursera.org/verify/specialization/VL3GH57TDMDR) |

---

## Repository Structure

```text
pushkar-sharma-portfolio/
├── index.html      # Complete markup, responsive styling, theme engine, and structured portfolio data
├── profile.jpeg    # High-resolution portrait asset rendered in the hero section
└── README.md       # Project documentation and overview
```
Running LocallySince this project uses pure static web standards with no external build tools, you can run it locally in seconds:Bash# 1. Clone the repository
git clone [https://github.com/pushkars17/pushkar-sharma-portfolio.git](https://github.com/pushkars17/pushkar-sharma-portfolio.git)

# 2. Navigate into the directory
cd pushkar-sharma-portfolio

# 3. Serve locally (using Python's built-in HTTP server)
python -m http.server 8000
Then open http://localhost:8000 in your browser.
