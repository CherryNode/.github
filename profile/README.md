<div align="center">

# 🍒 CherryNode

**Game server hosting** — built on a customized Pterodactyl panel.

![Panel](https://img.shields.io/badge/panel-Pterodactyl_1.14.1-blue?style=flat-square&logo=pterodactyl)
![Stack](https://img.shields.io/badge/stack-PHP_·_React_·_Go-777bb4?style=flat-square)
![Status](https://img.shields.io/badge/status-in_development-f59e0b?style=flat-square)

</div>

---

## What is CherryNode?

CherryNode is a game server hosting platform built on a heavily customized
[Pterodactyl](https://pterodactyl.io/) panel (Arix fork), with in-house tooling for
version management, server splitting, world management, and Discord integration.

## Repositories

| Repository | Description |
| ---------- | ----------- |
| [**panel**](https://github.com/CherryNode/panel) | The hosting panel — Pterodactyl 1.14.1 (Arix fork) + in-house features. |
| [**wings**](https://github.com/CherryNode/wings) | Custom Wings daemon — patched source (folder-size + server-importer). |
| [**eggs**](https://github.com/CherryNode/eggs)   | Minecraft egg catalog (82 eggs, PTDL_v2) + nest configuration. |

## Architecture

Repositories are split by **lifecycle**, not by "what they are" — things that change
together live together:

- **panel** — the production panel; where all feature work happens.
- **wings** — the node daemon; deployed per-node, on its own release cadence.
- **eggs** — portable data; versioned independently of the panel.

---

<div align="center">
<sub>© CherryNode · all repositories private</sub>
</div>
