<div align="center">

# Abdul Rahman Kamal

**Data Scientist · ML Systems Engineer · Rust Developer**

[![Crates.io](https://img.shields.io/crates/v/quantize-rs?style=flat-square&logo=rust&logoColor=white&label=crates.io&color=e43717)](https://crates.io/crates/quantize-rs)
[![Docs.rs](https://img.shields.io/docsrs/quantize-rs?style=flat-square&logo=docs.rs&logoColor=white&label=docs)](https://docs.rs/quantize-rs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ar-kamal)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abdulrahmandev141@gmail.com)

</div>

---

### About

Computer Science student specializing in Data Science at Albukhary International University, Malaysia. I build production-grade ML tooling and data-driven applications. Published crate author on [crates.io](https://crates.io/crates/quantize-rs).

```rust
impl Engineer {
    pub fn focus(&self) -> Vec<&str> {
        vec![
            "Neural Network Quantization — INT8/INT4 compression in pure Rust",
            "Machine Learning & Deep Learning pipelines",
            "Natural Language Processing, RAG, and AI Agents",
            "Full-stack development with React, Next.js, and TypeScript",
        ]
    }
}
```

**Certifications** — DataCamp Data Analyst · DataCamp Data Scientist · DataCamp Data Engineer (Python)

---

### Flagship — quantize-rs

Production-grade neural network quantization toolkit in pure Rust. Compresses ONNX models up to 8x with minimal accuracy loss. Zero Python dependency.

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AR-Kamal/quantize-rs)
[![crates.io](https://img.shields.io/crates/v/quantize-rs.svg?style=flat-square&color=e43717)](https://crates.io/crates/quantize-rs)
[![Downloads](https://img.shields.io/crates/d/quantize-rs.svg?style=flat-square&color=4cc61e)](https://crates.io/crates/quantize-rs)

```
  ┌──────────────┐       ┌──────────────────────────────┐       ┌──────────────┐
  │  ONNX Model  │       │      quantize-rs Engine       │       │  Compressed  │
  │  Float32     │──────>│                                │──────>│  Model       │
  │  44.65 MB    │       │  Per-Tensor / Per-Channel      │       │  5.60 MB     │
  └──────────────┘       │  INT8 (4x) / INT4 (8x)        │       └──────────────┘
                         │  Calibration: MinMax,          │
                         │  Percentile, Entropy, MSE      │
                         │  INT4 Bit Packing (2 vals/B)   │
                         └──────────────────────────────┘
```

**ResNet-18 Results**

| Method | Size | Compression | MSE | Accuracy Retained |
|:---|:---:|:---:|:---:|:---:|
| Original (Float32) | 44.65 MB | 1.0x | — | Baseline |
| INT8 Per-Channel | 11.18 MB | 4.0x | 0.000002 | 99.9% |
| INT4 Per-Channel | 5.60 MB | 8.0x | 0.000862 | 91.4% |

```bash
cargo install quantize-rs
quantize-rs quantize model.onnx -o model_int4.onnx --bits 4 --per-channel
```

---

### Tech Stack

**Languages** — Rust · Python · TypeScript · JavaScript · SQL

**ML / Data** — TensorFlow · Keras · Scikit-learn · Pandas · NumPy · ONNX

**Visualization** — Tableau · Power BI · Matplotlib · Seaborn

**Databases** — PostgreSQL · MySQL · MongoDB · Supabase

**Development** — React · Next.js · Node.js · Docker · Git · Cargo

---

### Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=AR-Kamal&theme=github-dark-blue&border=30363d&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=8b949e&sideLabels=8b949e&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=AR-Kamal&bg_color=0d1117&color=8b949e&line=58a6ff&point=c9d1d9&area_color=1f6feb&area=true&hide_border=true&custom_title=Contribution%20Activity" width="95%"/>

</div>

---

<div align="center">
<sub>Open to collaboration on ML tooling, quantization research, and systems-level AI projects.</sub>
</div>
