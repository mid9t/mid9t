<h1 align="center">Hi, I'm Ryu Kakuta 👋</h1>
<h3 align="center">Model Evaluation Engineer · Uncertainty Quantification Researcher</h3>

<p align="center">
I build models that know when they don't know — and evaluation harnesses that catch it when models fail silently instead.
</p>

<p align="center">
<a href="https://mid9t.github.io/RyuKakuta.github.io/"><img src="https://img.shields.io/badge/Portfolio-mid9t.github.io-black?style=flat-square&logo=googlechrome&logoColor=white"></a>
<a href="https://www.linkedin.com/in/kakury/"><img src="https://img.shields.io/badge/LinkedIn-kakury-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
<a href="mailto:kakuryu555@gmail.com"><img src="https://img.shields.io/badge/Email-kakuryu555%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
<a href="https://drive.google.com/file/d/1C9Dhx1d-iXLT55JD-BOZ-fEj9R-vqj1i/view?usp=sharing"><img src="https://img.shields.io/badge/Résumé-View-4B5563?style=flat-square&logo=readdotcv&logoColor=white"></a>
</p>

---

### 🎯 What I'm working on

My central research question is **can a model tell you when it's guessing?** I work on **density-aware Evidential Deep Learning** — architectures that emit a confidence/vacuity signal alongside every prediction, plus the diagnostics to prove that signal is actually load-bearing and not just noise dressed up as calibration.

Day to day, I'm an **AI Evaluation Engineer (Post-Training) at [Handshake](https://joinhandshake.com)**, where I work on RL environments and containerized coding tasks that stress-test frontier agents — authoring scoring gates, calibrating task difficulty, and figuring out whether a failure is the model's fault or the harness's.

```
uncertainty quantification → model evaluation → agent reliability
        (why a model fails)   (catching it)      (trusting it anyway)
```

---

### 🔬 Current build — ER-1: Epistemic Ranker

An early-exiting inference architecture gated by Evidential Deep Learning uncertainty. The model emits intermediate predictions during inference and exits early once confidence is high or vacuity is low enough — trading compute for confidence, on purpose.

`PyTorch` · `Model Calibration` · `Information Retrieval` · `HuggingFace` · `Data Streaming`
📎 [github.com/mid9t/ER-1-Epistemic-Ranker-](https://github.com/mid9t/ER-1-Epistemic-Ranker-)

---

### 📌 Selected projects

| Project | What it does | Stack |
|---|---|---|
| **[ER-1: Epistemic Ranker](https://github.com/mid9t/ER-1-Epistemic-Ranker-)** | Early-exit architecture gated by evidential uncertainty | PyTorch, EDL, HuggingFace |
| **[GeoGenie](https://github.com/mid9t/GeoGenie)** | Free-text intent → structured spatial queries over hand-built geometric indices | Python, NumPy, FastAPI, LLMs |
| **[RCA-Demo](https://github.com/mid9t/RCA-Demo)** | Automated root-cause analysis for sales anomalies (synthetic data) | Python, SHAP, Statistical Modeling |
| **EEG-Based MDD Classification** | End-to-end clinical signal pipeline, built around leakage prevention and evaluation rigor | CNNs, Granger Causality |

---

### ✍️ Featured writing

**[Evidential BERT on CLINC150: porting density-aware EDL from vision to language](https://mid9t.github.io/RyuKakuta.github.io/articles/evidential_bert_article/)**
A theory-and-engineering deep dive adapting density-aware Evidential Deep Learning to BERT embeddings — then validating on CLINC150 that the uncertainty signal is doing real work.

---

### 🧭 Path here

- **UC Berkeley** — B.A. Data Science
- **Terra Drone Corporation** — Data Systems Intern, automated GCP + SQL reporting pipelines
- **Fractal Analytics** — Research SWE Intern, ML infra for sales-forecast anomaly diagnosis (SHAP-validated)
- **Handshake** — AI Evaluation Engineer, Post-Training *(current)*

---

<p align="center">
<sub>Open to conversations about uncertainty quantification, model evaluation, and agent reliability. My inbox is always open — <a href="mailto:kakuryu555@gmail.com">say hello</a>.</sub>
</p>
