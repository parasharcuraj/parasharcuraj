# Himanshu Kumar Parashar

**Deep Learning Researcher · Medical Image Analysis · Healthcare AI · LLM Evaluator**

Integrated M.Sc. Computer Science · Central University of Rajasthan, Ajmer, India *(2021–2026)*

---

## 🎯 In One Line

> I build deep learning systems that **detect cancer from tissue slides, segment organs from 3D MRI, and decode brain signals** — with results that beat published state-of-the-art benchmarks. I also design **adversarial CS tasks that expose where frontier LLMs fail**, bridging research and model evaluation.

📍 Ajmer, India &nbsp;|&nbsp; 📧 hkp2857@gmail.com &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/himanshu-parashar-a7217222a) &nbsp;|&nbsp; **🎓 Seeking PhD / Research positions**

---

## 🏛️ Research Affiliations

| Period | Institute | Project |
|---|---|---|
| Dec 2025 – Present | **National Institute of Technology, Jamshedpur** | Oral Cancer Detection · DWT-Gabor Swin Transformer |
| Aug – Nov 2025 | **Indian Institute of Technology, Kharagpur** | EEG · Autism Detection · P300 BCI |
| May – Jul 2025 | **IIITDM Kurnool** | Human Activity Recognition · BiLSTM-Transformer |

---

## 🏆 Key Results

| Model | Task | My Result | Previous SOTA | Improvement |
|---|---|---|---|---|
| **DCFNet** (Thesis) | 3D Liver Segmentation · T2-MRI | **92.22% Dice** | 86.51% | **+5.71 pp** |
| **Inception-V3 + Huber** | Fundus Image Quality (FIQA) | **SRCC 0.9459** | TRIQ, HyperIQA | **Top result** |
| **BiLSTM-Transformer** | Human Activity Recognition | **95.80% Acc** | BiLSTM baseline | **Best of 6** |
| **CNN** | Lung Cancer · DICOM CT | **98.64% Acc** | ANN 85.69% | **+12.95 pp** |

---

## 🧪 LLM Evaluation Portfolio

**[→ llm-cs-eval-tasks](https://github.com/parasharcuraj/llm-cs-eval-tasks)** — 15 real systems engineering tasks that expose LLM reasoning failures

I design and evaluate complex CS debugging tasks as part of active LLM benchmarking work. These tasks cover:

- Protocol bugs requiring RFC-level spec knowledge (DNSSEC, HTTP/2, UART)
- Systems debugging with no documentation — format must be reverse-engineered from binaries (WAL, eBPF, custom ISA)
- Multi-layer cascade failures where fixing layer A reveals bugs in B, C, D
- Custom codecs, embedded linker scripts, distributed tracing pipelines

**Failure patterns I document:** cascade reasoning, spec inference, simultaneous multi-layer repair, byte-identical precision, edge-case semantics

> This work maps directly to: **AI Evaluator · LLM Red Teamer · Benchmark Dataset Creator**

---

## 🧠 Active Research

**🦷 Oral Cancer Detection — NIT Jamshedpur** *(Dec 2025 – Present)*
- Designing a **DWT-Gabor Fusion Swin Transformer** for early-stage OSCC classification from H&E-stained histopathological images
- Novel **4th-channel input strategy**: fusing multi-level Haar DWT + Gabor filter energy maps → stain-invariant frequency-domain features (cell boundaries, nuclear texture, tissue architecture)
- Replacing standard ViT patch merging with **DWT-based patch merging** — preserves edge and texture information critical for fine morphological distinction
- Benchmarking on NDB-UFES dataset (237 images, 3 classes) · correcting data leakage in prior work · 5-fold stratified image-level CV

**🧬 DCFNet: 3D Liver Segmentation — Master's Thesis**
- **Dual-encoder architecture** with Cross-Attention Fusion Module (CAFM): bidirectional cross-attention + learned per-voxel spatial gating
- Extended **Coordinate Attention from 2D → 3D** for volumetric medical image analysis
- Pipeline: PyTorch + MONAI · boundary-aware loss · deep supervision · mixed-precision · single NVIDIA T4 GPU
- Evaluated on **318 3D MRI volumes** (CirrMRI600+) · 4 baselines · 6-variant ablation study · statistical significance testing

---

## 🔭 Research Interests

`Deep Learning` &nbsp; `Medical Image Analysis` &nbsp; `3D Volumetric Segmentation` &nbsp; `Computational Pathology`  
`Oral Cancer Detection` &nbsp; `Vision Transformers` &nbsp; `Retinal Image Quality Assessment`  
`EEG / BCI Systems` &nbsp; `Wavelet-Based Feature Extraction` &nbsp; `Healthcare AI` &nbsp; `Time-Series Classification`

---

## 🛠️ Technical Stack

**ML / DL Frameworks** &nbsp;→&nbsp; `PyTorch` `TensorFlow` `MONAI` `Keras` `Scikit-learn`  
**Medical Imaging** &nbsp;→&nbsp; `DICOM` `OpenCV` `OpenSlide` `Stain Normalization` `Patch Extraction` `Image Segmentation`  
**Signal Processing** &nbsp;→&nbsp; `SciPy` `PyWavelets` `DWT` `Gabor Filters` `Band-pass Filtering` `Artifact Removal`  
**Languages** &nbsp;→&nbsp; `Python` `C/C++` `Java`  
**Tools** &nbsp;→&nbsp; `Git` `Docker` `FastAPI` `PostgreSQL` `LaTeX` `Jupyter` `VS Code`

---

## 📌 Featured Projects

| Project | What I built | Key metric |
|---|---|---|
| [🧬 **DCFNet** – 3D Liver Segmentation](https://github.com/parasharcuraj/histo) | Dual-encoder CNN · Cross-attention fusion · 3D MRI | 92.22% Dice |
| [🤖 **AI-Interview-Assistant**](https://github.com/parasharcuraj/AI-Interview-Assistant) | LLM-powered technical recruiter · scoring dashboard | End-to-end AI pipeline |
| [🚂 **RailSathiBE-Docker**](https://github.com/parasharcuraj/RailSathiBE-Docker) | Dockerized complaint system · Redis · JWT | Production-grade backend |
| [🔑 **kpa-api**](https://github.com/parasharcuraj/kpa-api) | FastAPI · JWT auth · PostgreSQL REST API | Secure, scalable |

---

## 📊 GitHub Activity

![Himanshu's GitHub stats](https://github-readme-stats.vercel.app/api?username=parasharcuraj&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=parasharcuraj&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=parasharcuraj&theme=tokyonight&hide_border=true)

---

💬 *I'm actively looking for PhD opportunities and research collaborations in AI-driven healthcare and computational pathology. Let's connect.*

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-parashar-a7217222a)
