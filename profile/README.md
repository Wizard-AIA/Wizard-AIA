# 🧙‍♂️ Wizard

> A local-first autonomous data analysis agent. Ask a real question about your data; it investigates — looking, computing, revising its approach when the data disagrees with it — then verifies the result and explains it, streaming its reasoning as it goes.

[![Status](https://img.shields.io/badge/Status-Active-success)](https://github.com/Wizard-AIA/Wizard-w2) [![Release](https://img.shields.io/github/v/release/Wizard-AIA/Wizard-w2?label=Release&color=orange&logo=github)](https://github.com/Wizard-AIA/Wizard-w2/releases/latest) [![Homebrew](https://img.shields.io/badge/Homebrew-brew_wizard-2e7d32?logo=homebrew&logoColor=white)](https://github.com/Wizard-AIA/homebrew-wizard) [![Codespaces](https://img.shields.io/badge/Codespaces-Open_in_Cloud-blue?logo=githubcodespaces&logoColor=white)](https://codespaces.new/Wizard-AIA/Wizard-w2) [![Awesome](https://img.shields.io/badge/Awesome-Wizard-fc60a8?logo=awesomelists&logoColor=white)](https://github.com/Wizard-AIA/awesome-wizard) [![OpenSSF Scorecard](https://img.shields.io/badge/OpenSSF_Scorecard-9.5%2F10-success?logo=openssf&logoColor=white)](https://scorecard.dev/viewer/?uri=github.com/Wizard-AIA/Wizard-w2) [![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)](https://www.python.org/) [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://github.com/Wizard-AIA/Wizard-w2/blob/master/LICENSE) [![Docs](https://img.shields.io/badge/Docs-wizardw2.vercel.app-6366f1?logo=vercel&logoColor=white)](https://wizardw2.vercel.app/)

Your data never leaves your machine unless you choose a cloud provider. No API key is required — two small [Ollama](https://ollama.com/) or [LM Studio](https://lmstudio.ai/) models running locally are all it takes.

**[📖 Documentation](https://wizardw2.vercel.app/docs)** · **[🚀 Quickstart](https://wizardw2.vercel.app/docs/getting-started/installation)** · **[💬 Discussions](https://github.com/Wizard-AIA/Wizard-w2/discussions)** · **[📦 Latest Release](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)**

---

## ⚡ Quick Start

### 🚀 1-Command Automated Installers

**Linux & macOS:**
```bash
curl -fsSL https://wizardw2.vercel.app/install.sh | bash
```

**Windows (PowerShell):**
```powershell
irm https://wizardw2.vercel.app/install.ps1 | iex
```

**Homebrew (macOS & Linux):**
```bash
brew tap Wizard-AIA/wizard && brew install wizard
```

### 📦 Standalone Packages
Download the prebuilt standalone package for your operating system, extract it, and launch:

| Operating System | Architecture | Download Package |
|---|---|---|
| **macOS** | Apple Silicon (M1 / M2 / M3 / M4) | [**`Wizard-v1.0.5-darwin-arm64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-darwin-arm64.zip) |
| **macOS** | Intel x86_64 | [**`Wizard-v1.0.5-darwin-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-darwin-amd64.zip) |
| **Linux** | x86_64 / amd64 | [**`Wizard-v1.0.5-linux-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-linux-amd64.zip) |
| **Linux** | ARM64 / aarch64 | [**`Wizard-v1.0.5-linux-arm64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-linux-arm64.zip) |
| **Windows** | x86_64 | [**`Wizard-v1.0.5-windows-amd64.zip`**](https://github.com/Wizard-AIA/Wizard-w2/releases/download/v1.0.5/Wizard-v1.0.5-windows-amd64.zip) |

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
| **[Wizard-w2](https://github.com/Wizard-AIA/Wizard-w2)** | Core Engine: FastAPI backend, analytical workspace, OS-contained sandboxes, and Go CLI supervisor. |
| **[website](https://github.com/Wizard-AIA/website)** | Official website, landing page, and comprehensive documentation hub. |
| **[awesome-wizard](https://github.com/Wizard-AIA/awesome-wizard)** | Curated playbooks, sample datasets, local model recipes, and community integrations. |
| **[homebrew-wizard](https://github.com/Wizard-AIA/homebrew-wizard)** | Official Homebrew tap for one-command macOS and Linux installation (`brew install wizard`). |
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
