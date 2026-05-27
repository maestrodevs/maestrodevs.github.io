<p align="center">
  <img src="logo-lockup.svg" alt="Maestro" width="380">
</p>

<h1 align="center">Maestro — distribution</h1>

<p align="center">
  <em>Mission control for automation — AI-orchestrated multi-agent coding for Claude Code.</em>
</p>

---

This repository is the public **distribution channel** for the Maestro framework. From one GitHub Pages site at **https://maestrodevs.github.io/** it serves:

1. A **[PEP 503](https://peps.python.org/pep-0503/) simple package index** (`simple/`) hosting the `maestro` wheels.
2. The project **landing page** (`index.html`).

## Install

```bash
pip install --upgrade maestro --extra-index-url https://maestrodevs.github.io/simple/
```

Then verify:

```bash
mso version          # → Maestro vX.Y.Z
```

## Links

| | |
|---|---|
| **Source code** | https://github.com/tavisbasing/Maestro |
| **Package index** | https://maestrodevs.github.io/simple/ |
| **Landing page** | https://maestrodevs.github.io/ |

## How publishing works

New wheels are published automatically by the Maestro source repo's release workflow: tagging a release builds the wheel, drops it under `wheels/`, and refreshes the `simple/maestro/` index. No manual steps here.

---

<p align="center"><sub>© Maestro · Built for Claude Code.</sub></p>
