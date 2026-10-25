
```
root@robisolutionsit:~$ whoami
```

<div align="center">

# Robert Senenko

### Bridging Silicon & Software

**Hardware & firmware engineer moving into DevOps**

25+ years of component-level electronics repair, now applied to Linux infrastructure:<br>
measurement first, conclusion second.

`Component-level repair` ⟶ `Linux & virtualization` ⟶ `DevOps & AI automation`

[![Portfolio](https://img.shields.io/badge/robisolutionsit.com-0a0f15?style=for-the-badge&logo=googlechrome&logoColor=2ee6c1)](https://robisolutionsit.com/en)
[![Open to work](https://img.shields.io/badge/open_to_work-ff8a3d?style=for-the-badge)](https://robisolutionsit.com/en#contact)

</div>

---

### About

For over 25 years I've repaired electronics at component level, including in the **MSI, GIGABYTE and Acer**
service centres: laptops and graphics cards, from power circuits to VRAM diagnostics and performance testing.

I write mostly in **Python**, plus Bash and PowerShell. I build infrastructure from code: Proxmox installed from
an answer file, servers hardened with Ansible, monitoring on Prometheus and Grafana, CI pipelines run locally.
I build tools with AI, and I check the result myself before I call anything working.

### At the bench

- **Board-level repair** — laptop motherboards and GPUs, VRM power sections, micro-short localization on multilayer PCB
- **Rework** — BGA / SMD soldering, PCH / GPU / VRAM reballing, signal-trace reconstruction
- **Instrumentation** — oscilloscope, thermal camera, lab PSU, logic probe; boardview and schematic analysis
- **Firmware** — BIOS / KBC / SPI programming and modification

### Projects

Each name opens the project's card on my portfolio. 🔒 means the code is private for now; the card describes
what the tool does and how it was tested.

**Bench** · tools for diagnosing and testing hardware

| Project | What it does | Code |
|---|---|---|
| [bios-builder](https://robisolutionsit.com/en#tool-bios-builder) | Rebuilds a working, board-correct BIOS image from a damaged chip (Intel and AMD) and drives the SPI programmer | 🔒 |
| [disk-builder](https://robisolutionsit.com/en#tool-disk-builder) | Bootable GPU test media around the vendors' own factory diagnostics, NVIDIA GTX 10xx to RTX 50xx and AMD | 🔒 |
| [schema-vault](https://robisolutionsit.com/en#tool-schema-vault) | Local RAG over schematics, boardviews and datasheets; refuses instead of guessing and flags every unbacked name | 🔒 |
| [lap-diag-tool](https://robisolutionsit.com/en#tool-lap-diag-tool) | Laptop QA from scan to document: functional tests, a PASS/WARN/FAIL verdict and a printable service sheet | 🔒 |
| [winpe-builder](https://robisolutionsit.com/en#tool-winpe-builder) | WinPE built on Ubuntu with drivers picked by the target's real PCI IDs; network boot through iPXE | 🔒 |
| [iso-builder](https://robisolutionsit.com/en#tool-iso-builder) | Config-driven builder of bootable service media: a new tool is a JSON entry, not a code change | 🔒 |

**Infra** · servers, monitoring, CI

| Project | What it does | Code |
|---|---|---|
| [observability-bundle](https://robisolutionsit.com/en#tool-observability-bundle) | Prometheus, Grafana, Loki and Alertmanager in one compose up; failure to message in 2m18s–2m37s over five runs | 🔒 |
| [vps-ansible](https://robisolutionsit.com/en#tool-vps-ansible) | VPS hardening with Ansible, measured: Lynis 66 → 78, weak SSH algorithms 4 → 0, second run changes nothing | 🔒 |
| [cicd-showcase](https://robisolutionsit.com/en#tool-cicd-showcase) | CI across eleven of my repositories, run locally in act: 14 of 15 jobs pass, 1 act limit, 0 fail | 🔒 |
| [wazuh](https://robisolutionsit.com/en#tool-wazuh) | Wazuh on my Proxmox host: CIS Debian 13, 80 of 185 applicable checks passed (43%), not polished first | 🔒 |
| [rc-commander](https://robisolutionsit.com/en#tool-rc-commander) | The dual-pane file manager I work in daily, with git, Docker, systemd and Ansible menus; 234 tests | 🔒 |
| [proxmox](https://robisolutionsit.com/en#tool-proxmox) | Keyboard-free Proxmox install (3 min 12 s to first SSH), then one playbook builds the LXC and KVM guests | 🔒 |
| [autoinstall-builder](https://robisolutionsit.com/en#tool-autoinstall-builder) | One tool, three answer-file formats; Ubuntu, Fedora and Windows each installed unattended from real media | 🔒 |

### Stack

```text
Bare-metal / PCB     component-level diagnostics · BGA / SMD rework · VRM · VRAM
                     schematics / boardview · oscilloscope · thermal imaging
                     BIOS / EEPROM flashing · UEFI / Secure Boot / TPM
Linux / Proxmox      Debian / Ubuntu · Proxmox VE · QEMU / KVM · Tailscale
                     Python · Bash · PowerShell
Docker · monitoring  Docker · Coolify · Ansible · Git · GitHub Actions · n8n
                     Prometheus · Grafana · Loki · Wazuh
AI agents / LLM      Claude (Code and Cowork) · RAG · embeddings · MCP servers
                     Ollama · LM Studio
```

### Live

- [robisolutionsit.com](https://robisolutionsit.com/en) — this portfolio (Next.js), self-hosted on Coolify
- [links.robisolutionsit.com](https://links.robisolutionsit.com) — link-hub, a one-URL digital business card
- [qvertech.eu](https://qvertech.eu/) — company site bridging hardware sales with IT service and support
- [elektroniktech.de](https://elektroniktech.de/) — information platform and eBay sales support for the German market

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-0a0f15?style=for-the-badge&logo=googlechrome&logoColor=2ee6c1)](https://robisolutionsit.com/en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=fff)](https://www.linkedin.com/in/robert-senenko-it/)
[![dev.to](https://img.shields.io/badge/DEV.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=fff)](https://dev.to/robisolutionsit)
[![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=for-the-badge&logo=bluesky&logoColor=fff)](https://bsky.app/profile/robisolutionsit.com)

`contact:`

[![Telegram](https://img.shields.io/badge/Telegram-26A5E1?style=for-the-badge&logo=telegram&logoColor=fff)](https://t.me/RobiSolutionsIT)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=fff)](https://wa.me/48502316393)

`// presence initialized — waiting for handshake...`

</div>
