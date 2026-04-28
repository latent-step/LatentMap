# LatentMap

> AI Agent Observability for Code — watch AI agents edit your codebase live, drill from package to function, navigate calls with proper edge semantics.

VS Code extension. Python only (Stage 1).

---

## Why

When you run multiple AI coding agents (Cursor, Claude Code, Cline) at once, you lose track of *what is happening where*. Diff views show what changed *after* it changed. LatentMap shows it *as it happens*, on a spatial map of your codebase.

- 🟢 added · 🔴 removed · 🔵 modified · 🟡 affected
- Drill from package → module → class → function
- Vertical edges = value flow · horizontal edges = call relationship

---

## Install

1. Download the latest `.vsix` from the [Releases page](https://github.com/latent-step/LatentMap/releases).
2. In VS Code, open the Command Palette (`⌘+Shift+P` / `Ctrl+Shift+P`) and run **`Extensions: Install from VSIX…`**.
3. Pick the downloaded file. Restart VS Code if prompted.

---

## Quick start

1. Open a Python project in VS Code.
2. Command Palette → **`LatentMap: Open Canvas (Entire Workspace)`**.
3. Double-click any module / class to drill in.
4. `V` / `H` to toggle Select / Pan tool. `Cmd+Click` jumps to source.

*(Screenshots and a longer walkthrough coming soon.)*

---

## Issues & feedback

[Submit an issue or start a discussion](https://github.com/latent-step/LatentMap/issues) — bug reports, feature requests, and use cases all welcome.

---

## License

**Proprietary — All rights reserved.** Source code is private. The `.vsix` is provided for evaluation only. See [LICENSE](./LICENSE) for full terms (or the LICENSE shipped inside the `.vsix`).

For commercial licensing inquiries: johnlu0410@gmail.com
