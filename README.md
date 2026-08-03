<div align="center">

# Marcel Stevano

### Native Linux Desktop Engineer — Rust · GTK4 · Libadwaita

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1200&color=3584E4&center=true&vCenter=true&width=760&lines=Rust+Systems+Engineer;GTK4+%26+Libadwaita+GUI+Engineer;Linux+Desktop+%26+CLI+Tooling;Building+Native+GNOME+Applications)](https://git.io/typing-svg)

<p>
<img src="https://img.shields.io/badge/status-actively--building-3584E4?style=flat-square"/>
<img src="https://img.shields.io/badge/platform-Linux%20%2F%20GNOME-2ec27e?style=flat-square"/>
<img src="https://img.shields.io/badge/language-Rust-orange?style=flat-square"/>
</p>

</div>

---

## About

I build native Linux desktop applications — not Electron wrappers, not cross-platform compromises. My stack is Rust for the core logic and GTK4 with Libadwaita for GUI, following GNOME Human Interface Guidelines so the applications feel like they belong on the desktop rather than being ported onto it.

Each GUI project is paired with a CLI counterpart, sharing the same core library. The GUI is a shell over the engine, not the engine itself — this keeps logic testable, scriptable, and reusable outside the desktop session.

**Principles I work by:**
- **Correctness over speed of shipping.** Compile errors and runtime panics are treated as design failures, not inconveniences to patch around.
- **No hidden dependencies on Electron/Chromium.** If it runs on Linux, it should feel native to Linux.
- **GUI and CLI share one core.** Business logic lives in a library crate; `app` and `app-cli` are thin binaries on top.
- **Documentation and install scripts are part of the deliverable**, not an afterthought — every project ships with proper multi-distro install/uninstall support.

---

## Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=rust,linux,git,bash,neovim"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/GTK4-3584E4?style=for-the-badge&logo=gtk&logoColor=white"/>
<img src="https://img.shields.io/badge/Libadwaita-4A86CF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Tantivy-D4A017?style=for-the-badge"/>
<img src="https://img.shields.io/badge/systemd-facfc9?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

| Layer | Tools |
|---|---|
| **Language** | Rust (stable toolchain, `cargo`) |
| **GUI Framework** | GTK4 + Libadwaita (`gtk4-rs`, `adw`) |
| **CLI** | `clap`-based argument parsing, shared core-crate architecture |
| **Search / Indexing** | Tantivy (full-text search engine, embedded) |
| **System Integration** | systemd journal (`journalctl` / `sd-journal` bindings), D-Bus |
| **Packaging** | Multi-distro install scripts (`.deb`, `.rpm`-aware, generic `install.sh`) |
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

*Built on Linux, for Linux — native by design..*

</div>
