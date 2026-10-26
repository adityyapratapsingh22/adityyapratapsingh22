<div align="center">
<img width="100%" src="https://raw.githubusercontent.com/adityyapratapsingh22/adityyapratapsingh22/main/assets/profile/masthead.svg" alt="Aditya Pratap Singh — Full-Stack Developer · Applied AI · Kanpur, India"/>
<br/>
<a href="https://github.com/adityyapratapsingh22" target="_blank"><img src="https://img.shields.io/badge/GITHUB-111a27?style=for-the-badge&logo=github&logoColor=9fb0c4"/></a>
<a href="https://www.linkedin.com/in/aditya-pratap-singh-909263333/" target="_blank"><img src="https://img.shields.io/badge/LINKEDIN-111a27?style=for-the-badge&logo=linkedin&logoColor=4aa8ff"/></a>
<a href="mailto:2k24.cs1b.2413601@gmail.com" target="_blank"><img src="https://img.shields.io/badge/EMAIL-111a27?style=for-the-badge&logo=gmail&logoColor=e8a33d"/></a>
 
<br/><br/>
 
<img src="https://komarev.com/ghpvc/?username=adityyapratapsingh22&style=flat-square&color=4aa8ff&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/adityyapratapsingh22?style=flat-square&color=111a27&labelColor=0a0f18&label=FOLLOWERS&logo=github&logoColor=9fb0c4"/>
<img src="https://img.shields.io/github/stars/adityyapratapsingh22?style=flat-square&color=111a27&labelColor=0a0f18&label=STARS&logo=github&logoColor=9fb0c4"/>
</div>

## 01 · Profile

<table>
<tr>
<td width="60%" valign="top">

I'm a **Full-Stack Developer** and B.Tech Computer Science student who builds AI-powered products end to end: computer-vision and deep-learning models in Python, served through APIs and surfaced in responsive React dashboards.

**My approach:** get the data model and API contract right first, build security in from the start, make model decisions explainable, and ship something a person can actually run and use.

**What I enjoy building:**  
→ Computer-vision systems that turn raw video into live analytics  
→ Deep-learning classifiers with explainable outputs  
→ Authenticated full-stack apps with APIs, history and dashboards  
→ Real-time and CRUD-heavy tools with proper RBAC

**Currently strengthening:** DSA, Python and SQL.

> *"Build with purpose. Ship with discipline. Improve relentlessly."*

</td>
<td width="40%" valign="top">

```yaml
profile:
  role:      Full-Stack Developer
  location:  Kanpur, Uttar Pradesh, India
  education: B.Tech CSE, PSIT Kanpur

status:
  availability: [open to internships / SDE roles]
  focus:        full-stack apps with applied AI

practice:
  building:  YatayatAi, Sentinel
  learning:  DSA, Python, SQL
```

</td>
</tr>
</table>

## 03 · Technical Systems

<div align="center">

| Languages | Frontend | Backend | Data | AI / Vision | Tooling |
|:---:|:---:|:---:|:---:|:---:|:---:|
| <img src="https://skillicons.dev/icons?i=python" width="34"/><br/>Python | <img src="https://skillicons.dev/icons?i=react" width="34"/><br/>React | <img src="https://skillicons.dev/icons?i=fastapi" width="34"/><br/>FastAPI | <img src="https://skillicons.dev/icons?i=sqlite" width="34"/><br/>SQLite | <img src="https://skillicons.dev/icons?i=pytorch" width="34"/><br/>PyTorch | <img src="https://skillicons.dev/icons?i=git" width="34"/><br/>Git |
| <img src="https://skillicons.dev/icons?i=ts" width="34"/><br/>TypeScript | <img src="https://skillicons.dev/icons?i=vite" width="34"/><br/>Vite | <img src="https://skillicons.dev/icons?i=nodejs" width="34"/><br/>Node.js | <img src="https://skillicons.dev/icons?i=mongodb" width="34"/><br/>MongoDB | <img src="https://skillicons.dev/icons?i=opencv" width="34"/><br/>OpenCV | <img src="https://skillicons.dev/icons?i=github" width="34"/><br/>GitHub |
| <img src="https://skillicons.dev/icons?i=js" width="34"/><br/>JavaScript | <img src="https://skillicons.dev/icons?i=tailwind" width="34"/><br/>Tailwind CSS | <img src="https://skillicons.dev/icons?i=express" width="34"/><br/>Express | <img src="https://img.shields.io/badge/SQL-111a27?style=flat-square&logo=mysql&logoColor=4aa8ff" height="20"/><br/>SQL | <img src="https://img.shields.io/badge/YOLO-111a27?style=flat-square&logoColor=white" height="20"/><br/>YOLO | <img src="https://img.shields.io/badge/Jupyter-111a27?style=flat-square&logo=jupyter&logoColor=e8a33d" height="20"/><br/>Jupyter |
| <img src="https://skillicons.dev/icons?i=html,css" width="34"/><br/>HTML / CSS | | <img src="https://img.shields.io/badge/JWT_·_RBAC-111a27?style=flat-square&logo=jsonwebtokens&logoColor=white" height="20"/><br/>JWT · RBAC | | | <img src="https://skillicons.dev/icons?i=vscode" width="34"/><br/>VS Code |

</div>

## 04 · Machine Intelligence

| Domain | Applied in practice |
|:---|:---|
| Computer Vision | Vehicle detection, tracking, counting and classification from traffic video with YOLO and OpenCV (YatayatAi) |
| Deepfake Detection | Dual-branch classifier combining an EfficientNet-B0 spatial branch with a 2D-FFT frequency branch, for images and video (Sentinel) |
| Explainable ML | Grad-CAM visual explanations for each prediction (Sentinel) |
| Model Evaluation | Cross-generator generalisation testing rather than a single in-distribution score (Sentinel) |
| Model Serving | PyTorch models behind FastAPI with authenticated React front ends |

## 05 · Selected Work

Individual projects, designed and built by me.

### 01 · YatayatAi
*AI traffic-video analytics · Individual project*

AI-powered traffic video analyzer that **detects, tracks, counts and classifies vehicles using YOLO**, estimates traffic density, and visualises the analytics on a **live dashboard**. Combines an OpenCV and Python computer-vision pipeline with a TypeScript and React front end.

`TypeScript` `React` `Python` `OpenCV` `YOLO` `Computer Vision`

🔗 [Live](https://yatayat-ai.vercel.app/) · [Source](https://github.com/adityyapratapsingh22/YatayatAi) · MIT License <!-- add one metric here (e.g. detection accuracy or FPS) -->

<br/>

### 02 · Sentinel
*Explainable deepfake detection · Individual project*

**Dual-branch deepfake detector (EfficientNet-B0 + 2D FFT)** for images and video. It pairs a spatial branch with a frequency-domain branch, explains each prediction with **Grad-CAM**, and ships with real authentication and per-account scan history. The model is tested for **cross-generator generalisation**, meaning how it holds up on fakes from generators it was not trained on.

`PyTorch` `Python` `FastAPI` `React` `Vite` `Tailwind CSS v4` `SQLite`

🔗 [Source](https://github.com/adityyapratapsingh22/Sentinel) <!-- add a Live link here once deployed, plus your headline result (e.g. accuracy / AUC on unseen generators) -->

## 06 · Experience

| Organisation | Role | Period | Focus |
|:---|:---|:---:|:---|
| **Prodigy InfoTech** | Full-Stack Web Development Intern | [July — August 2026] | Delivered four tasks as public repositories: a JWT + RBAC auth system, an employee management dashboard, an e-commerce platform and a Socket.IO real-time chat |

<!-- Add hackathons, job simulations, certifications and competitive-programming profiles here as they apply. Keep only the ones you can link or verify. -->

## 07 · Telemetry

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=adityyapratapsingh22&show_icons=true&hide_border=true&bg_color=0a0f18&title_color=4aa8ff&text_color=9fb0c4&icon_color=4aa8ff" alt="GitHub statistics"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityyapratapsingh22&layout=compact&hide_border=true&bg_color=0a0f18&title_color=4aa8ff&text_color=9fb0c4" alt="Most-used languages"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/adityyapratapsingh22/adityyapratapsingh22/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/adityyapratapsingh22/adityyapratapsingh22/output/github-contribution-grid-snake.svg"/>
    <img width="95%" alt="Contribution snake" src="https://raw.githubusercontent.com/adityyapratapsingh22/adityyapratapsingh22/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
</p>

## 08 · Contact

<div align="center">

| Channel | Address |
|:---|:---|
| GitHub | [github.com/adityyapratapsingh22](https://github.com/adityyapratapsingh22) |
| LinkedIn | [in/aditya-pratap-singh-909263333](https://www.linkedin.com/in/aditya-pratap-singh-909263333/) |
| Email | [2k24.cs1b.2413601@gmail.com](mailto:2k24.cs1b.2413601@gmail.com) |

<br/>

**Open to [internships / SDE roles] and open-source collaboration.**

<br/>

<sub>Kanpur, Uttar Pradesh, India</sub>

</div>
