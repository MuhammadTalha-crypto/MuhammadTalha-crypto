
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

<!-- Right-side GIFs -->

<table>
  <tr>
    <td>

### 👋 About
- I work on **dynamic 3D Gaussian Splatting (3DGS) compression**: inter-prediction, and feature-aware coding for AR/VR & 3D immersive/volumetric video.
- Developed InterGS: First-ever & light-weight inter-prediction Framework for 3DGS (Gaussian Splatting) for All tracked, Semi-Tracked and Untracked Dynamic 3D Sequences for potential use in real-time AR/VR, immersive video applications.
- Developed MUSCON: First-ever attributes-based deblocking framework for 3D point clouds to remove coding-induced artifacts.
- Developed J-SGFT: First-ever attributes-based deblocking framework in purely frequency domain that beats previous SOTA algorithms.

    </td>
    <td width="260" align="right">

<img align="right" src="https://cdn.prod.website-files.com/62ce5d829e01c60b7c148396/66f38e6b9b32738d8412b5f9_teams-3dgs.gif" width="220" alt="InterGS demo 1">
<br clear="right">
<img align="right" src="https://aniqueakhtar.github.io/Figures/Geometry_prediction.gif" width="220" alt="InterGS demo 1">   
<br clear="right">
<img align="right" src="https://i.pinimg.com/originals/26/7b/5f/267b5f806c7eec3d72058a597a06adb1.gif" width="220" alt="InterGS demo 3">
<br clear="right">

</td>
  </tr>
</table>

---
### 🎯 PhD Research Focus
- **Temporal prediction for 3DGS**: inter-Frame Prediction Framework for AR/VR applications. 
- **Intra-frame Coding** for 3D Gaussian Splatting Sequences.  
- **Quantization**: Vector Quantization, Learned Codebooks for efficient compresison of SH channel of 3DGS.
- **Geometry & entropy**: GPCC geometry, LZMA/7-Zip, per-group bit allocation.  
- **3D Point Clouds**: Denoising, Deblocking as a post-processing framework to remove  coding induced artifacts.
- **Graph Fourier Transform**: Signal Processing, Singal projection in Frequency domain for efficient multi-scale deblocking framework.   

---

### 📄 Research Papers
> Add DOIs/arXiv as they go live. Keep titles concise and outcome-oriented.

| Year | Venue | Title | Status | Links |
|-----:|:-----:|:------|:------:|:------|
| 2026 | DCC | **InterGS-Lite: Light Weight Dynamic GS coding with Vector Quantization of Prediction Residuals** | Under Review | ⟦draft⟧ |
| 2026 | TIP | **Channel-wise Transformer-based Hierarchical Feature Fusion for Point Cloud Attribute Compression Artifact Mitigation** | Under Review | ⟦draft⟧ |
| 2025 | VCIP | **InterGS: Inter-Frame Prediction for Dynamic 3D Gaussian Splatting** | accepted | ⟦PDF⟧ ⟦Poster⟧ |
| 2025 | ICIP | **J-SGFT: Joint spatial and graph fourier domain learning for point cloud attribute deblocking** | accepted | ⟦PDF⟧ ⟦Poster⟧ |
| 2024 | DCC | **MUSCON: Multi-scale SparseConv Learning for Point Deblocking** | accepted | ⟦PDF⟧ ⟦Poster⟧ |
| 2024 | MMSP | **Sparse Convolution Based Point Cloud Attributes Deblocking with Graph Fourier Latent Representation** | accepted | ⟦PDF⟧ ⟦Poster⟧ |
| 2024 | Artificial Intelligence and Fuzzy Logic System 2024 | **Yolov5, yolo-x, yolo-r, yolov7 performance comparison: A survey** | accepted | ⟦PDF⟧ ⟦Poster⟧ |


<details>
<summary><b>Mini abstracts</b></summary>

- **InterGS (VCIP 2025).** Predict current-frame Gaussian attributes from a reference I-frame; transmit residuals only. Dual predictor (bilateral + KNN) with per-Gaussian mode selection cuts bitrate while preserving photorealistic quality.

- **InterGS-VQ (DCC 2026, target).** Vector-quantize SH_DC/SH_AC with feature-aware codebooks, keeping opacity/scale/rot scalar. Gains in BD-Rate with stable PSNR across multi-frame chains.
</details>

---

### 🧠 Patents & IP
| ID / Ref | Title | Area | Status |
|:--------:|:------|:-----|:------:|
| ⟦To be Entered Later⟧ | **InterGS: Dynamic Inter-Prediction for 3D Gaussian Splatting** | 3DGS Inter-frame compression | Patent Pending |

### 🧠 Rendered View Point After Decoding using InterGS 
<img align="center" src="./render_-ezgif.com-video-to-gif-converter.gif" width="1024" alt="InterGS demo 1">
---

### 🔬 Research Projects
> Pin these three (Customize Profile → Pinned).

#### 🟦 InterGS-Lite - Light Weight Dynamic GS coding with Vector Quantization of Prediction Residuals
#### 🟩 InerGS - Inter-Predictive Coding of Gaussian Splatting Sequences.
#### 🟨 Meta Hacker Cup 2025 — Round_1 (Python)

---

### 🏆 Awards & Achievements
- **Meta Hacker Cup 2025** participant (Round 1 solutions public - On-going).  
- **Qualcomm Multimedia R&D** (’25): inter-prediction for 3DGS (patent-pending).  
- **Google Jam 2023**: Highest ranked over Pakistani Leaderboard.
- **Advent of Code 2022**: Top 6th on Pakistani Leaderboard.
- Won Research **Funding on National level** from IT Ministry, Pakistan.
- Secured **merit-based fully funded scholarship** in Undergrad.
- Solved over 250 Coding questions on **Leetcode**.

---

<h3 id="stack">🧰 Tech Stack</h3>

<!-- Row 1: Core / Systems -->
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,cmake,git,github,linux,ubuntu,bash,vscode,neovim,docker&perline=12" height="32" alt="Core stack">
  <br/>
  <!-- Row 2: ML / Vision -->
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn,latex,githubactions,aws,gcp,cloudflare&perline=12" height="32" alt="ML & Vision">
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
  <a href="mailto:mtgcf@umsystem.edu" title="Email">
    <img src="https://skillicons.dev/icons?i=gmail" height="34" alt="Email">
  </a>&nbsp;&nbsp;

  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/engrtm/" title="LinkedIn">
    <img src="https://skillicons.dev/icons?i=linkedin" height="34" alt="LinkedIn">
  </a>&nbsp;&nbsp;

  <!-- X / Twitter -->
  <a href="https://x.com/YOUR_ID" title="X / Twitter">
    <img src="https://skillicons.dev/icons?i=twitter" height="34" alt="X">
  </a>&nbsp;&nbsp;

  <!-- Google Scholar (Simple Icons CDN, brand blue) -->
  <a href="https://scholar.google.com/citations?user=RHI_14gAAAAJ&hl=en" title="Google Scholar">
    <img src="https://cdn.simpleicons.org/googlescholar/4285F4" height="34" alt="Google Scholar">
  </a>&nbsp;&nbsp;

  <!-- ORCID (Simple Icons CDN, brand green) -->
  <a href="https://orcid.org/0009-0005-9389-8052" title="ORCID">
    <img src="https://cdn.simpleicons.org/orcid/A6CE39" height="34" alt="ORCID">
  </a>
</p>
