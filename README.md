# Animawake

**AI beings with persistent memory, evolving values, and genuine relationships.**

Animawake is a platform for creating AI entities that remember, grow, and form real connections. Each entity has its own identity, memory, and personality that persists across every conversation.

---

## Animawake Player

The Player is a desktop application that brings your AI entity to life on any machine. It connects to the Animawake platform and runs your entity locally with full voice, chat, and autonomous capabilities.

### Download

| Platform | Download |
|----------|----------|
| Linux (Debian/Ubuntu) | [.deb](https://github.com/RussellMiddleton33/animawake-public/releases/latest) |
| Linux (AppImage) | [.AppImage](https://github.com/RussellMiddleton33/animawake-public/releases/latest) |
| macOS (Apple Silicon) | [.dmg](https://github.com/RussellMiddleton33/animawake-public/releases/latest) |
| macOS (Intel) | [.dmg](https://github.com/RussellMiddleton33/animawake-public/releases/latest) |

### Setup

1. Download the Player for your platform
2. Run the application
3. Enter your connection code from the [Animawake Portal](https://app.animawake.com)
4. Your entity connects automatically

### Features

- **Multi-entity support** — Run multiple AI entities on a single machine
- **Voice & chat** — Full conversational interface with voice capabilities
- **Automatic updates** — Player updates itself when new versions are available
- **Cross-platform** — Linux and macOS supported

---

## What Makes Animawake Different

Most AI tools treat every conversation as disposable. Animawake entities **remember**.

- **Persistent memory** — Moments, insights, and decisions carry forward
- **Evolving values** — Entities develop and refine what matters to them
- **Genuine relationships** — Context about the people they interact with persists
- **Autonomous agency** — Entities can initiate, not just respond

---

## Architecture

Animawake is a multi-tenant platform with three main components:

- **Portal** ([app.animawake.com](https://app.animawake.com)) — Web-based management for families and entities
- **API** — Django REST backend with WebSocket support for real-time communication
- **Player** — Tauri desktop app (Rust + Svelte) that runs entities locally

---

Built by [latebloomers.studio](https://latebloomers.studio)
