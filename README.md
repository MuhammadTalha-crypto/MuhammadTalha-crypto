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
  <a href="#-tech-stack">Tech Stack</a> ·
  <a href="#-contact">Contact</a>
</p>

---

### 👋 About
- Researching **dynamic 3D Gaussian Splatting compression** (inter-prediction, vector quantization) for AR/VR & volumetric video.  
- Built **InterGS**: bilateral + KNN hybrid predictors, per-group bit budgets, GPCC/LZMA integration, and multi-frame chaining.  
- I like clean **RD curves (BD-Rate/PSNR)**, reproducible scripts, and decode-time profiling.

---

### 🎯 Research Focus
- **Temporal prediction for 3DGS**: feature-level inter-frame prediction (I/P chains), predictor selection streams.
- **Quantization**: residual scalar/VQ (codebooks for SH_DC/SH_AC), PCA/whitening, K-means codebooks.
- **Geometry & entropy**: GPCC geometry coding, LZMA/7-Zip integration, per-group bit budgeting.
- **Evaluation**: BD-Rate vs baselines, PSNR stability across frames, decode FPS targets.

---

### 📄 Research Papers
> Add DOI/arXiv links as they go live. Keep titles concise and outcome-oriented.

| Year | Venue | Title | Status | Links |
|-----:|:-----:|:------|:------:|:------|
| 2025 | VCIP | **InterGS: Inter-Frame Prediction for Dynamic 3D Gaussian Splatting** | accepted (camera-ready) | ⟦PDF⟧ ⟦Poster⟧ |
| 2026 | DCC (target) | **InterGS-VQ: Feature-Aware Vector Quantization for Dynamic 3DGS** | in preparation | ⟦draft⟧ |

> Want me to add a mini abstract block per paper? I can scaffold them under collapsible sections.

---

### 🧠 Patents & IP
> Use the notes you already have (e.g., “IDF 2507738”) and update as they progress.

| ID / Ref | Title | Area | Status |
|:--------:|:------|:-----|:------:|
| ⟦IDF 2507738⟧ | **Dynamic Inter-Prediction for 3D Gaussian Splatting** | 3DGS compression | filed / pending |
| ⟦IDF …⟧ | **Per-Group VQ for SH/DC+AC with Predictor Choice Streams** | quantization | drafting |

---

### 🔬 Research Projects
> Pin these repos to your profile (Customize Profile → Pinned).

#### 🟦 InterGS-VQ
- Vector-quantization for SH coefficients, per-group bit allocation, multi-frame chaining (I + P frames).  
- Reproducible RD scripts, codebook dumps, predictor choice traces.

#### 🟩 CompGS++ Comparisons
- Baseline parity, BD-Rate utility, and plotting kit for fair comparisons.  
- Geometry caching, consistent PSNR eval, scripts for rate points r01–r05/r06.

#### 🟨 Meta Hacker Cup 2025 — Round_1 (Python)
- Clean I/O (`Case #x:`), test harness (`tools/test.py`), samples, and concise write-ups.

---

### 🧰 Tech Stack
<p>
  <!-- Reliable hosted icons -->
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,faiss,opencv,cmake,linux,git,github,latex&perline=10" alt="stack" />
</p>

<details>
<summary>Local icon fallback (never breaks)</summary>

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

### 🧪 Reproducibility & Metrics
- **RD curves**: BD-Rate/PSNR plotted with matched rate points.  
- **Decode performance**: ms/gaussian + FPS targets, per-sequence breakdowns.  
- **Logs & Artifacts**: codebook dumps, quant configs, predictor-choice streams, geometry bytes.

---

### 📫 Contact
- Email: ⟦your@email⟧  
- LinkedIn: ⟦link⟧  
- X/Twitter: ⟦link⟧
