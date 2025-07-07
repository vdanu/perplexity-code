# Perplexity-Code 💻

**AI-Driven Code Assistant — Built for Cursor, VSCode & CLI**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build](https://img.shields.io/github/actions/workflow/status/holasoymalva/perplexity-code/main.yml)](https://github.com/holasoymalva/perplexity-code/actions)
[![Twitter](https://img.shields.io/twitter/follow/holasoymalva?style=social)](https://twitter.com/holasoymalva)

> The power of Perplexity, reimagined for developers.  
> Ask questions. Generate code. Debug. Refactor. All inside your favorite code editor or terminal.

---

## 🧩 What is Perplexity-Code?

**Perplexity-Code** is a specialized edition of the Perplexity CLI built for **developers**, fully compatible with:

- 🖥️ **VS Code** (as a native extension)
- 🧠 **Cursor** (AI-first code editor)
- 🧪 **CLI workflows** (with syntax-aware code output)

Whether you're exploring a new framework, debugging an error, or refactoring legacy code — Perplexity-Code acts as your AI programming partner, wherever you code.

---

## 🔥 Features

- 🔍 **Semantic code search**: Ask anything — get precise, syntax-highlighted answers
- 💬 **Contextual chat mode**: Code-aware back-and-forth with inline memory
- 🛠️ **Code tools**: `/explain`, `/debug`, `/convert`, `/refactor`, `/optimize`
- 🧠 **Editor integrations**: Cursor and VSCode compatibility out-of-the-box
- ⚡ **CLI-mode** for fast, distraction-free querying
- 🧪 **Multi-model support** (Perplexity, Gemini, OpenAI)

---

## 🎯 Use Cases

- 🧑‍💻 Learn new libraries and patterns on the fly
- 🐛 Understand and fix complex bugs
- 🪄 Generate snippets in multiple languages
- 🔁 Refactor legacy codebases with AI guidance
- 📎 Summarize or document code files

---

## 🚀 Quickstart

### 1. Clone the Repo

```bash
git clone https://github.com/holasoymalva/perplexity-code.git
cd perplexity-code
````

### 2. Install dependencies

```bash
npm install
# or
pip install -r requirements.txt
```

### 3. Set up your API key

Create a `.env` file:

```env
PERPLEXITY_API_KEY=your_api_key_here
```

---

## 💻 Editor Integrations

### ✅ VSCode

1. Go to `Extensions > Install from VSIX`
2. Choose the `perplexity-code.vsix` file (coming soon)
3. Use `⌘⇧P` → `Perplexity: Ask AI` to start chatting with code context

### ✅ Cursor

1. Open `Settings > Plugins`
2. Add CLI integration path to `perplexity-code` binary
3. Use `⌘K` or `/` command palette to ask in context

---

## 🧪 CLI Usage

```bash
$ perplexity-code "What's the difference between useMemo and useCallback?"
```

```bash
$ perplexity-code /explain "What does this SQL query do?" -f ./query.sql
```

```bash
$ perplexity-code /refactor ./legacy-component.js
```

---

## ⚙️ Configuration

Customize behavior via `perplexity.config.json`:

```json
{
  "model": "perplexity-codellama",
  "defaultCommand": "/explain",
  "editor": "vscode",
  "language": "typescript"
}
```

---

## 🧱 Roadmap

* [ ] Inline VSCode explanations (hover)
* [ ] Git diff analysis and patch generation
* [ ] Multi-file context support
* [ ] Custom slash commands
* [ ] Offline fallback mode

---

## 🤝 Contribute

Perplexity-Code is community-driven.
We welcome contributions, feedback, and plugins.

```bash
# Fork and clone
git clone https://github.com/holasoymalva/perplexity-code.git
```

Pull requests are welcome. See `CONTRIBUTING.md` (coming soon).

---

## 📄 License

MIT License © 2025 [@holasoymalva](https://github.com/holasoymalva)

---

## 💬 Follow & Connect

Built with ❤️ by [@holasoymalva](https://twitter.com/holasoymalva)

> Let’s redefine how developers interact with knowledge.
