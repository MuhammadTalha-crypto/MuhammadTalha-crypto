
<p align="center">
  <img src="assets/banner.png" alt="Muhammad Talha — 3DGS • Compression • ML Systems" width="100%" />
</p>

<h1 align="center">Muhammad Talha</h1>
<p align="center">
  <b>PhD @ UMKC</b> • Ex-Intern Qualcomm R&D (’25) • 3D Gaussian Splatting • 3D Point Clouds <br> • Denoising/Deblocking • Graph Signal Processing • Compression 
</p>

<p align="center">
  <a href="https://github.com/MuhammadTalha-crypto?tab=followers">
    <img alt="Followers" src="https://img.shields.io/github/followers/MuhammadTalha-crypto?style=for-the-badge&label=Followers&color=0ea5e9" />
  </a>
  <a href="mailto:⟦your@email⟧">
    <img alt="Email" src="https://img.shields.io/badge/Email-Contact-0ea5e9?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="⟦your-linkedin⟧">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0ea5e9?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <a href="#-about">About</a> ·
  <a href="#-research-focus">Research Focus</a> ·
  <a href="#-research-papers">Research Papers</a> ·
  <a href="#-patents--ip">Patents & IP</a> ·
  <a href="#-research-projects">Research Projects</a> ·
  <a href="#-awards--achievements">Awards & Achievements</a> ·
  <a href="#-tech-stack">Tech Stack</a> ·
  <a href="#-contact">Contact</a>
</p>

---

### 👋 About
- I work on **dynamic 3D Gaussian Splatting (3DGS) compression**: inter-prediction, and feature-aware coding for AR/VR & 3D immersive/volumetric video.
- Developed First-ever & light-weight inter-prediction Framework for 3DGS (Gaussian Splatting) for All tracked, Semi-Tracked and Untracked Dynamice 3D Sequences for Potential use in real-time AR/VR, immersive video applications.   
- Developed First-ever attributes based deblocing framework for 3D Point clouds to remove the coding induced artifacts.
- 

---

### 🎯 Research Focus
- **Temporal prediction for 3DGS**: per-Gaussian inter-frame predictors and mode selection streams.  
- **Quantization**: VQ for SH_DC/SH_AC (PCA/whitening, K-means), scalar baselines.  
- **Geometry & entropy**: GPCC geometry, LZMA/7-Zip, per-group bit allocation.  
- **Evaluation**: BD-Rate vs baselines, PSNR stability across frames, ms/gaussian → FPS.

---

### 📄 Research Papers
> Add DOIs/arXiv as they go live. Keep titles concise and outcome-oriented.

| Year | Venue | Title | Status | Links |
|-----:|:-----:|:------|:------:|:------|
| 2025 | VCIP | **InterGS: Inter-Frame Prediction for Dynamic 3D Gaussian Splatting** | accepted | ⟦PDF⟧ ⟦Poster⟧ |
| 2026 | DCC (target) | **InterGS-VQ: Feature-Aware Vector Quantization for Dynamic 3DGS** | in prep | ⟦draft⟧ |

<details>
<summary><b>Mini abstracts</b></summary>

- **InterGS (VCIP 2025).** Predict current-frame Gaussian attributes from a reference I-frame; transmit residuals only. Dual predictor (bilateral + KNN) with per-Gaussian mode selection cuts bitrate while preserving photorealistic quality.

- **InterGS-VQ (DCC 2026, target).** Vector-quantize SH_DC/SH_AC with feature-aware codebooks, keeping opacity/scale/rot scalar. Gains in BD-Rate with stable PSNR across multi-frame chains.
</details>

---

### 🧠 Patents & IP
| ID / Ref | Title | Area | Status |
|:--------:|:------|:-----|:------:|
| ⟦IDF 2507738⟧ | **Dynamic Inter-Prediction for 3D Gaussian Splatting** | 3DGS compression | filed / pending |
| ⟦IDF …⟧ | **Per-Group VQ for SH/DC+AC with Predictor Choice Streams** | quantization | drafting |

---

### 🔬 Research Projects
> Pin these three (Customize Profile → Pinned).

#### 🟦 InterGS-VQ
Vector-quantization for SH coefficients, per-group bit budgets, multi-frame chaining (I + P). Includes RD scripts, predictor traces, and codebook dumps.

#### 🟩 CompGS++ Comparisons
Baseline parity, BD-Rate utility, plotting kit; geometry caching and consistent PSNR evaluation across rate points (r01–r05/06).

#### 🟨 Meta Hacker Cup 2025 — Round_1 (Python)
Clean I/O (`Case #x:`), sample harness, concise write-ups.

---

### 🏆 Awards & Achievements
- **Meta Hacker Cup 2025** participant (Round 1 solutions public).  
- **Qualcomm Multimedia R&D** (’25): inter-prediction for 3DGS (patent-pending).  
- **VCIP 2025** paper accepted; **DCC 2026** extension in progress.

---

<h3 id="stack">🧰 Tech Stack</h3>

<!-- Row 1: Core / Systems -->
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,cmake,git,github,linux,ubuntu,bash,vscode,neovim,docker&perline=12" height="32" alt="Core stack">
  <br/>
  <!-- Row 2: ML / Vision -->
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn,numpy,scipy,pandas,matplotlib,jupyter,latex&perline=12" height="32" alt="ML & Vision">
  <br/>
  <!-- Row 3: Infra / Cloud -->
  <img src="https://skillicons.dev/icons?i=nvidia,githubactions,aws,gcp,cloudflare&perline=12" height="32" alt="Infra">
</p>

<!-- Not on skillicons: use reliable pills so they never break -->
<p align="center">
  <a href="https://github.com/facebookresearch/faiss" title="FAISS">
    <img src="https://img.shields.io/badge/FAISS-0ea5e9?style=for-the-badge&labelColor=111&color=0ea5e9" height="22" alt="FAISS">
  </a>&nbsp;
  <a href="https://github.com/MPEGGroup/mpeg-pcc-tmc13" title="MPEG GPCC">
    <img src="https://img.shields.io/badge/MPEG%20GPCC-555?style=for-the-badge&labelColor=111&color=555" height="22" alt="MPEG GPCC">
  </a>
</p>


---

### 📊 Reproducibility & Metrics
- **RD curves**: BD-Rate/PSNR with matched rate points.  
- **Decode performance**: ms/gaussian + FPS targets per sequence.  
- **Artifacts**: quant configs, codebook dumps, predictor-choice streams, geometry bytes.

---

### 📫 Contact
<p align="center">
  <!-- Email -->
  <a href="mailto:YOUR_EMAIL" title="Email">
    <img src="https://skillicons.dev/icons?i=gmail" height="34" alt="Email">
  </a>&nbsp;&nbsp;

  <!-- LinkedIn -->
  <a href="https://linkedin.com/in/YOUR_ID" title="LinkedIn">
    <img src="https://skillicons.dev/icons?i=linkedin" height="34" alt="LinkedIn">
  </a>&nbsp;&nbsp;

  <!-- X / Twitter -->
  <a href="https://x.com/YOUR_ID" title="X / Twitter">
    <img src="https://skillicons.dev/icons?i=twitter" height="34" alt="X">
  </a>&nbsp;&nbsp;

  <!-- Google Scholar (Simple Icons CDN, brand blue) -->
  <a href="https://scholar.google.com/citations?user=YOUR_ID" title="Google Scholar">
    <img src="https://cdn.simpleicons.org/googlescholar/4285F4" height="34" alt="Google Scholar">
  </a>&nbsp;&nbsp;

  <!-- ORCID (Simple Icons CDN, brand green) -->
  <a href="https://orcid.org/0000-0000-0000-0000" title="ORCID">
    <img src="https://cdn.simpleicons.org/orcid/A6CE39" height="34" alt="ORCID">
  </a>
</p>
