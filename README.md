<div align="center">

# Hey, I'm fastroware 👋

**Software craftsman focused on developer tooling, lean code, and anti-slop workflows.**

<br />

<p align="center">
  <a href="https://github.com/fastroware/waitsec"><img src="https://img.shields.io/badge/Project-waitsec-000000?style=for-the-badge&logo=github&logoColor=white" alt="waitsec" /></a>
  <a href="https://www.npmjs.com/package/waitsec"><img src="https://img.shields.io/npm/v/waitsec?style=for-the-badge&color=CB3837&logo=npm&logoColor=white" alt="npm" /></a>
  <a href="https://packagist.org/packages/waitsec/waitsec"><img src="https://img.shields.io/packagist/v/waitsec/waitsec?style=for-the-badge&color=F28D1A&logo=packagist&logoColor=white" alt="packagist" /></a>
</p>

</div>

---

## ⚡ Featured Project: [`waitsec`](https://github.com/fastroware/waitsec)

> **"Hold on. Think first. Code less."**  
> Practical guardrails that prevent AI coding agents from bloated diffs, overengineering, and blind assumptions.

<br />

### Why waitsec?
Most AI assistants (Kilo Code, Cursor, Cline, Claude Code) move too fast and assume too much:
- You ask for a small tweak, and the AI creates ten new abstraction layers.
- You report a one-line bug, and the AI modifies five unrelated files.
- You give a vague requirement, and the AI invents database schemas without asking.

`waitsec` acts as a practical brake:

| Guardrail | What It Does |
| :--- | :--- |
| **`ask-first`** | Forces AI to clarify missing requirements before writing code instead of guessing. |
| **`anti-overengineering`** | Rejects unneeded design patterns, DTOs, and speculative abstractions for simple tasks. |
| **`small-diff`** | Restricts code changes strictly to what solves the prompt without collateral edits. |
| **`debug-first`** | Mandates inspecting stack traces and root causes before touching code. |

<br />

### Quick Install

```bash
npx waitsec
```

Works out of the box with **Kilo Code**, **Cline**, **Cursor**, **Google Antigravity**, **Claude Code**, and **Laravel / PHP (Composer)**.

👉 **[View the Repository & Documentation →](https://github.com/fastroware/waitsec)**

---

## 📊 GitHub & Language Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fastroware&theme=tokyonight&show_icons=true&hide_border=true&layout=compact" alt="Top Languages" />
</div>

---

<div align="center">

**[GitHub](https://github.com/fastroware)** • **[NPM](https://www.npmjs.com/package/waitsec)** • **[Packagist](https://packagist.org/packages/waitsec/waitsec)**

</div>
