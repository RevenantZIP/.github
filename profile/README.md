# Revenant 🩶

**Revenant** is a modular ecosystem of performance-focused, low-level tools for Windows — built for control, speed, and clarity.  
Crafted with Rust, C++, TypeScript, and Bun.js, Revenant rethinks what system utilities can be: elegant, hackable, and dead quiet.

---

## 🧩 Core Projects

- **Rift** — A fast, Scoop-compatible package manager written in Rust[^1]  
- **Grim** — Local-first terminal AI assistant with contextual memory  
- **Invoke** — TypeScript + Bun.js gateway to Claude Code and external AI providers  
- **RevenantUI** — Remote system management via Discord (C++ frontend, Bun.js backend)  
- **Specter** — Windows theming / ricing utility with declarative config  
- **Wraith** — Minimal, reactive system monitor with RevenantOS visuals[^2]

---

## ✴️ Design Philosophy

> *Minimal by default. Powerful by design.*  

Revenant tools are meant to stay quiet until needed — then act instantly. Each project is modular, scriptable, and designed with power users in mind.  
No clutter, no daemons, no unnecessary abstractions.

---

## 📁 Stack

- **Languages:** Rust · C++ · TypeScript · Zig (experimental)  
- **Runtime:** Bun.js · WSL2 · Native  
- **UX Goals:** CLI-first · Declarative configs · Low memory overhead  

---

[^1]: `rift` uses a Scoop-style bucket system but with modern Rust safety, better caching, and parallel downloads.  
[^2]: Wraith is optionally skinnable via RevenantUI’s theme pipeline.

