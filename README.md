# 🎮 AI GAME STUDIO

> **Master Autonomous AI-Powered Game Development Environment**

**AI Game Studio** is a professional desktop application that turns natural language descriptions into fully functional, playable games. Powered by Electron, React, TypeScript, and OpenCode, it orchestrates specialized AI agents, Model Context Protocol (MCP) servers, game engines, asset management, and self-healing test loops to automate the entire software development lifecycle.

---

## 🌟 Key Capabilities

* **Natural Language to Game**: Describe game concepts in plain English; the system infers genre, mechanics, camera perspective, platforms, and generates a structured Game Design Document (`/docs/GDD.md`).
* **Autonomous AI Game Director**: Coordinates dedicated specialized agents:
  * 🎨 **Game Designer Agent**: Mechanics, game loop, balancing, GDD maintenance.
  * 💻 **Programmer Agent**: Code architecture, component implementation, integration.
  * 📦 **Asset Agent**: Discovery, licensing compliance (CC0/Public Domain), downloads, and setup.
  * 🧪 **QA Agent**: Playwright-based gameplay, interaction, and console error testing.
  * 🐛 **Debugging Agent**: Stack trace analysis, root cause identification, and automated fixes.
  * ⚡ **Optimization Agent**: Memory usage, CPU/GPU draw calls, asset reduction.
  * 🏗️ **Build Agent**: Packaging, multi-platform exporting, and deployment.
* **Self-Healing Development Loop**: Automatically runs `BUILD → TEST → LOG ANALYSIS → FIX → RE-TEST` until target criteria pass without entering infinite loops.
* **Multi-Engine Target Support**:
  * **HTML / Web**: Canvas, WebGL, Three.js with live preview controls (Play, Pause, Restart, Screenshots, Performance monitor).
  * **Unity Engine**: Automated project scaffolding, C# scripting, scene management, batch-mode compilation, and runtime log parsing.
* **Zero Simulated Output**: Displays real terminal process logs via `xterm.js`, real execution outputs via OpenCode CLI, and strict error reporting (never generates false successes).

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| **Desktop Shell** | Electron, Node.js main process with secure `contextBridge` / IPC |
| **Frontend UI** | React, TypeScript, Vite, Modern CSS |
| **State & Storage** | Zustand, Local SQLite database (Projects, metadata, model/task history) |
| **Editor & Terminal** | Monaco Editor, `xterm.js` for real system process output |
| **AI & CLI Engine** | OpenCode CLI, OpenRouter / OpenAI-compatible APIs |
| **Protocols & Tools**| Model Context Protocol (MCP), Playwright Browser Testing, Custom `SKILL.md` workflows |
| **Packaging** | `electron-builder` |

---

##**Some reference photos for the application. These photos were generated with AI; we are just sharing them to give you an idea.**
