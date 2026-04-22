<h1 align="center">Hi, I'm <a href="https://github.com/qbit-glitch">qbit-glitch</a> 👋</h1>

<p align="center">
  <samp>
    Building tools that make AI agents remember. <br/>
    Rust · Python · Systems · Machine Learning · Agent Infrastructure
  </samp>
</p>

<p align="center">
  <a href="https://github.com/qbit-glitch?tab=repositories"><img alt="Repos" src="https://img.shields.io/badge/Repos-40+-blue?style=flat-square&logo=github"></a>
  <a href="https://pypi.org/user/qbit-glitch/"><img alt="PyPI" src="https://img.shields.io/badge/PyPI-ccr--memory-3775A9?style=flat-square&logo=pypi&logoColor=white"></a>
</p>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [CCR](https://github.com/qbit-glitch/ccr) — Continuous Context Retention

> **Persistent memory and self-evolving playbooks for AI agents.**

An MCP server that gives AI agents **long-term memory** across sessions. No more starting from scratch every time you open a new chat.

- 🧠 **Git-style versioned memory** (GCC) — branch, merge, search history
- 📓 **Playbooks** (ACE) — structured strategy bullets with optional LLM-powered evolution
- 🛡️ **Sandboxed Python REPL** (RLM) — AST validation + restricted builtins
- 🔌 **Multi-agent** — full hooks for Claude Code & Kimi; MCP for Continue.dev; SDK wrappers for Ollama & OpenAI
- ⚡ **No external database** — SQLite + flat files, runs entirely local

```bash
pip install ccr-memory
ccr install-global
```

[![GitHub Repo stars](https://img.shields.io/github/stars/qbit-glitch/ccr?style=social)](https://github.com/qbit-glitch/ccr/stargazers)
[![PyPI](https://img.shields.io/pypi/v/ccr-memory?color=3775A9&label=PyPI&logo=pypi&logoColor=white)](https://pypi.org/project/ccr-memory/)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://github.com/qbit-glitch/ccr/blob/main/LICENSE)

</td>
<td width="50%" valign="top">

### [Unsupervised Panoptic Segmentation](https://github.com/qbit-glitch/unsupervised_panoptic_segmentation)

> **NeurIPS 2026 Submission** — First unsupervised panoptic segmentation system using state space models for cross-modal fusion.

MBPS tackles unsupervised panoptic segmentation by bridging semantic and instance branches through a novel Mamba2-based Structured State Space Duality (SSD) fusion mechanism. Operates without any human annotations.

- 🌉 **Adaptive Projection Bridge (APB)** — Fuses heterogeneous semantic + instance features into shared 192-dim space
- 🎯 **Unified Depth Conditioning (UDCM)** — FiLM-style modulation from monocular ZoeDepth estimates
- 🔄 **Bidirectional Cross-Modal Scan (BiCMS)** — Mamba2 SSD on interleaved tokens with learned gating
- 🧠 **Stuff-Things Classifier (STC)** — Automatic discrimination via depth boundary density, cluster compactness, and decomposition frequency

[![JAX](https://img.shields.io/badge/JAX-4285F4?style=flat-square&logo=google&logoColor=white)](https://github.com/qbit-glitch/unsupervised_panoptic_segmentation)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/qbit-glitch/unsupervised_panoptic_segmentation)
[![NeurIPS](https://img.shields.io/badge/NeurIPS%202026-Under%20Review-orange?style=flat-square)](https://github.com/qbit-glitch/unsupervised_panoptic_segmentation)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">
</p>

---

## 📂 Projects

### Agent Infrastructure & Tools

| Project | Language | Description |
|---------|----------|-------------|
| **[ccr](https://github.com/qbit-glitch/ccr)** | Python | Persistent memory MCP server for AI agents |
| **[ruflo](https://github.com/qbit-glitch/ruflo)** *(fork)* | Python | Agent orchestration platform for Claude |

### Systems & Rust

| Project | Language | Description |
|---------|----------|-------------|
| **[rust_os](https://github.com/qbit-glitch/rust_os)** | Rust | Operating system experiments in Rust |
| **[rusty-store](https://github.com/qbit-glitch/rusty-store)** | Rust | A Rust-based key-value store |
| **[redis-cli-codecrafters](https://github.com/qbit-glitch/redis-cli-codecrafters)** | Shell | Redis CLI implementation challenge |
| **[simple-calculator-rust](https://github.com/qbit-glitch/simple-calculator-rust)** | Rust | Calculator in Rust |

### Machine Learning & Computer Vision

| Project | Language | Description |
|---------|----------|-------------|
| **[wrong_parking_car_detection](https://github.com/qbit-glitch/wrong_parking_car_detection)** | Python | Computer vision-based parking violation detection |
| **[unsupervised_panoptic_segmentation](https://github.com/qbit-glitch/unsupervised_panoptic_segmentation)** | Jupyter | Unsupervised panoptic segmentation research |
| **[proposed_methodology](https://github.com/qbit-glitch/proposed_methodology)** | Python | ML methodology experiments |
| **[pytorch_tutorials](https://github.com/qbit-glitch/pytorch_tutorials)** | Jupyter | PyTorch learning notebooks |

### Web & Applications

| Project | Language | Description |
|---------|----------|-------------|
| **[oracle-search](https://github.com/qbit-glitch/oracle-search)** | JavaScript | Search interface with oracle integration |
| **[word-of-day](https://github.com/qbit-glitch/word-of-day)** | JavaScript | Daily word learning app |
| **[RAG-support-ticket-system](https://github.com/qbit-glitch/RAG-support-ticket-system)** | Jupyter | RAG-based support ticket system |

### Blockchain & Security

| Project | Language | Description |
|---------|----------|-------------|
| **[programming_bitcoin](https://github.com/qbit-glitch/programming_bitcoin)** | Jupyter | Bitcoin protocol implementation studies |
| **[shellclass](https://github.com/qbit-glitch/shellclass)** | Shell | Shell scripting experiments |

---

## 📊 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=qbit-glitch&show_icons=true&theme=tokyonight&hide_border=true&count_private=true">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=qbit-glitch&layout=compact&theme=tokyonight&hide_border=true&langs_count=8">
</p>

---

## 🌱 Currently Learning

- **Rust systems programming** — OS dev, memory-safe concurrency
- **Agent infrastructure** — MCP, context compression, multi-agent orchestration
- **ONNX & edge ML** — Running models without GPU dependency

---

## 📫 Connect

<p align="center">
  <a href="https://github.com/qbit-glitch"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://pypi.org/user/qbit-glitch/"><img alt="PyPI" src="https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white"></a>
</p>

---

<p align="center">
  <samp>
    <i>"The best time to start a project was yesterday. The second best time is now."</i>
  </samp>
</p>
