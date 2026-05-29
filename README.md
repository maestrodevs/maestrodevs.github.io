<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-lockup-light.svg">
    <img src="logo-lockup.svg" alt="Maestro" width="380">
  </picture>
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
pip install maestro-fleet
```

(The public PyPI distribution name is `maestro-fleet`; the Python import is `maestro`.) For advanced / airgapped installs, the private wheel index here at `https://maestrodevs.github.io/simple/` ships the same wheels under the original `maestro` name:

```bash
pip install maestro --extra-index-url https://maestrodevs.github.io/simple/
```

Then verify:

```bash
mso version          # → Maestro vX.Y.Z
```

## Links

| | |
|---|---|
| **Maestro** | https://maestrodevs.com/ |
| **Maestro Doco** | https://docs.maestrodevs.com/ |
| **Package index** | https://maestrodevs.github.io/simple/ |
| **Landing page** | https://maestrodevs.github.io/ |

## How publishing works

New wheels are published automatically by the Maestro source repo's release workflow: tagging a release builds the wheel, drops it under `wheels/`, and refreshes the `simple/maestro/` index. No manual steps here.

---

<p align="center"><sub>© Maestro · Built for Claude Code.</sub></p>
