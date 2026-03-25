# Changelog

All notable changes to Winaborator will be documented here.

---

## [0.1.0-beta] — 2025

### Initial beta release

This is the first public release of Winaborator. Everything is early-stage — expect bugs and missing polish. Feedback and bug reports are welcome via [GitHub Issues](https://github.com/jakeefr/winaborator-ai/issues).

#### What's included
- Infinite pan-and-zoom canvas with dot-grid background
- Terminal tiles (xterm.js + node-pty)
- Code editor tiles (Monaco Editor)
- Note / Markdown tiles
- Image viewer tiles
- Left-side file browser with workspace support
- File search (Ctrl+K)
- Right-side Sessions panel with live terminal status
- Workspace graph visualization
- Background presets (Plain, Midnight, Slate, Ember, Ocean)
- Persistent state — layout, tiles, background, and window position saved automatically
- Welcome modal on first launch
- Beta warning banner with issue link

#### Known issues
- Some drag-and-drop interactions may be unreliable
- Terminal session state is not restored after app restart (terminals reopen but history is lost)
- Graph visualization is early-stage
- Windows 10/11 only — no Mac or Linux support

---

*Inspired by [Collaborator](https://github.com/collaborator-ai/collab-public). Built from scratch for Windows.*
