# 🧙‍♂️ Wizard

> A local-first autonomous data analysis agent. Ask a real question about your data; it investigates — looking, computing, revising its approach when the data disagrees with it — then verifies the result and explains it, streaming its reasoning as it goes.

![Status](https://img.shields.io/badge/Status-Active-success) [![Release](https://img.shields.io/github/v/release/Wizard-AIA/Wizard-w2?label=Release&color=orange)](https://github.com/Wizard-AIA/Wizard-w2/releases/latest) [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://github.com/Wizard-AIA/Wizard-w2/blob/master/LICENSE) [![Docs](https://img.shields.io/badge/Docs-wizard--aia.github.io-blue)](https://wizard-aia.github.io/docs/) [![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/Wizard-AIA/Wizard-w2/badge)](https://scorecard.dev/viewer/?uri=github.com/Wizard-AIA/Wizard-w2)

Your data never leaves your machine unless you choose a cloud provider. No API key is required — two small [Ollama](https://ollama.com/) or [LM Studio](https://lmstudio.ai/) models running locally are all it takes.

**[📖 Documentation](https://wizard-aia.github.io/docs/)** · **[🚀 Quickstart](https://wizard-aia.github.io/docs/getting-started/installation/)** · **[💬 Discussions](https://github.com/Wizard-AIA/Wizard-w2/discussions)** · **[📦 Latest Release](https://github.com/Wizard-AIA/Wizard-w2/releases/latest)**

---

## ⚡ Quick Download

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
| **[docs](https://github.com/Wizard-AIA/docs)** | Official documentation site source and technical architecture specifications. |
| **[skills](https://github.com/Wizard-AIA/skills)** | Community registry of curated `SKILL.md` know-how files the agent retrieves and executes mid-turn. |
| **[.github](https://github.com/Wizard-AIA/.github)** | Organization-wide default issue templates, security reporting, and community guidelines. |

---

## 🌟 Why Wizard

- **Local-First & Private:** Your datasets and query results never leave your hardware.
- **Real Code Execution:** Answers are generated from actual executed code, not LLM guesswork.
- **Self-Correction & Trust:** Automatic execution retry on Python tracebacks and self-verification of headline analytical claims.
- **Full Analytical Stack:** Native support for Pandas, DuckDB, Polars, Scipy, Statsmodels, Scikit-Learn, and Plotly.
- **Flexible Sandboxing:** Runs securely in OS-native subprocesses (Landlock/seccomp, sandbox-exec, Job Objects) or Docker containers.

---

BSD-3-Clause Licensed. Contributions are welcome — see [CONTRIBUTING.md](https://github.com/Wizard-AIA/Wizard-w2/blob/master/CONTRIBUTING.md) to get involved.
