</p>

<h1 align="center">B.O.N. SOFTWARE</h1>

<p align="center">
  <b>SECURITY TOOLS AND SCRIPTS</b><br>
  <b>FOR THE BON-INTOSH AND THE B-RICK</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-early%20development-orange?style=for-the-badge" alt="Status: early development">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
</p>

The software side of **[B-Together](https://github.com/BA-Varlet)**: the tools and scripts that run on the [Bon-intosh](https://github.com/BA-Varlet/Bon-intosh) command center and the [B-rick](https://github.com/BA-Varlet/B-rick) mobile companion. Each tool lives in its own folder with its own README, and I add new ones as the project grows.

**B.O.N stands for:** [Built on Nostalgia]

> **Status:** Early development. The hardware is still being built, so most tools below are planned and not yet written. The table shows which ones actually work.

---

## Tools

| Tool | What it does | Runs on | Status |
|---|---|---|---|
| [`recon-scanner`](recon-scanner/) | Lists nearby Wi-Fi networks (signal, channel, encryption) and Bluetooth devices, with a local dashboard | Bon-intosh | Planned |
| [`bluetooth-link`](bluetooth-link/) | Data link and message format between the Bon-intosh and the B-rick | Both | Planned |


<!-- Status key: Idea, Planned, In progress, Working. -->

## Repo layout

```
b-together-software/
├── README.md
├── .gitignore
├── LICENSE
├── recon-scanner/     one folder per tool, each with its own README
├── bluetooth-link/
└── docs/              protocol notes and shared design docs
```

Every tool folder should have a short README that covers what it does, how to run it, and what it should only be used on.

## Getting started

[TBA]

```bash
# example, replace when real
git clone [REPO-URL]
cd [REPO-FOLDER]
```

## Responsible use

These tools are for learning and for testing networks and devices that I own or have explicit written permission to assess. Scanning or attacking systems without authorization is illegal and unethical, and I don't support using this code that way. Captured data can contain private information.

## Related repos

- [B-Together](https://github.com/BA-Varlet): the umbrella project and my profile
- [Bon-intosh](https://github.com/BA-Varlet/Bon-intosh): the command center hardware and base setup
- [B-rick](https://github.com/BA-Varlet/B-rick): the mobile companion hardware and base setup

## License

[MIT]
