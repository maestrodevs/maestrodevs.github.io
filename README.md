<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-lockup-light.svg">
    <img src="logo-lockup.svg" alt="Maestro" width="380">
  </picture>
</p>

<h1 align="center">Maestro - distribution</h1>

<p align="center">
  <em>Mission control for automation - AI-orchestrated multi-agent coding for Claude Code.</em>
</p>

---

This repository is the public **distribution channel** for the Maestro framework. From one GitHub Pages site at **https://maestrodevs.github.io/** it serves:

1. A **[PEP 503](https://peps.python.org/pep-0503/) simple package index** (`simple/`) hosting the `maestro` wheels.
2. The project **landing page** (`index.html`).

## Install

```bash
pip install maestro-fleet
```

The public PyPI distribution name is `maestro-fleet`; the Python import is `maestro`. Airgapped / restricted-egress operators can use this same wheel index as a private-index install source, under the original `maestro` distribution name - see the docs site's air-gapped install guide at https://docs.maestrodevs.com for the full pattern.

Then verify:

```bash
mso version          # → Maestro vX.Y.Z
```

## Links

| | |
|---|---|
| **Maestro** | https://maestrodevs.com/ |
| **Maestro Doco** | https://docs.maestrodevs.com/ |
| **Landing page** | https://maestrodevs.github.io/ |

---

<p align="center"><sub>© Maestro · Built for Claude Code.</sub></p>
