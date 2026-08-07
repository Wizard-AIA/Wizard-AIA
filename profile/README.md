# 🧙‍♂️ Wizard

A **local-first autonomous data analysis agent.** Ask a real question about
your data; it investigates — looking, computing, revising its approach when
the data disagrees with it — then verifies the result and explains it,
streaming its reasoning as it goes.

Your data never leaves your machine unless you explicitly choose a cloud
provider. No API key required to start — two small [Ollama](https://ollama.com/)
models are enough to be useful.

**[📖 Documentation](https://wizard-aia.github.io/docs/)** ·
**[🚀 Quickstart](https://wizard-aia.github.io/docs/getting-started/installation/)** ·
**[💬 Discussions](https://github.com/Wizard-AIA/Wizard-w2/discussions)**

---

## Repositories

| Repo | What it is |
|---|---|
| **[Wizard-w2](https://github.com/Wizard-AIA/Wizard-w2)** | The core engine — FastAPI backend, Next.js frontend, and a Go CLI daemon. Start here. |
| **[docs](https://github.com/Wizard-AIA/docs)** | Source for the [documentation site](https://wizard-aia.github.io/docs/). |
| **[skills](https://github.com/Wizard-AIA/skills)** | Community registry of `SKILL.md` files the agent can retrieve and cite mid-analysis. |
| **[.github](https://github.com/Wizard-AIA/.github)** | Organization-wide default community health files. |

## Why Wizard

- **It runs the code, it doesn't just suggest it.** Results come from real
  execution, not a model claiming an answer.
- **It checks its own work.** The headline result is recomputed by a
  different route, and any figure that isn't grounded in real output is
  flagged rather than quietly presented.
- **Docker is optional, not a fallback.** Generated code runs in a sandboxed
  subprocess by default — OS-native containment on Linux, macOS, and
  Windows — or in a container if you opt into that instead.
- **It's honest about degradation.** No embedding model? Retrieval falls
  back to word overlap. Model unreachable? A clear message, not a hang.

BSD-3-Clause licensed. See
[CONTRIBUTING.md](https://github.com/Wizard-AIA/Wizard-w2/blob/master/CONTRIBUTING.md)
in the core repo to get involved.
