<div align="center">

# 🦞 CLAW CODE
**The Blazing-Fast, Open-Source Claude Code Alternative built in Rust.**

[![Rust](https://img.shields.io/badge/Built_with-Rust_🦀-f26522?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![Discord](https://img.shields.io/discord/1234567890?color=7289da&label=Discord&logo=discord&style=for-the-badge)](https://discord.gg/5TUQKqFWd)

[Usage Guide](./USAGE.md) • [Rust Workspace](./rust/README.md) • [Parity Status](./PARITY.md) • [Roadmap](./ROADMAP.md)

<img src="assets/claw-hero.jpeg" alt="Claw Code Hero Image" width="400" style="border-radius: 15px; box-shadow: 0 8px 16px rgba(0,0,0,0.3); margin: 20px 0;" />

*Run the official Claude CLI harness entirely in the open. Faster, lighter, and completely hackable.*

</div>

---

## ⚡ Why Claw Code?

| Feature | Description |
| :--- | :--- |
| **🚀 Unmatched Speed** | Written entirely in Rust. Near-zero startup time and minimal memory footprint compared to Node.js. |
| **🛠️ Native Tools** | Built-in bash execution, native file read/write, fast grepping, and web fetching. |
| **🔌 MCP Protocol** | Full support for the Model Context Protocol. Connect your own tools instantly. |
| **🤖 Provider Agnostic** | Out-of-the-box Anthropic/OpenAI compatibility with smooth SSE streaming. |

> [!NOTE]  
> **Source of Truth:** Claw Code is the public Rust implementation of the `claw` CLI agent harness. The canonical implementation lives in [`rust/`](./rust). Make `claw doctor` your first health check after building!

---

## 💻 Quick Start

Get up and running in under 60 seconds:

```bash
# 1. Navigate to the workspace
cd rust

# 2. Build the lightning-fast binary
cargo build --workspace

# 3. Ask it anything
./target/debug/claw prompt "summarize this repository"
```

### 🔐 Authentication
Use your API key or the built-in OAuth flow:
```bash
export ANTHROPIC_API_KEY="sk-ant-..."
# OR run the interactive login:
./target/debug/claw login
```

---

<details>
<summary><b>📂 Click to view Repository Architecture</b></summary>
<br>

- **`rust/`** — Canonical Rust workspace and the `claw` CLI binary
- **`USAGE.md`** — Task-oriented usage guide for the current product surface
- **`PARITY.md`** — Rust-port parity status and migration notes
- **`ROADMAP.md`** — Active roadmap and cleanup backlog
- **`PHILOSOPHY.md`** — Project intent and system-design framing

</details>

---

## 🌍 The UltraWorkers Ecosystem

Claw Code doesn't live in isolation. We are building the future of open-source agentic tooling:
* 🦞 [clawhip](https://github.com/Yeachan-Heo/clawhip)
* 🐙 [oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)
* 🧠 [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)
* 👾 [oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)

Join the discussion in the **[UltraWorkers Discord](https://discord.gg/5TUQKqFWd)**!

---

<div align="center">

**Disclaimer** <br>
*This repository does not claim ownership of the original Claude Code source material. It is not affiliated with, endorsed by, or maintained by Anthropic.*

</div>
