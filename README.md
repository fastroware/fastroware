# Hey, I'm fastroware 👋

I build tools that make software development faster, cleaner, and less bloated.

---

## ⚡ Featured Project: [`waitsec`](https://github.com/fastroware/waitsec)

> **Hold on. Think first. Code less.**  
> Practical guardrails for AI coding agents.

<p align="left">
  <a href="https://www.npmjs.com/package/waitsec"><img src="https://img.shields.io/npm/v/waitsec?color=black&style=flat-square" alt="NPM Version" /></a>
  <a href="https://packagist.org/packages/waitsec/waitsec"><img src="https://img.shields.io/packagist/v/waitsec/waitsec?color=black&style=flat-square" alt="Packagist Version" /></a>
  <a href="https://github.com/fastroware/waitsec/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License" /></a>
</p>

### Why did I build this?
Most AI coding assistants (Kilo Code, Cursor, Cline, Claude Code) move too fast and assume too much. You ask for a small fix, and the AI generates ten new files, rewrites unrelated code, and invents requirements out of nowhere.

`waitsec` acts as a brake:
- **`ask-first`** — Stops AI from guessing. It pauses and clarifies vague requirements before writing code.
- **`anti-overengineering`** — Rejects unneeded design patterns and speculative abstractions for simple tasks.
- **`small-diff`** — Keeps code modifications strictly scoped to what solves the prompt.
- **`debug-first`** — Forces AI to inspect error traces and find root causes instead of guessing fixes.

### Quick Run
```bash
npx waitsec
