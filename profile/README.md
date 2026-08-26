# 🧙‍♂️ Wizard

> A local-first autonomous data analysis agent. Ask a real question about your data; it investigates — looking, computing, revising its approach when the data disagrees with it — then verifies the result and explains it, streaming its reasoning as it goes.

![Status](https://img.shields.io/badge/Status-Active-success) [![Release](https://img.shields.io/github/v/release/Wizard-AIA/Wizard-w2?label=Release&color=orange)](https://github.com/Wizard-AIA/Wizard-w2/releases/latest) [![Homebrew](https://img.shields.io/badge/brew-wizard-green)](https://github.com/Wizard-AIA/homebrew-wizard) [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/Wizard-AIA/Wizard-w2) [![Awesome](https://awesome.re/badge-flat2.svg)](https://github.com/Wizard-AIA/awesome-wizard) [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://github.com/Wizard-AIA/Wizard-w2/blob/master/LICENSE) [![Docs](https://img.shields.io/badge/Docs-wizard--aia.github.io-blue)](https://wizard-aia.github.io/docs/) [![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/Wizard-AIA/Wizard-w2/badge)](https://scorecard.dev/viewer/?uri=github.com/Wizard-AIA/Wizard-w2)

Your data never leaves your machine unless you choose a cloud provider. No API key is required — two small [Ollama](https://ollama.com/) or [LM Studio](https://lmstudio.ai/) models running locally are all it takes.

**[📖 Documentation](https://wizard-aia.github.io/docs/)** · **[🚀 Quickstart](https://wizard-aia.github.io/docs/getting-started/installation/)** · **[💬 Discussions](https://github.com/Wizard-AIA/Wizard-w2/discussions)** · **[📦 Latest Release](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)**

---

## ⚡ Quick Start

### 🍺 Install with Homebrew (macOS & Linux)
```bash
brew install Wizard-AIA/wizard/wizard
wizard init && wizard start
```

### 📦 Standalone Packages
Download the prebuilt standalone package for your operating system, extract it, and launch:

| Operating System | Architecture | Download Package |
|---|---|---|
| **macOS** | Apple Silicon (M1 / M2 / M3 / M4) | [**`Wizard-v1.0.1-darwin-arm64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.1/Wizard-v1.0.1-darwin-arm64.zip) |
| **macOS** | Intel x86_64 | [**`Wizard-v1.0.1-darwin-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.1/Wizard-v1.0.1-darwin-amd64.zip) |
| **Linux** | x86_64 / amd64 | [**`Wizard-v1.0.1-linux-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.1/Wizard-v1.0.1-linux-amd64.zip) |
| **Linux** | ARM64 / aarch64 | [**`Wizard-v1.0.1-linux-arm64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.1/Wizard-v1.0.1-linux-arm64.zip) |
| **Windows** | x86_64 | [**`Wizard-v1.0.1-windows-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.1/Wizard-v1.0.1-windows-amd64.zip) |

```bash
# After extracting your zip:
./cli/wizard init       # Checks prerequisites & installs environment
./cli/wizard start      # Starts backend + frontend daemon and opens your browser
```

Open **http://localhost:3000** to begin analyzing your data.

---

## 🏛️ Ecosystem Repositories

| Repository | Description |
|---|---|
| **[Wizard-w2](https://github.com/Wizard-AIA/Wizard-w2)** | Core Engine: FastAPI backend, Next.js analytical workspace, OS-contained sandboxes, and Go CLI supervisor. |
| **[awesome-wizard](https://github.com/Wizard-AIA/awesome-wizard)** | Curated playbooks, sample datasets, local model recipes, and community integrations. |
| **[homebrew-wizard](https://github.com/Wizard-AIA/homebrew-wizard)** | Official Homebrew tap for one-command macOS and Linux installation (`brew install wizard`). |
| **[docs](https://github.com/Wizard-AIA/docs)** | Official documentation site source and technical architecture specifications. |
| **[skills](https://github.com/Wizard-AIA/skills)** | Community registry of curated `SKILL.md` know-how files the agent retrieves and executes mid-turn. |
| **[.github](https://github.com/Wizard-AIA/.github)** | Organization-wide issue forms, welcome automation, and security policies. |

---

## 🌟 Why Wizard

- **Local-First & Private:** Your datasets and query results never leave your hardware.
- **Real Code Execution:** Answers are generated from actual executed code, not LLM guesswork.
- **Self-Correction & Trust:** Automatic execution retry on Python tracebacks and self-verification of headline analytical claims.
- **Full Analytical Stack:** Native support for Pandas, DuckDB, Polars, Scipy, Statsmodels, Scikit-Learn, and Plotly.
- **Flexible Sandboxing:** Runs securely in OS-native subprocesses (Landlock/seccomp, sandbox-exec, Job Objects) or Docker containers.

---

## 👥 Contributors

Thank you to everyone building and improving Wizard!

[![Contributors](https://contrib.rocks/image?repo=Wizard-AIA/Wizard-w2)](https://github.com/Wizard-AIA/Wizard-w2/graphs/contributors)

---

BSD-3-Clause Licensed. Created by **Aniket Saha** ([@Aniket-a14](https://github.com/Aniket-a14)). Contributions are welcome — see [CONTRIBUTING.md](https://github.com/Wizard-AIA/Wizard-w2/blob/master/CONTRIBUTING.md) to get involved.
