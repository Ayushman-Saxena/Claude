<div align="center">

# 🦞 CLAW CODE
**The Blazing-Fast, Open-Source Claude Code Alternative (Built in Rust)**

[![Rust](https://img.shields.io/badge/Built_with-Rust_🦀-f26522?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![Discord](https://img.shields.io/discord/1234567890?color=7289da&label=Discord&logo=discord&style=for-the-badge)](https://discord.gg/5TUQKqFWd)

[Usage Guide](./USAGE.md) • [Rust Workspace](./rust/README.md) • [Parity Status](./PARITY.md) • [Roadmap](./ROADMAP.md)

<img src="assets/claw-hero.jpeg" alt="Claw Code Hero Image" width="400" style="border-radius: 15px; box-shadow: 0 8px 16px rgba(0,0,0,0.3); margin: 20px 0;" />

*Run the official Claude CLI harness entirely in the open. Faster, lighter, and completely hackable.*

</div>

---

## 📖 What is this? (The Context)

Recently, Anthropic released **Claude Code**—a powerful terminal-based AI assistant that can read your files, write code, run bash commands, and fix bugs autonomously right inside your CLI. 

However, the official tool is closed-source and written in Node.js/TypeScript. 

**Claw Code** is our answer to that. We rebuilt the exact same tool from the ground up using **Rust**. Our goal? To give developers an open-source, fully transparent, and heavily optimized version of the Claude CLI that you can run, modify, and hack on locally.

---

## ⚡ Why use Claw Code?

| Feature | Plain English Description |
| :--- | :--- |
| **🚀 Lightning Fast** | Because it's written in Rust, it starts up instantly and uses way less memory than the official Node.js version. |
| **🛠️ Your Terminal, Automated** | It can safely run bash commands, edit your files, search through your codebase, and pull data from the web. |
| **🔌 Plug & Play Tools (MCP)** | Full support for the Model Context Protocol (MCP). Want it to talk to your database or Notion? Just connect a server. |
| **🤖 Use Any AI Model** | Works perfectly with Anthropic and OpenAI API formats. Plus, smooth text streaming right in your terminal. |

---

## 💻 Quick Start

Get your AI agent up and running in under 60 seconds.

**1. Build the project:**
```bash
cd rust
cargo build --workspace
```

**2. Log in with your Anthropic Account:**
```bash
./target/debug/claw login
```
*(Alternatively, you can just set `export ANTHROPIC_API_KEY="sk-ant-..."`)*

**3. Ask it to do something:**
```bash
./target/debug/claw prompt "summarize this repository"
```

> **Note:** Make sure to run `./target/debug/claw doctor` as your first health check to ensure everything is set up correctly!

---

<details>
<summary><b>📂 Repository Breakdown (Click to expand)</b></summary>
<br>

If you want to poke around the code, here is where everything lives:

- **`rust/`** — The actual codebase. This is where the magic happens and where the `claw` CLI is built.
- **`USAGE.md`** — A simple guide on how to use the commands and features.
- **`PARITY.md`** — A checklist showing how close we are to matching 100% of the official Claude Code's features.
- **`ROADMAP.md`** — What we are building next.
- **`PHILOSOPHY.md`** — Why we made this project and our design choices.

</details>

---

## 🌍 The UltraWorkers Ecosystem

Claw Code doesn't live in isolation. We are building the future of open-source AI dev tools alongside:
* 🦞 [clawhip](https://github.com/Yeachan-Heo/clawhip)
* 🐙 [oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)
* 🧠 [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)
* 👾 [oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)

Want to contribute or just hang out? Join the discussion in the **[UltraWorkers Discord](https://discord.gg/5TUQKqFWd)**!

---

<div align="center">

**Disclaimer** <br>
*This repository does not claim ownership of the original Claude Code source material. It is not affiliated with, endorsed by, or maintained by Anthropic.*

</div>
