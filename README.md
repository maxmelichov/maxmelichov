# Maxim (Max) Melichov

**Data Scientist & AI Engineer — NLP, Speech, and Applied Deep Learning**
MSc Student in Data Science & Machine Learning @ Reichman University

I build production‑grade AI systems with a focus on **text‑to‑speech (TTS)**, **Hebrew NLP (diacritization/“niqqud”)**, **deepfake detection**, and **medical imaging**. My work spans from research and model design to deployment with **ONNX/TensorRT**, **CUDA optimization**, and **MLOps** pipelines.

* Awarded **1st place** in a Hebrew synthetic‑voice challenge for **Kan News** (broadcast‑grade TTS quality).
* **Kaggle**: consistent competitor; e.g., **BirdCLEF 2025** Top 2% (AUC 0.902; Rank 38/2025).
* Creator of **MamreVoice** — a production‑ready Hebrew/Multilingual TTS with high‑fidelity voice cloning and fast inference.

---

## Contents

* [What I Do](#what-i-do)
* [Selected Projects](#selected-projects)
* [Technical Skills](#technical-skills)
* [Experience Highlights](#experience-highlights)
* [Writing & Talks](#writing--talks)
* [Contact](#contact)

---

## What I Do

* **Custom TTS Pipelines**: Speaker cloning, prosody control, cross‑language transfer, long‑form stability; FastAPI/GRPC services; streaming TTS.
* **Private, Efficient Deployment**: Triton Inference Server, TensorRT, ONNX Runtime; serverless GPU endpoints (cold‑start tuned), autoscaling, observability.
* **Hebrew NLP**: State‑of‑the‑art **diacritization** with Dicta‑BERT variants + retrieval; spelling/vowelization correction; evaluation tooling.
* **Deepfake Detection**: Temporal+spatial modeling, mixed‑precision training, robust inference pipelines.
* **Medical Imaging**: 2.5D/3D CNNs and transformers; segmentation → diagnosis pipelines (e.g., RSNA challenges).
* **Reinforcement Learning**: Agents for MiniGrid dynamic‑obstacles; reward shaping, diagnostics, and rigorous eval.

---

## Selected Projects

* **MamreVoice** — High‑fidelity Hebrew/Multilingual TTS
  Real‑time and batch synthesis, accurate voice cloning, robust long‑form output. Optimized with TensorRT and ONNX; deployable as private endpoints with key‑based billing.
  • Demo site: **[https://maxmelichov.github.io/mamre-site/](https://maxmelichov.github.io/mamre-site/)**
  • API/UI options: RunPod/Novita serverless, Triton‑backed services.

* **Phonikud / Hebrew Diacritization R\&D**
  Retrieval‑augmented Dicta‑BERT pipeline for modern Hebrew; kNN‑assisted decoding; sentence‑level evaluation and detailed error analysis.

* **Deepfake Detection**
  Hybrid temporal–spatial training under autocast; balanced optimizers; robust data processing; export to ONNX/TensorRT for production.

* **RSNA Imaging Work**
  2.5D CNNs for spine analysis; segmentation→classification composition; intensive experimentation under GPU constraints.

> If you want details or references, I’m happy to share code, notebooks, and reports where appropriate.

---

## Technical Skills

**Languages**: Python, C/C++ (tools), SQL
**DL/ML**: PyTorch, Hugging Face, scikit‑learn, Lightning
**Speech/Audio**: TTS, ASR, DSP basics, speaker embeddings
**Optimization**: CUDA, TensorRT, ONNX Runtime, quantization, mixed precision
**Serving**: Triton Inference Server, FastAPI/GRPC, serverless GPU endpoints, streaming
**MLOps**: Docker, GitHub Actions, experiment tracking, profiling, reproducibility
**Data**: Pandas/Polars, NumPy, DVC, data curation/labeling workflows
**Tooling**: VS Code Remote‑SSH, rclone, uv/pip‑tools, containers, multi‑GPU workflows

---

## Experience Highlights

* Designed **end‑to‑end TTS** stack with accurate **voice cloning**, prosody controls, and fast inference; exported to ONNX/TensorRT; deployed as a **private API** with request‑level billing.
* Built **Hebrew NLP** pipelines for **diacritization** with retrieval augmentation, including sentence‑level evaluation, confusion matrices, and qualitative analyses.
* Trained **deepfake detectors** with temporal and spatial modules; emphasized stability, speed, and production exportability.
* Developed **medical‑imaging** classifiers that integrate segmentation outputs (2.5D/3D); handled tight VRAM and throughput trade‑offs.
* Implemented **RL agents** (Q‑learning, DQN/PPO, etc.) with principled reward shaping and comprehensive evaluation tooling.

---

## Writing & Talks

* *How to Create a TensorRT Engine (v10.4.0)* — Medium (technical deep‑dive).
* *RSNA Lumbar Spine: Segmentation→Classification Lessons* — notes and write‑ups.
* *Hebrew Diacritization with RAG + Dicta‑BERT* — research notes, evaluation framework.

> More posts and notebooks are available on my Medium and GitHub.

---

## Contact

* Email: **[maxme006@gmail.com](mailto:maxme006@gmail.com)**
* LinkedIn: **[https://www.linkedin.com/in/max-melichov/](https://www.linkedin.com/in/max-melichov/)**
* GitHub: **[https://github.com/maxmelichov/](https://github.com/maxmelichov/)**
* Medium: **[https://medium.com/@maxme006](https://medium.com/@maxme006)**

---

<details>
<summary>Additional Links and Badges (optional)</summary>

* GitHub stats card (public services):

  ![GitHub stats](https://github-readme-stats.vercel.app/api?username=maxmelichov\&show_icons=true)

* Top languages:

  ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=maxmelichov\&layout=compact)

* Shields examples:

  ![Python](https://img.shields.io/badge/Python-3.10%2B-blue) ![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red) ![TensorRT](https://img.shields.io/badge/TensorRT-10.x-informational) ![ONNX](https://img.shields.io/badge/ONNX-runtime-important) ![Docker](https://img.shields.io/badge/Docker-ready-success)

</details>
