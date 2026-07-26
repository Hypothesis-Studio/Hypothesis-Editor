# Hypothesis Editor

> Every Great Solution Starts with a Hypothesis.

A lightweight, extensible, and modern code editor built on Electron + React, designed for a fast, customizable, and productive development experience — with built-in AI, browser, database, REST client, tunnels, and more.

<p align="center">
  <img src="./Screenshot1.jpg" alt="Hypothesis Editor Screenshot" />
</p>

## 📦 Download

Get the latest release for your platform from [**GitHub Releases**](https://github.com/Hypothesis-Studio/Hypothesis-Editor/releases).

| Platform | Format |
|----------|--------|
| Windows  | `.exe` (installer), `.exe` (portable) |
| macOS    | `.dmg`, `.zip` |
| Linux    | `.AppImage`, `.deb`, `.rpm` |

---

## ✨ Features

### 🖊️ Editor
- Monaco-based code editor (same engine as VS Code)
- Syntax highlighting for 50+ languages
- Multi-tab editing with dirty state indicators
- Auto-save, trim whitespace, insert final newline, format on save
- Font picker: JetBrains Mono, Fira Code, Cascadia Code, Geist Mono, Monaspace Argon
- 4 built-in themes: Hypothesis Dark, Hypothesis Light, VS Dark, High Contrast
- Side-by-side diff viewer (right-click tab → Compare With...)
- Resizable split preview panel (drag divider, 15–85% range)
- File preview: HTML, Markdown, SVG, images, audio, video, PDF (auto-opens in preview mode)

### 🤖 AI Agent
- Autonomous multi-turn AI agent with tool execution
- 10 built-in tools: read/write/edit file, list/search files, terminal run, git status/log/diff, get open editors
- Provider support: OpenRouter, 9Router, OpenAI-compatible, custom gateways
- Streaming chat with collapsible code blocks, copy per message
- Right-click selected code → "Ask AI Agent" / "Fix With AI Agent"
- Slash commands: `/clear` `/reset` `/context` `/model` `/tools` `/status` `/export` `/help`
- Memory system with TF-relevance search
- Rate limiting, session persistence, real-time log viewer
- Open with `Ctrl+Shift+A`

### 🌐 Web Browser
- Full embedded browser via Electron WebView
- Multi-tab with favicon, loading spinner, pin tab
- Address bar with HTTPS lock icon, search suggestions
- Bookmarks with folders, history (grouped by day), downloads with progress
- Find in page (`Ctrl+F`), zoom, DevTools toggle
- New Tab page: clock, search, quick links, recent visits
- Open with `Ctrl+Shift+B`

### 🔌 Tunnels
- Forward any local port to a public URL instantly via LocalTunnel
- Multi-tunnel support — run multiple simultaneously
- Auto-reconnect with exponential backoff
- Custom subdomain and label per tunnel
- Per-tunnel HTTP request log: method, status, path, timestamp
- Copy URL to clipboard, open in browser, close individual or all tunnels
- Live status: Connecting / Connected / Error with animated indicator
- Accessible via Panel → Tunnels tab

### 🗄️ Database Explorer
- SQLite, PostgreSQL, MySQL/MariaDB support
- Connection manager with test, edit, delete
- Schema browser: tables, views, columns, indexes, foreign keys
- Table data viewer with pagination, NULL highlighting
- Multi-tab query editor with Ctrl+Enter to run
- Query history grouped by day with OK/Error badges
- Open with `Ctrl+Shift+D`

### 🔧 REST Client
- Full API testing client (like Postman/Insomnia)
- Collections and folders with ordering
- Request builder: Params, Headers, Body (raw/form/urlencoded/binary), Auth, Scripts tabs
- Auth: Bearer, Basic, API Key, OAuth2, Digest, AWS SigV4
- Pre-request and test scripts (sandboxed JS)
- Response: Body (pretty/raw), Headers, Cookies, Timeline, Tests, TLS Info
- Environments with `{{variable}}` interpolation
- Collection Runner with progress and assertion results
- Import: Postman, OpenAPI 3, Swagger 2, Insomnia, HAR, cURL
- Export: Native, Postman, OpenAPI 3, cURL, HAR
- cURL generator via right-click
- Open with `Ctrl+Shift+R`

### 📊 Project Insights
- Full project analysis dashboard
- File statistics, language breakdown, code complexity, dependency check
- Security vulnerability scan (`npm audit`), git health, duplicate detection
- Health score with ring chart and recommendations
- Real-time scan progress with 5-minute caching
- Open via ActivityBar dashboard icon

### 🔍 Search & Replace
- Full-text search across workspace files
- Replace and Replace All with preview
- Skips binary files and files >1MB for speed
- Parallel file reads with concurrency limit

### 📁 File Explorer
- Multi-root workspace support
- Create, rename, delete, copy, move files and folders
- Drag-and-drop support
- Previewable files auto-open in preview mode

### 🔀 Git Integration
- Full git workflow: stage, unstage, commit, push, pull, fetch
- Branch selector, create/checkout branch, merge
- Stash, discard changes
- Diff viewer, commit log
- Real git operations via `child_process`

### 💻 Terminal
- Integrated terminal via xterm.js
- Multiple terminal instances
- Run File (`Ctrl+F5`) with output captured to Output/Console/Problems panels
- Problem auto-parsing (Node.js, Python, compiler error patterns)

### 🔌 Extensions
- `.hyp` format (tar archive with `package.json` + `extension.js`)
- Install, enable, disable, uninstall from sidebar
- Export installed extensions
- Icon themes via `contributes.iconThemes`

### ⌨️ Command Palette
- `Ctrl+Shift+P` — access all commands
- Open Browser, REST Client, Database Explorer, Project Insights, Tunnels, Diff, and more

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Command Palette | `Ctrl+Shift+P` |
| Open Folder | `Ctrl+K Ctrl+O` |
| Save | `Ctrl+S` |
| Save All | `Ctrl+Shift+S` |
| Find in Files | `Ctrl+Shift+F` |
| AI Agent | `Ctrl+Shift+A` |
| Web Browser | `Ctrl+Shift+B` |
| REST Client | `Ctrl+Shift+R` |
| Database Explorer | `Ctrl+Shift+D` |
| Run File | `Ctrl+F5` |
| New Terminal | `Ctrl+`` ` |
| Keyboard Shortcuts | `Ctrl+K Ctrl+S` |

---

## 🔌 Extensions

Hypothesis supports a lightweight extension system. Extensions are `.hyp` files installable from the Extensions sidebar.

Browse community extensions at the [**Hypothesis Extension**](https://github.com/Hypothesis-Studio/Hypothesis-Extension) repository.

Build your own using the [Extension Boilerplate](https://github.com/Hypothesis-Studio/Hypothesis-Extension/tree/main/Extention-Boilerplate).

---

## 📋 Changelog

See [CHANGELOG.md](https://github.com/Hypothesis-Studio/Hypothesis-Editor-Source/blob/main/CHANGELOG.md) for full version history.

---

## 📄 License

[MIT](LICENSE) © 2026 Hypothesis Studio

<p align="center">
  <sub>Made with ❤️ by <a href="https://github.com/Hypothesis-Studio">Hypothesis Studio</a></sub>
</p>
