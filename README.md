<h1 align="center">Hi, I'm Eduardo — Ed for short 👋</h1>

<h2 align="center">Software Engineer · MSc in AI</h2>

<p align="center">
  <strong>Researching and building practical, open-source AI systems.</strong>
</p>

<p align="center">
  🌍 <strong>Open to remote opportunities</strong> in software engineering, AI systems, and developer tooling.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Systems-154f4f?style=for-the-badge&labelColor=123f40" alt="AI Systems"/>
  <img src="https://img.shields.io/badge/Evaluation%20%26%20Observability-2b7370?style=for-the-badge&labelColor=1d5f5d" alt="Evaluation & Observability"/>
  <img src="https://img.shields.io/badge/Developer%20Tools-3aa7a1?style=for-the-badge&labelColor=2b7370" alt="Developer Tools"/>
  <img src="https://img.shields.io/badge/Open%20Source-8edbd6?style=for-the-badge&labelColor=52cfc7" alt="Open Source"/>
</p>

---

## 🚧 Active Research & Development

**Building systems that make software and AI more readable, reliable, and verifiable.**

| Project | What makes it different |
| :-- | :-- |
| **[Semauri](https://github.com/edujbarrios/semauri)** | **A real programming language, engineered from the ground up.** Semauri brings static typing to natural-language-inspired syntax, with its own Rust compiler, executable programs, source-aware diagnostics, and explicitly controlled side effects. |
| **[TrainLens](https://github.com/edujbarrios/trainlens)** | **Turn training runs into next experiments.** Deterministic notebook diagnostics, visualizations, and evidence-backed recommendations, with optional LLM and agent workflows.<br/><br/>[![TrainLens downloads](https://api.pepy.tech/badge/trainlens)](https://pepy.tech/project/trainlens) |
| **[ASTScribe](https://github.com/edujbarrios/astscribe)** | **Understand ML notebooks without executing them.** Static analysis traces model setup, training, evaluation, and cell dependencies back to their original source lines.<br/><br/>[![ASTScribe downloads](https://api.pepy.tech/badge/astscribe)](https://pepy.tech/project/astscribe) |
| **[LastLight](https://github.com/edujbarrios/lastlight)** | **Reliable retrieval when infrastructure fails.** Standard-library-only, offline knowledge search with inspectable sources and evidence-based refusal—no cloud, embeddings, or vector database.<br/><br/>[![LastLight downloads](https://api.pepy.tech/badge/lastlight)](https://pepy.tech/project/lastlight) |

---

## 📦 Open-Source AI Tooling

<details>
  <summary><b>Python Package Portfolio</b></summary>

<br/>

Small, practical Python tools for AI evaluation, data quality, retrieval, multimodal analysis, visualization, and generative-audio workflows.

### Retrieval, Context & Agent Evidence

| Package | Research / engineering focus | Downloads |
| :-- | :-- | :--: |
| [**context-dedup**](https://github.com/edujbarrios/context-dedup) | Context deduplication for reducing redundant content in LLM and agent workflows. | [![context-dedup downloads](https://api.pepy.tech/badge/context-dedup)](https://pepy.tech/project/context-dedup) |
| [**evidenceflow**](https://github.com/edujbarrios/evidenceflow) | Deterministic analysis of how retrieved and tool-generated evidence propagates through AI-agent traces. | [![evidenceflow downloads](https://api.pepy.tech/badge/evidenceflow)](https://pepy.tech/project/evidenceflow) |
| [**rag-chunk-audit**](https://pypi.org/project/rag-chunk-audit/) | RAG chunk-quality auditing for segmentation and retrieval analysis. | [![rag-chunk-audit downloads](https://api.pepy.tech/badge/rag-chunk-audit)](https://pepy.tech/project/rag-chunk-audit) |

### Evaluation, Regression & Safety

| Package | Research / engineering focus | Downloads |
| :-- | :-- | :--: |
| [**embedding-drift-lite**](https://pypi.org/project/embedding-drift-lite/) | Embedding-distribution drift detection and diagnostic inspection. | [![embedding-drift-lite downloads](https://api.pepy.tech/badge/embedding-drift-lite)](https://pepy.tech/project/embedding-drift-lite) |
| [**parametricbench**](https://pypi.org/project/parametricbench/) | Provider-independent regression benchmarking for LLM and VLM systems. | [![parametricbench downloads](https://api.pepy.tech/badge/parametricbench)](https://pepy.tech/project/parametricbench) |
| [**promptshield-llm**](https://pypi.org/project/promptshield-llm/) | Prompt-injection, unsafe-instruction, and input-risk screening for LLM pipelines. | [![promptshield-llm downloads](https://api.pepy.tech/badge/promptshield-llm)](https://pepy.tech/project/promptshield-llm) |

### Multimodal & VLM Analysis

| Package | Research / engineering focus | Downloads |
| :-- | :-- | :--: |
| [**metaclean-vlm**](https://pypi.org/project/metaclean-vlm/) | Metadata normalization for image and vision-language model datasets. | [![metaclean-vlm downloads](https://api.pepy.tech/badge/metaclean-vlm)](https://pepy.tech/project/metaclean-vlm) |
| [**visual-patch-audit**](https://pypi.org/project/visual-patch-audit/) | Image-patch auditing and visual-signal inspection for VLM workflows. | [![visual-patch-audit downloads](https://api.pepy.tech/badge/visual-patch-audit)](https://pepy.tech/project/visual-patch-audit) |
| [**vlm-occlusion**](https://pypi.org/project/vlm-occlusion/) | Grid-based black-box occlusion analysis for VLM claim sensitivity. | [![vlm-occlusion downloads](https://api.pepy.tech/badge/vlm-occlusion)](https://pepy.tech/project/vlm-occlusion) |
| [**vlm-prior-probe**](https://github.com/edujbarrios/vlm-prior-probe) | Counterfactual black-box evaluation of whether VLMs follow visual evidence or learned priors. | [![vlm-prior-probe downloads](https://api.pepy.tech/badge/vlm-prior-probe)](https://pepy.tech/project/vlm-prior-probe) |

### Visualization & Developer Experience

| Package | Research / engineering focus | Downloads |
| :-- | :-- | :--: |
| [**matplotlib-dark**](https://github.com/edujbarrios/matplotlib-dark) | Automatic dark mode for Matplotlib with ready-to-use themes and safe temporary styling. | [![matplotlib-dark downloads](https://api.pepy.tech/badge/matplotlib-dark)](https://pepy.tech/project/matplotlib-dark) |

### Language & Transliteration

| Package | Research / engineering focus | Downloads |
| :-- | :-- | :--: |
| [**egypttranslit**](https://github.com/edujbarrios/egypttranslit) | Egyptological transliteration to clean Unicode from Python or the command line, with MdC conversion, normalization, validation, and diagnostics. | [![egypttranslit downloads](https://api.pepy.tech/badge/egypttranslit)](https://pepy.tech/project/egypttranslit) |

### Generative Audio

| Package | Research / engineering focus | Downloads |
| :-- | :-- | :--: |
| [**text-to-music-prompt-structurer**](https://pypi.org/project/text-to-music-prompt-structurer/) | Structured prompt extraction for text-to-music generation workflows. | [![text-to-music-prompt-structurer downloads](https://api.pepy.tech/badge/text-to-music-prompt-structurer)](https://pepy.tech/project/text-to-music-prompt-structurer) |


</details>

---

## 🔌 APIs

<details>
  <summary><b>API Clients</b></summary>

<br/>

| Library | Language | Focus |
| :-- | :-- | :-- |
| [**llm7R**](https://github.com/edujbarrios/llm7R) | R | Lightweight client for the LLM7.io API, with chat, streaming, model discovery, JSON mode, tool calling, data-frame analysis, vision, and image/video generation. |
| [**llm-ts-api-wrapper**](https://github.com/edujbarrios/llm-ts-api-wrapper) | TypeScript | Zero-runtime-dependency client for OpenAI-compatible APIs, covering chat and Responses APIs, streaming, embeddings, models, tool calling, retries, timeouts, and typed errors. Designed for direct source integration; not published on npm. |

</details>

---

## 🧠 AI Research

| Project | Research focus |
| :-- | :-- |
| [**Cablegram**](https://github.com/edujbarrios/cablegram) | Token-efficient communication for humans and AI agents, with auditable context compression and invariant checks. |
| [**Suffice**](https://github.com/edujbarrios/suffice) | Finding the minimum successful token budgets for AI agents under explicit quality constraints. |
| [**MAVERICK**](https://github.com/edujbarrios/maverick-oss) | Cognition-inspired, multi-agent visual reasoning with an interpretable perceive–describe–critique–refine loop. |
| [**music-to-text**](https://github.com/edujbarrios/music-to-text) | Local-first audio feature extraction and structured music metadata and industry copy generation. |

---

## 📚 Educational Guides

| Guide | What's inside |
| :-- | :-- |
| [**Neural Audio Theory**](https://github.com/edujbarrios/neural-audio-theory) | A practical and technical guide to AI music generation, signal processing, embeddings, model architectures and training. [Live guide](https://neural-audio-theory.vercel.app/). |
| [**edujbarrios-ai**](https://github.com/edujbarrios/edujbarrios-ai) | AI algorithms from scratch in C, Python, Rust and R, with explanations, documented implementations and tests. |
| [**edujbarrios-ui**](https://github.com/edujbarrios/edujbarrios-ui) | A compendium of copy-ready React and TypeScript frontend components for AI products, dashboards and developer tools. [Component gallery](https://edujbarrios-ui.vercel.app/). |

---

## 📊 Benchmarks

| Benchmark | Evaluation focus |
| :-- | :-- |
| [**LastLight Bench**](https://github.com/edujbarrios/lastlight-bench) | Reproducible offline retrieval evaluation: ranking, answer/refusal calibration, bilingual behavior, routing, latency and memory usage. |

---

## 💻 Tech Stack

<details>
  <summary><b>Languages</b></summary>

<br/>

<p align="center">

![Python](https://img.shields.io/badge/Python-14354C.svg?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2.svg?style=for-the-badge&logo=julia&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![C](https://img.shields.io/badge/C-00599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000.svg?style=for-the-badge&logo=rust&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34B00.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

</p>

</details>

<details>
  <summary><b>AI Systems & Tooling</b></summary>

<br/>

<p align="center">

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000000?style=for-the-badge)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5A45FF?style=for-the-badge)

![React](https://img.shields.io/badge/React-20232A.svg?style=for-the-badge&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FFB000.svg?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)

![Quarto](https://img.shields.io/badge/Quarto-39729E.svg?style=for-the-badge)
![Docusaurus](https://img.shields.io/badge/Docusaurus-2E8555.svg?style=for-the-badge)
![MDX](https://img.shields.io/badge/MDX-1B1F23.svg?style=for-the-badge)
![Jinja](https://img.shields.io/badge/Jinja-B41717.svg?style=for-the-badge)

</p>

</details>

---

## 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- [I Created a Complete Educational Guide on AI Music Generation](https://edujbarrios.com/blog/neural-audio-theory-complete-guide)
- [I Built My Own Documentation Site Builder - Here's Why and How](https://www.edujbarrios.com/blog/building-ncmds-documentation-site-builder)
- [I Built a Notebook Engine for C, and the Potential Is Incredible](https://edujbarrios.com/blog/c-notebook-engine-potential)
<!-- BLOG-POST-LIST:END -->

---

## 🎧 Beyond the Code

<details>
  <summary><b>Creative Side</b></summary>

<br/>

<p align="center">
  <strong>Music Producer with 7+ years of experience and global reach.</strong>
</p>

<p align="center">
  <a href="https://www.edujbarrios.com/music">
    🎵 Listen
  </a>
</p>

</details>

---

## 🖥 Environment

<details>
  <summary><b>OS & Development</b></summary>

<br/>

<p align="center">

![Windows](https://img.shields.io/badge/Windows-0078D6.svg?style=for-the-badge&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-999999.svg?style=for-the-badge&logo=apple&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC.svg?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=github&logoColor=white)

</p>

</details>
