<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=30&pause=1000&color=00F7FF&center=true&vCenter=true&width=650&lines=ADITYA+PRATAP+SINGH_;FULL+STACK+DEVELOPER;PYTHON+%26+DSA+ENTHUSIAST" alt="Typing SVG" />

**B.Tech CSE @ PSIT Kanpur | Full-Stack Developer (MERN) | Applied Deep Learning — Computer Vision & Deepfake Detection | Python · DSA · SQL**

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-pratap-singh-909263333)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityyapratapsingh22)
[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:2k24.cs1b.2413601@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=adityyapratapsingh22&style=for-the-badge&color=00F7FF&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/adityyapratapsingh22?style=for-the-badge&logo=github&label=FOLLOWERS&color=00F7FF)

</div>

---

## 🚀 About Me

- 🎓 **B.Tech in Computer Science & Engineering** — PSIT Kanpur
- 💻 Currently focused on **Full Stack Development** (MERN)
- 🐍 Sharpening skills in **Python, DSA, and SQL**
- 🧠 Building applied **Computer Vision / Deep Learning** projects — object detection, deepfake classification, model explainability
- 📍 Based in **Kanpur, Uttar Pradesh, India**
- 💬 Ask me about: **JavaScript, React, Node.js, MongoDB, Express, PyTorch**

## currently:

  - building: "Full-stack apps + applied AI/CV systems"
  - learning: "Data Structures & Algorithms, SQL, System Design fundamentals"
  - stack: "React · Node.js · Express · MongoDB · Python · PyTorch"


---

## 🎓 Education

<div align="center">

| | |
|---|---|
| **Degree** | B.Tech, Computer Science & Engineering |
| **Institute** | PSIT Kanpur |
| **Location** | Kanpur, Uttar Pradesh, India |

</div>

---

## 🛠️ How I Build

<div align="center">

| Languages | Frontend | Backend | Database | AI / ML | Tools |
|:---:|:---:|:---:|:---:|:---:|:---:|
| <img src="https://skillicons.dev/icons?i=python" width="40"/><br>Python | <img src="https://skillicons.dev/icons?i=react" width="40"/><br>React | <img src="https://skillicons.dev/icons?i=nodejs" width="40"/><br>Node.js | <img src="https://skillicons.dev/icons?i=mongodb" width="40"/><br>MongoDB | <img src="https://skillicons.dev/icons?i=pytorch" width="40"/><br>PyTorch | <img src="https://skillicons.dev/icons?i=git" width="40"/><br>Git |
| <img src="https://skillicons.dev/icons?i=js" width="40"/><br>JavaScript | <img src="https://skillicons.dev/icons?i=html" width="40"/><br>HTML5 | <img src="https://skillicons.dev/icons?i=express" width="40"/><br>Express | <img src="https://skillicons.dev/icons?i=sqlite" width="40"/><br>SQLite | <img src="https://skillicons.dev/icons?i=opencv" width="40"/><br>OpenCV | <img src="https://skillicons.dev/icons?i=github" width="40"/><br>GitHub |
| | <img src="https://skillicons.dev/icons?i=css" width="40"/><br>CSS3 | <img src="https://skillicons.dev/icons?i=fastapi" width="40"/><br>FastAPI | | | <img src="https://skillicons.dev/icons?i=vscode" width="40"/><br>VS Code |

</div>

---

## 📌 Pinned Repositories

| Repository | Description |
|---|---|
| 🚦 [**AI_Traffic_Analyzer**](https://github.com/adityyapratapsingh22/AI_Traffic_Analyzer) | AI-powered traffic video analyzer — detects, tracks, counts, and classifies vehicles with YOLO, estimates density, and visualizes it on a live authenticated dashboard |
| 🕵️ [**Deepfake_Detector**](https://github.com/adityyapratapsingh22/Deepfake_Detector) | Full-stack deepfake detection system — dual-branch EfficientNet + FFT image classifier, video pipeline, Grad-CAM explainability |

---

## 🚀 Featured Projects

### 1. 🚦 AI Traffic Analyzer

🔗 **Repo:** [View Source](https://github.com/adityyapratapsingh22/AI_Traffic_Analyzer)

- Built an **AI-powered traffic analytics platform** that detects, tracks, and classifies vehicles from video using **YOLOv8 + ByteTrack**, estimating live traffic density and streaming results over an **authenticated WebSocket**.
- Implemented full **JWT authentication** (access + refresh tokens, bcrypt hashing, email-based password reset) so every session, report, and analytics view is scoped to its owner.
- Built **server-generated PDF reports** (ReportLab + Matplotlib) and **cross-session aggregate analytics** via SQLAlchemy — busiest session, density distribution, day-by-day trends.
- Shipped a **React + TypeScript** frontend (Vite, Tailwind v4) with a live dashboard, searchable session history (CSV/PDF export), and a full settings/profile system.
- Found and fixed a critical detection bug where **pedestrians were being counted as vehicles** — added a strict vehicle-class allowlist to the pipeline.

### 2. 🕵️ Deepfake Detector

🔗 **Repo:** [View Source](https://github.com/adityyapratapsingh22/Deepfake_Detector)

- Built a **dual-branch deepfake classifier** (EfficientNet-B0 + a 2D-FFT frequency-analysis branch) that flags manipulated images and videos, with **Grad-CAM** explaining every prediction.
- Designed the **video pipeline** independently — frame sampling, per-frame inference, and aggregation-strategy testing (mean / max / variance) — reusing the image classifier as a per-frame feature extractor.
- Ran a **cross-generator generalization test**: hit **92.0% accuracy / 0.974 AUC-ROC** in-distribution, but watched fake-recall on an unseen generator (Stable Diffusion) collapse to **2.3%** — documented honestly instead of hidden behind one inflated number.
- Diagnosed a **0% recall on unseen face-swap video**, traced it to a training-distribution mismatch, and recovered it to **82% recall** via targeted fine-tuning on a held-out video split.
- Shipped the model behind a full-stack app: **FastAPI** backend (`/predict/image`, `/predict/video`), full auth + SQLite persistence, real SHA-256 detection history, and a **React** frontend (Landing, Login, Lab, History, Analytics, Profile).

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=adityyapratapsingh22&show_icons=true&theme=radical&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityyapratapsingh22&layout=compact&theme=radical&hide_border=true" />

</div>

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=adityyapratapsingh22&theme=react-dark&hide_border=true" />

</div>

## 🔥 Streak Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=adityyapratapsingh22&theme=highcontrast&hide_border=true" />

</div>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/adityyapratapsingh22/adityyapratapsingh22/output/github-contribution-grid-snake.svg" alt="Contribution Snake" />

</div>

<details>
<summary>⚙️ Setup (one-time — needed to activate the snake)</summary>

Add this file at `.github/workflows/snake.yml` in your **profile repo** (`adityyapratapsingh22/adityyapratapsingh22`):

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  push:
    branches:
      - main
  workflow_dispatch: {}

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Commit, push to `main`, and the snake image above will populate automatically once the Action runs.
</details>

---

<div align="center">

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-pratap-singh-909263333)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityyapratapsingh22)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:2k24.cs1b.2413601@gmail.com)

</div>
