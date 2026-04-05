<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=E2E8F0&center=true&vCenter=true&width=600&lines=Abdul+Rahman+Kamal;Systems+Engineer+%26+AI+Researcher;Building+at+the+intersection+of+Rust+%26+ML" alt="Typing SVG" />

<br/>

<p>
  <a href="https://github.com/AR-Kamal">
    <img src="https://img.shields.io/badge/GitHub-AR--Kamal-0d1117?style=flat-square&logo=github&logoColor=white&labelColor=1a1f2e" />
  </a>
  <a href="https://crates.io/users/AR-Kamal">
    <img src="https://img.shields.io/badge/crates.io-Published-dea584?style=flat-square&logo=rust&logoColor=white&labelColor=1a1f2e" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=AR-Kamal&color=64748b&style=flat-square&label=profile+views" />
</p>

</div>

---

## About

I build software at the intersection of **systems performance** and **machine learning** — writing tools that are fast by design, not by accident. My focus is on the lower layers of the AI stack: model optimization, efficient inference, and the infrastructure that bridges research with production.

Currently pursuing a degree in AI Engineering while shipping open-source ML tooling in Rust.

---

## What I Work On

<table>
<tr>
<td width="33%" valign="top">

**ML Infrastructure**

Neural network quantization, model compression, ONNX pipelines, and inference optimization. Work that makes models smaller without making them worse.

</td>
<td width="33%" valign="top">

**Applied AI**

NLP, sentiment analysis, LLM integration, and AI-assisted applications. Translating model capabilities into usable products.

</td>
<td width="33%" valign="top">

**Systems & Web**

Full-stack applications in TypeScript and React Native, static tooling, and developer utilities — built with the same rigor as the ML work.

</td>
</tr>
</table>

---

## Featured Project

<table>
<tr>
<td>

### [quantize-rs](https://github.com/AR-Kamal/quantize-rs) — Neural Network Quantization in Pure Rust

Production-grade toolkit for compressing neural networks. Converts float32 weights to INT8 or INT4, achieving up to **8x model size reduction** with minimal accuracy loss — no Python runtime required.

<br/>

[![Crates.io](https://img.shields.io/crates/v/quantize-rs?style=flat-square&logo=rust&logoColor=white&labelColor=1a1f2e&color=dea584)](https://crates.io/crates/quantize-rs)
[![Downloads](https://img.shields.io/crates/d/quantize-rs?style=flat-square&labelColor=1a1f2e&color=64748b)](https://crates.io/crates/quantize-rs)
[![Docs](https://img.shields.io/badge/docs.rs-quantize--rs-4a90d9?style=flat-square&labelColor=1a1f2e)](https://docs.rs/quantize-rs)
[![License](https://img.shields.io/badge/license-MIT-a3be8c?style=flat-square&labelColor=1a1f2e)](https://github.com/AR-Kamal/quantize-rs/blob/master/LICENSE)

<br/>

**Measured results on ResNet-18:**

| Method | Size | Compression | Avg MSE |
|---|---|---|---|
| Original | 44.65 MB | 1.0x | — |
| INT8 | 11.18 MB | **4.0x** | 0.000003 |
| INT8 Per-Channel | 11.18 MB | **4.0x** | 0.000002 |
| INT4 Per-Channel | 5.60 MB | **8.0x** | 0.000862 |

<br/>

**Core capabilities:**
- INT8 and INT4 quantization with custom packed storage
- Per-channel quantization — 40–60% error reduction vs. per-tensor
- Calibration framework: MinMax, Percentile, Entropy, MSE
- Full CLI: batch processing, validation, benchmarking
- YAML/TOML config for pipeline automation
- ONNX-native — works with PyTorch and TensorFlow models

```bash
# Install
cargo install quantize-rs

# Compress a model 8x
quantize-rs quantize model.onnx -o model_int4.onnx --bits 4 --per-channel

# Calibrate for maximum accuracy
quantize-rs calibrate model.onnx --data calib.npy -o model_cal.onnx --method percentile

# Validate the result
quantize-rs validate model.onnx model_int4.onnx
```

</td>
</tr>
</table>

---

## Other Projects

<table>
<tr>
<td width="50%">

**[AI-TravelPlanner](https://github.com/AR-Kamal/AI-TravelPlanner)**

AI-powered travel planning assistant. Built with JavaScript, integrating LLM capabilities for personalized itinerary generation.

</td>
<td width="50%">

**[StatTours](https://github.com/AR-Kamal/StatTours)**

Tourism analytics platform in TypeScript. Data-driven interface for stakeholders to understand visitor patterns and trends.

</td>
</tr>
<tr>
<td width="50%">

**[NLP-text-sentiment](https://github.com/AR-Kamal/NLP-text-sentiment)**

End-to-end NLP pipeline in Python. Text classification using Naive Bayes, SVM, Logistic Regression, and Random Forest with TF-IDF feature engineering.

</td>
<td width="50%">

**[static-site-generator](https://github.com/AR-Kamal/static_site_generator)**

A no-dependency static site generator built from scratch in Python. Markdown to HTML, clean output.

</td>
</tr>
</table>

---

## Stack

**Languages**

![Rust](https://img.shields.io/badge/Rust-1a1f2e?style=flat-square&logo=rust&logoColor=dea584)
![Python](https://img.shields.io/badge/Python-1a1f2e?style=flat-square&logo=python&logoColor=4b8bbe)
![TypeScript](https://img.shields.io/badge/TypeScript-1a1f2e?style=flat-square&logo=typescript&logoColor=3178c6)
![JavaScript](https://img.shields.io/badge/JavaScript-1a1f2e?style=flat-square&logo=javascript&logoColor=f7df1e)
![SQL](https://img.shields.io/badge/SQL-1a1f2e?style=flat-square&logo=postgresql&logoColor=336791)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-1a1f2e?style=flat-square&logo=pytorch&logoColor=ee4c2c)
![ONNX](https://img.shields.io/badge/ONNX-1a1f2e?style=flat-square&logo=onnx&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1a1f2e?style=flat-square&logo=scikit-learn&logoColor=f89939)
![NLTK](https://img.shields.io/badge/NLTK-1a1f2e?style=flat-square&logo=python&logoColor=4b8bbe)
![spaCy](https://img.shields.io/badge/spaCy-1a1f2e?style=flat-square&logo=spacy&logoColor=09a3d5)

**Web & Mobile**

![React](https://img.shields.io/badge/React-1a1f2e?style=flat-square&logo=react&logoColor=61dafb)
![React Native](https://img.shields.io/badge/React_Native-1a1f2e?style=flat-square&logo=react&logoColor=61dafb)
![Next.js](https://img.shields.io/badge/Next.js-1a1f2e?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-1a1f2e?style=flat-square&logo=node.js&logoColor=3c873a)
![Supabase](https://img.shields.io/badge/Supabase-1a1f2e?style=flat-square&logo=supabase&logoColor=3ecf8e)

**Tools**

![Git](https://img.shields.io/badge/Git-1a1f2e?style=flat-square&logo=git&logoColor=f05032)
![Docker](https://img.shields.io/badge/Docker-1a1f2e?style=flat-square&logo=docker&logoColor=2496ed)
![Linux](https://img.shields.io/badge/Linux-1a1f2e?style=flat-square&logo=linux&logoColor=fcc624)
![VS Code](https://img.shields.io/badge/VS_Code-1a1f2e?style=flat-square&logo=visual-studio-code&logoColor=007acc)

---

## Activity

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=AR-Kamal&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e2e8f0&icon_color=dea584&text_color=94a3b8&rank_icon=github" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AR-Kamal&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e2e8f0&text_color=94a3b8&langs_count=6" />

</div>

---

<div align="center">

<sub>Open to collaboration on ML infrastructure, developer tooling, and applied AI projects.</sub>

<br/>

<a href="https://github.com/AR-Kamal?tab=repositories">
  <img src="https://img.shields.io/badge/View_All_Repositories-0d1117?style=flat-square&logo=github&logoColor=white" />
</a>

</div>
