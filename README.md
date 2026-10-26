<h1 align="center">Hi, I'm Eduardo — Ed for short 👋</h1>

<h2 align="center">Software Engineer · MSc in AI</h2>

<p align="center">
  <strong>Researching and building practical, open-source AI systems.</strong>
</p>

<p align="center">
  🌍 <strong>Open to remote opportunities</strong> in software engineering, AI systems, and developer tooling.
</p>

---

## 🚧 Active Research & Development

<div align="center">

<h2>
  <a href="https://github.com/edujbarrios/trainlens">TrainLens</a>:
  ML training diagnostics with actionable next steps
</h2>

<p>
  TrainLens turns notebook training state into interpretable diagnostics, performance visualizations, and proposals for subsequent experiments. Its deterministic local analysis grounds recommendations in observed evidence. Optional LLM reports or coding-agent integrations extend the workflow.
</p>

</div>

<br/>

<div align="center">

<h2>
  <a href="https://github.com/edujbarrios/astscribe">ASTScribe</a>:
  trace model setup, training, evaluation, and cell dependencies in ML notebooks
</h2>

<p>
  ASTScribe transforms supported Python ML code or Jupyter notebooks into evidence-backed methodological explanations. Static analysis identifies training or inference patterns, reconstructs cell dependencies, then traces findings to their original source lines—without executing code or relying on an LLM.
</p>

</div>

<br/>

<div align="center">

<h2>
  <a href="https://github.com/edujbarrios/lastlight">LastLight</a>:
  offline knowledge retrieval with verifiable sources
</h2>

<p>
  LastLight makes locally stored knowledge accessible when connectivity or infrastructure is unreliable. Its standard-library Python engine searches Markdown or ZIP collections, exposes the evidence behind each result, then withholds answers when support is insufficient. No cloud services, embeddings or vector database required.
</p>

</div>

<br/>

<div align="center">

<h2>
  <a href="https://github.com/edujbarrios/semauri">Semauri</a>:
  deterministic programming through controlled natural language
</h2>

<p>
  Semauri explores a human-readable programming language with predictable compiler semantics. It generates web documents or JSON Schema, plans filesystem operations, and represents machine-learning workflows through typed constructs. Effectful actions require explicit authorization; compilation itself executes no side effects.
</p>

</div>

---

## 📦 Open-Source AI Tooling

<details>
  <summary><b>Python Package Portfolio</b></summary>

<br/>

Small, practical Python tools for AI evaluation, data quality, retrieval, multimodal analysis, visualization, and generative-audio workflows.

### Retrieval, Context & Agent Evidence

| Package | Research / engineering focus |
| :-- | :-- |
| [**context-dedup**](https://github.com/edujbarrios/context-dedup) | Context deduplication for reducing redundant content in LLM and agent workflows. |
| [**evidenceflow**](https://github.com/edujbarrios/evidenceflow) | Deterministic analysis of how retrieved and tool-generated evidence propagates through AI-agent traces. |
| [**rag-chunk-audit**](https://pypi.org/project/rag-chunk-audit/) | RAG chunk-quality auditing for segmentation and retrieval analysis. |

### Evaluation, Regression & Safety

| Package | Research / engineering focus |
| :-- | :-- |
| [**embedding-drift-lite**](https://pypi.org/project/embedding-drift-lite/) | Embedding-distribution drift detection and diagnostic inspection. |
| [**parametricbench**](https://pypi.org/project/parametricbench/) | Provider-independent regression benchmarking for LLM and VLM systems. |
| [**promptshield-llm**](https://pypi.org/project/promptshield-llm/) | Prompt-injection, unsafe-instruction, and input-risk screening for LLM pipelines. |

### Multimodal & VLM Analysis

| Package | Research / engineering focus |
| :-- | :-- |
| [**metaclean-vlm**](https://pypi.org/project/metaclean-vlm/) | Metadata normalization for image and vision-language model datasets. |
| [**visual-patch-audit**](https://pypi.org/project/visual-patch-audit/) | Image-patch auditing and visual-signal inspection for VLM workflows. |
| [**vlm-occlusion**](https://pypi.org/project/vlm-occlusion/) | Grid-based black-box occlusion analysis for VLM claim sensitivity. |
| [**vlm-prior-probe**](https://github.com/edujbarrios/vlm-prior-probe) | Counterfactual black-box evaluation of whether VLMs follow visual evidence or learned priors. |

### Visualization & Developer Experience

| Package | Research / engineering focus |
| :-- | :-- |
| [**matplotlib-dark**](https://github.com/edujbarrios/matplotlib-dark) | Automatic dark mode for Matplotlib with ready-to-use themes and safe temporary styling. |

### Language & Transliteration

| Package | Research / engineering focus |
| :-- | :-- |
| [**egypttranslit**](https://github.com/edujbarrios/egypttranslit) | Egyptological transliteration to clean Unicode from Python or the command line, with MdC conversion, normalization, validation, and diagnostics. |

### Generative Audio

| Package | Research / engineering focus |
| :-- | :-- |
| [**text-to-music-prompt-structurer**](https://pypi.org/project/text-to-music-prompt-structurer/) | Structured prompt extraction for text-to-music generation workflows. |

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

Python · R · Julia · Java · C · C++ · Rust · TypeScript · JavaScript · HTML5 · CSS3

</details>

<details>
  <summary><b>AI Systems & Tooling</b></summary>

PyTorch · Jupyter · LlamaIndex · PostgreSQL · pgvector · ChromaDB · React · Streamlit · Gradio · Docker · Quarto · Docusaurus · MDX · Jinja

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

Windows · macOS · VS Code · Git · GitHub

</details>
