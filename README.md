<!-- Banner -->
<p align="center">
  <img src="assets/banner.png" alt="Muhammad Talha — 3DGS • Compression • ML Systems" width="100%" />
</p>

<h1 align="center">Muhammad Talha</h1>
<p align="center">
  <b>PhD @ UMKC</b> · 3D Gaussian Splatting • Compression • ML Systems · Qualcomm R&D (’25)
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
- I work on **dynamic 3D Gaussian Splatting (3DGS) compression**: inter-prediction, vector quantization, and feature-aware coding for AR/VR & volumetric video.
- Built **InterGS**: bilateral + KNN hybrid predictors, per-group bit budgets, GPCC/LZMA integration, multi-frame chaining (I/P).
- Obsessive about **reproducibility**: RD curves (BD-Rate/PSNR), decode FPS, codebook dumps, and clean harnesses.

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

### 🧰 Tech Stack
<p>
  <!-- Hosted row (fast) -->
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,faiss,opencv,cmake,linux,git,github,latex&perline=10" alt="stack" />
</p>

<details>
<summary><b>Local icon fallback (never breaks)</b></summary>
<p>
  <img src="assets/icons/python.svg" height="28" alt="Python" />
  <img src="assets/icons/cplusplus.svg" height="28" alt="C++" />
  <img src="assets/icons/pytorch.svg" height="28" alt="PyTorch" />
  <img src="assets/icons/faiss.svg" height="28" alt="FAISS" />
  <img src="assets/icons/opencv.svg" height="28" alt="OpenCV" />
  <img src="assets/icons/cmake.svg" height="28" alt="CMake" />
  <img src="assets/icons/linux.svg" height="28" alt="Linux" />
  <img src="assets/icons/git.svg" height="28" alt="Git" />
  <img src="assets/icons/github.svg" height="28" alt="GitHub" />
  <img src="assets/icons/latex.svg" height="28" alt="LaTeX" />
</p>
</details>

---

### 📊 Reproducibility & Metrics
- **RD curves**: BD-Rate/PSNR with matched rate points.  
- **Decode performance**: ms/gaussian + FPS targets per sequence.  
- **Artifacts**: quant configs, codebook dumps, predictor-choice streams, geometry bytes.

---

### 📫 Contact
<!-- Contact: icons only -->
<p align="center">
  <!-- Email -->
  <a href="mailto:your@email" title="Email">
    <img src="https://skillicons.dev/icons?i=gmail" height="34" alt="Email">
  </a>&nbsp;&nbsp;

  <!-- LinkedIn -->
  <a href="https://linkedin.com/in/your-id" title="LinkedIn">
    <img src="https://skillicons.dev/icons?i=linkedin" height="34" alt="LinkedIn">
  </a>&nbsp;&nbsp;

  <!-- X / Twitter -->
  <a href="https://x.com/your-id" title="X / Twitter">
    <img src="https://skillicons.dev/icons?i=twitter" height="34" alt="X">
  </a>&nbsp;&nbsp;

  <!-- Google Scholar (local) -->
  <a href="https://scholar.google.com/citations?user=YOUR_ID" title="Google Scholar">
    <img src="assets/icons/scholar.svg" height="34" alt="Google Scholar">
  </a>&nbsp;&nbsp;

  <!-- ORCID (local) -->
  <a href="https://orcid.org/0000-0000-0000-0000" title="ORCID">
    <img src="assets/icons/orcid.svg" height="34" alt="ORCID">
  </a>&nbsp;&nbsp;

  <!-- (Optional) ResearchGate (local) -->
  <!-- <a href="https://www.researchgate.net/profile/Your-Name" title="ResearchGate">
    <img src="assets/icons/researchgate.svg" height="34" alt="ResearchGate">
  </a> -->
</p>


<sub>Accent color: `#0ea5e9` (swap to `#7c3aed` purple if preferred). Keep it consistent across badges.</sub>
