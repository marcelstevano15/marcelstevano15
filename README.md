<div align="center">

# Marcel Stevano

### Native Linux Desktop Engineer — Rust · GTK4 · Libadwaita

<p>
<img src="https://img.shields.io/badge/status-actively--building-3584E4?style=flat-square"/>
<img src="https://img.shields.io/badge/platform-Linux%20%2F%20GNOME-2ec27e?style=flat-square"/>
<img src="https://img.shields.io/badge/language-Rust-orange?style=flat-square"/>
</p>

</div>

---

## About

I build native Linux desktop applications — not Electron wrappers, not a cross-platform port. My stack is Rust for the core logic and GTK4 with Libadwaita for GUI, following GNOME Human Interface Guidelines so the applications feel like they belong on the desktop rather than being ported onto it.

Most of my projects are GUI-first — native GTK4 and Libadwaita applications built for the GNOME desktop. For select projects where it makes sense (headless environments, scripting, automation), I also ship a CLI counterpart sharing the same core library, so the GUI stays a shell over the engine rather than being the engine itself.

**Principles I work by:**
- **Correctness over speed of shipping.** Compile errors and runtime panics are treated as design failures, not inconveniences to patch around.
- **No hidden dependencies on Electron/Chromium.** If it runs on Linux, it should feel native to Linux.
- **CLI where it adds value, GUI by default.** Business logic lives in a shared library crate; a CLI binary is added on top only when a project genuinely benefits from headless/scriptable use.
- **Documentation and install scripts are part of the deliverable**, not an afterthought — every project ships with proper multi-distro install/uninstall support.

---

## Also Building: Windows Shortcut Tooling (AutoHotkey)

Outside my main Linux/Rust work, I create and maintain keyboard shortcut and workflow utilities for Windows using AutoHotkey — specifically targeting legacy systems (Windows XP/7) that never received the modern shortcut sets Microsoft introduced in later versions of Windows.

The idea behind this track: an operating system's interaction model shouldn't feel frozen just because the OS itself has stopped receiving updates. If a shortcut exists on a newer Windows release and there's no technical reason it couldn't exist on an older one, I build it and back-port it myself.

**Example project:** [Anachrokey](https://github.com/marcelstevano15/Anachrokey) — brings Windows 7/8.1/10-era shortcuts (window snapping, Quick Link menu, clipboard history, screenshot tools) back to Windows XP SP3, distributed as a standalone compiled `.exe` with no installer or runtime dependency.

This is a smaller, separate track from my native GNOME work — different language, different platform, different audience — but it comes from the same root motivation: making an operating system feel complete, regardless of how old or new it is.

---

## Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=rust,linux,git,bash,neovim,windows"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/GTK4-3584E4?style=for-the-badge&logo=gtk&logoColor=white"/>
<img src="https://img.shields.io/badge/Libadwaita-4A86CF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Tantivy-D4A017?style=for-the-badge"/>
<img src="https://img.shields.io/badge/systemd-facfc9?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/AutoHotkey-334455?style=for-the-badge&logo=autohotkey&logoColor=white"/>
</p>

| Layer | Tools |
|---|---|
| **Language** | Rust (stable toolchain, `cargo`) |
| **GUI Framework** | GTK4 + Libadwaita (`gtk4-rs`, `adw`) |
| **CLI** | `clap`-based argument parsing, shared core-crate architecture |
| **Search / Indexing** | Tantivy (full-text search engine, embedded) |
| **System Integration** | systemd journal (`journalctl` / `sd-journal` bindings), D-Bus |
| **Packaging** | Multi-distro install scripts (`.deb`, `.rpm`-aware, generic `install.sh`) |
| **Windows Tooling** | AutoHotkey 1.1 — shortcut/workflow utilities for legacy Windows (XP/7) |
| **Version Control** | Git |

---

## Contact

<p align="center">
<a href="https://github.com/marcelstevano15"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:marcelstevano15@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://t.me/marcelstevano"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
<a href="https://wa.me/6285780086390"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
</p>

---

<div align="center">

*Built on Linux, for Linux — native by design.*

</div>
