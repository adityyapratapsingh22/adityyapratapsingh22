<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=28&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Aditya+Pratap+Singh+%F0%9F%91%8B;Full+Stack+Developer;Python+%26+DSA+Enthusiast;Building+AI-Powered+Applications" alt="Typing SVG" />

### Full Stack Developer · Python & DSA Enthusiast · B.Tech CSE @ PSIT Kanpur

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-pratap-singh-909263333)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityyapratapsingh22)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:2k24.cs1b.2413601@gmail.com)

</div>

---

## 🚀 About Me

- 🎓 **B.Tech in Computer Science & Engineering** — PSIT Kanpur
- 💻 Currently focused on **Full Stack Development** (MERN)
- 🐍 Sharpening skills in **Python, DSA, and SQL**
- 📍 Based in **Kanpur, Uttar Pradesh, India**
- 💬 Ask me about: **JavaScript, React, Node.js, MongoDB, Express**
- 🧠 Also building hands-on projects in **Computer Vision & Applied Deep Learning** (see below)

```yaml
currently:
  building: "Full-stack apps + AI-powered systems (computer vision, deep learning)"
  learning: "Data Structures & Algorithms, SQL, System Design fundamentals"
  stack: "React · Node.js · Express · MongoDB · Python"
```

---

## 🎓 Education

| | |
|---|---|
| **Degree** | B.Tech, Computer Science & Engineering |
| **Institute** | PSIT Kanpur |
| **Location** | Kanpur, Uttar Pradesh, India |

---

## 🛠️ Tech Stack

<div align="center">

![Skills](https://skillicons.dev/icons?i=js,html,css,react,nodejs,express,mongodb,python,pytorch,opencv,fastapi,git,github,vscode)

</div>

| Category | Technologies |
|---|---|
| **Languages** | JavaScript, Python |
| **Frontend** | React, HTML5, CSS3 |
| **Backend** | Node.js, Express, FastAPI |
| **Database** | MongoDB, SQLite |
| **AI / ML** | PyTorch, OpenCV, YOLO, MTCNN, Grad-CAM |
| **Tools** | Git, GitHub, VS Code |

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=adityyapratapsingh22&show_icons=true&theme=radical&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityyapratapsingh22&layout=compact&theme=radical&hide_border=true" />

<img src="https://streak-stats.demolab.com/?user=adityyapratapsingh22&theme=radical&hide_border=true" />

</div>

> Stats above are **live and auto-updating** via [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) — no numbers are hardcoded.

---

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/adityyapratapsingh22/adityyapratapsingh22/output/github-contribution-grid-snake.svg" alt="Contribution Snake" />

</div>

<details>
<summary>⚙️ How this is generated (setup instructions)</summary>

This animated snake eats your real contribution graph and is generated automatically by a GitHub Action. To activate it on your profile repo, add this file at `.github/workflows/snake.yml`:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # runs daily
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

Commit it, push to `main`, and the Action will populate the `output` branch with the SVG referenced above.
</details>

---

## 🚀 Featured Projects

### 1. 🚦 AI Traffic Analyzer

[![Repo](https://img.shields.io/badge/Repo-View_Source-181717?logo=github&logoColor=white)](https://github.com/adityyapratapsingh22/AI_Traffic_Analyzer)
![Stars](https://img.shields.io/github/stars/adityyapratapsingh22/AI_Traffic_Analyzer?style=social)

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-purple?logo=yolo&logoColor=white)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-v4-06B6D4?logo=tailwindcss&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite&logoColor=white)
![JWT](https://img.shields.io/badge/Auth-JWT-black?logo=jsonwebtokens&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered traffic video analysis system that detects, tracks, counts, and classifies vehicles in real time — turning any uploaded video into structured traffic data behind a **real, backend-enforced authentication system**.

**Key Features**
- 🚗 **Vehicle Detection** — pretrained YOLO detects car, bus, truck, motorcycle, and bicycle per frame, with a strict vehicle-only class filter
- 🎯 **Multi-Object Tracking** — ByteTrack assigns each vehicle a persistent ID across frames to avoid double-counting
- 📏 **Line-Crossing Counting** — accurate one-time counts per vehicle, broken down by class
- 🌡️ **Density Estimation** — live congestion level (Light / Moderate / Heavy), smoothed over a rolling window
- ⚡ **Real-Time Streaming** — live analytics pushed to the browser over an authenticated WebSocket
- 🔐 **Real Authentication** — JWT access + refresh tokens, bcrypt password hashing, email-based password reset (Gmail SMTP)
- 📄 **PDF Reports** — server-generated reports with embedded trend charts and per-class breakdowns (ReportLab + Matplotlib)
- 📈 **Aggregate Analytics** — cross-session insights: total vehicles counted, density distribution, busiest session, daily activity trend
- 👤 **Real User Profiles** — editable info, secure password change, lifetime stats, photo upload

**Tech Stack**

| Layer | Technology |
|---|---|
| Computer Vision | Ultralytics YOLO (YOLOv8 / YOLO26) + OpenCV |
| Tracking | ByteTrack |
| Backend | Python, FastAPI, WebSockets |
| Auth | JWT (access + refresh), bcrypt, Gmail SMTP |
| Reporting | ReportLab + Matplotlib |
| Analytics | SQLAlchemy aggregate queries |
| Frontend | React + TypeScript, Vite, Tailwind CSS v4 |
| Database | SQLite via SQLAlchemy |

<details>
<summary>🔧 Quality Assurance & Bug Fixes (documented for transparency)</summary>

| Issue | Severity | Fix |
|---|---|---|
| Pedestrians and other non-vehicle COCO classes were being tracked and counted | 🔴 Critical | Added an explicit `VEHICLE_CLASSES` allowlist — only car, truck, bus, motorcycle, bicycle are counted |
| Token auto-refresh was inconsistent across service files | 🟠 Bug | Centralized all refresh logic into one shared `httpClient.ts` |
| Profile photo could show a stale cached image after re-upload | 🟡 Bug | Added an `avatarVersion` counter to bust the image cache |
| Pipeline crash mid-analysis failed silently | 🟠 Robustness | WebSocket handler now catches exceptions, logs server-side, sends a clean error to the client |
| Failed density-alert email failed silently with no record | 🟡 Robustness | Wrapped in a logged, error-handled function |

</details>

---

### 2. 🕵️ Deepfake Detector

[![Repo](https://img.shields.io/badge/Repo-View_Source-181717?logo=github&logoColor=white)](https://github.com/adityyapratapsingh22/Deepfake_Detector)

![Python](https://img.shields.io/badge/Python-PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![EfficientNet](https://img.shields.io/badge/Model-EfficientNet--B0-orange)
![GradCAM](https://img.shields.io/badge/Explainability-Grad--CAM-yellow)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react&logoColor=black)
![MTCNN](https://img.shields.io/badge/Face_Detection-MTCNN-blue)

A full-stack system that classifies uploaded **images and videos** as real or AI-generated/manipulated, combining a fine-tuned CNN image classifier with a temporal aggregation layer for video, and explaining every prediction with a Grad-CAM heatmap.

**Key Features**
- 🧠 **Dual-Branch Image Classifier** — fine-tuned EfficientNet-B0 fused with a 2D FFT frequency-domain branch to catch GAN upsampling artifacts
- 👤 **Face Detection & Cropping** — MTCNN isolates the face region before classification for far higher accuracy
- 🔍 **Grad-CAM Explainability** — every prediction ships with a heatmap showing *why* it was flagged
- 🎞️ **Video Pipeline** — frame sampling + per-frame inference, with mean/max/variance aggregation strategies tested and a video-level train/test split (fine-tuned on video frames, not just images)
- 🔐 **Full Authentication** — signup/login/forgot/reset, backed by SQLite persistence
- 🗂️ **Detection History** — real SHA-256-based history, filterable and paginated
- 📊 **Analytics** — real aggregate queries, not mocked data
- 👤 **Profile Management** — edit info, change password, photo upload
- 🖥️ **React Frontend** — Landing, Login, Lab, History, Analytics, and Profile pages, all wired to the real backend

**Tech Stack**

| Layer | Technology |
|---|---|
| Deep Learning | PyTorch, EfficientNet-B0 (dual-branch: CNN + 2D FFT) |
| Face Detection | MTCNN |
| Explainability | Grad-CAM |
| Backend | FastAPI (`/predict/image`, `/predict/video`) |
| Database | SQLite |
| Frontend | React |

**📊 Dataset Notes**
- **Images:** 140k Real and Fake Faces (StyleGAN, Kaggle) — a 3,000-image working subset used for fast iteration
- **Cross-generator test set:** Stable Diffusion Face Dataset (Kaggle) — used specifically to test generalization to an unseen generation method
- **Video:** SDFVD (Small-scale Deepfake Forgery Video Dataset) — 53 real + 53 fake videos, split 80/20 **by video** (not by frame) to prevent data leakage

**🔬 Research Findings**

> The most valuable result in this project isn't the headline accuracy — it's what happens outside the training distribution.

| Scenario | Result |
|---|---|
| In-distribution (StyleGAN images, held-out test set) | **92.0% accuracy, 0.974 AUC-ROC** |
| Out-of-distribution images (Stable Diffusion, unseen) | Fake recall collapsed from 90% → **2.3%**, confidently wrong |
| Out-of-distribution video (face-swap, unseen) | **50% accuracy / 0% fake recall** — every video called "real" |
| Face-swap video, after targeted fine-tuning | **77% accuracy / 82% fake recall** on held-out videos |

The model learned StyleGAN-specific frequency artifacts, not a general notion of "fakeness" — and it failed *confidently*, not uncertainly, on unseen manipulation types. Exposing it to a small amount of representative data recovered real detection capability. This is documented honestly rather than hidden behind a single inflated accuracy number.

<details>
<summary>✅ Project Task Tracker</summary>

**Phase 1–2: Image Classifier**

| Task | Status |
|---|---|
| Environment setup (PyTorch + CUDA) | ✅ Done |
| Face detection/cropping (MTCNN) | ✅ Done |
| EfficientNet-B0 fine-tuning | ✅ Done |
| 2D FFT frequency branch (dual-branch fusion) | ✅ Done |
| Grad-CAM explainability | ✅ Done |
| Cross-generator generalization testing | ✅ Done |

**Phase 3: Video Pipeline**

| Task | Status |
|---|---|
| Frame sampling + per-frame inference | ✅ Done |
| Aggregation strategy testing (mean/max/variance) | ✅ Done |
| Video-level train/test split, fine-tuning on video frames | ✅ Done |

**Phase 4: Backend & Frontend**

| Task | Status |
|---|---|
| FastAPI backend with `/predict/image`, `/predict/video` | ✅ Done |
| Auth (signup/login/forgot/reset), SQLite persistence | ✅ Done |
| Detection history (real SHA-256, filterable, paginated) | ✅ Done |
| Analytics (real aggregate queries) | ✅ Done |
| Profile (edit info, change password, photo upload) | ✅ Done |
| React frontend (Landing, Login, Lab, History, Analytics, Profile) | ✅ Done |

**Deployment & Extras**

| Task | Status |
|---|---|
| Docker packaging | ❌ Not started |
| Cloud deployment | ❌ Not started |

</details>

<details>
<summary>🔧 Quality Assurance & Bug Fixes (documented for transparency)</summary>

| Issue | Severity | Fix |
|---|---|---|
| Frozen CNN backbone gave near-random (~52%) accuracy | 🔴 Critical | Unfroze and fully fine-tuned the backbone — accuracy jumped to 83%+ |
| Wrong image normalization (plain 0.5 mean/std instead of ImageNet stats) | 🟠 Bug | Corrected to proper ImageNet mean/std, fixing degraded feature quality |
| `numpy` 2.x silently breaking `torch`/`facenet-pytorch` compatibility | 🟠 Robustness | Pinned `numpy<2.0.0`; recurred multiple times from transitive installs and was fixed each time |
| Grad-CAM silently failing on every single request | 🔴 Critical | The library calls `model(input_tensor)` with one argument, but the dual-branch model needs two (`img`, `fft_feat`) — fixed with a per-request adapter module that wraps the model and closes over the fixed FFT features |
| Model gave unstable, near-random output after loading from checkpoint | 🟠 Bug | Missing `.eval()` call after reloading — model was left in training mode, destabilizing BatchNorm behavior |
| Model completely failed to detect face-swap video deepfakes (0% recall) | 🔴 Critical / Model | Root-caused to a distribution mismatch (model only ever saw StyleGAN stills); fixed via targeted fine-tuning on a held-out video split — recall recovered to 82% |

</details>

---

## 📫 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-pratap-singh-909263333)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityyapratapsingh22)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:2k24.cs1b.2413601@gmail.com)

*"A simple system that works beats a complex one that doesn't."*

</div>
