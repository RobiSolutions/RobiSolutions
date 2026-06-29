<!-- Profile README → repo: RobiSolutions/README.md  |  WERSJA DOCELOWA -->

<div align="center">

[![HARDWARE](https://img.shields.io/badge/HARDWARE-BGA·SMD·VRM-00d9ff?style=for-the-badge&logo=hackthebox&logoColor=000)](#)
[![DEVOPS](https://img.shields.io/badge/DEVOPS-PROXMOX·DOCKER·COOLIFY-ffb000?style=for-the-badge&logo=linux&logoColor=000)](#)
[![AI](https://img.shields.io/badge/AI-N8N·RAG·LLM-00d9ff?style=for-the-badge&logo=openai&logoColor=000)](#)

</div>

```
root@robisolutionsit:~$ whoami
```

# Robert Senenko — Bridging Silicon & Software

> **20+ years** of board-level electronics repair and micro-diagnostics — trained and certified
> across **GIGABYTE, MSI and Acer (EMEA)** authorized service centers.
> Now applying the same fault-isolation discipline from the circuit board up to the cluster:
> DevOps, Linux infrastructure and AI automation.

<div align="center">

`Component-level repair` ⟶ `Linux & virtualization` ⟶ `DevOps & AI automation`

</div>

---

### `> INFRASTRUCTURE & VIRTUALIZATION`

- **Proxmox VE** — VM/LXC clusters, isolated test labs, snapshot/incremental backup policies
- **Self-hosted PaaS** — Coolify on a Linux VPS as a control plane for Dockerized production apps (incl. n8n)
- **FOG Project** — network-based OS imaging, cloning and mass workstation deployment
- **Networking** — reverse proxy, DNS, VPN, firewall; Zabbix infrastructure monitoring

### `> DIAGNOSTICS [HARDWARE ↔ SOFTWARE]`

- **Board-level repair** — laptop motherboards & GPUs, VRM power sections, micro-short localization on multilayer PCB
- **Rework** — BGA / THT / SMT soldering, PCH/GPU/VRAM reballing, signal-trace reconstruction
- **Instrumentation** — oscilloscope, thermal camera, lab PSU, logic probe; boardview & schematic analysis
- **Firmware** — BIOS / KBC / SPI programming and modification

### `> AI & AUTOMATION   // focus`

- **n8n** — autonomous, event-driven workflows integrating internal systems and social channels
- **RAG & local LLM** — private knowledge bases over technical docs and boardviews; self-hosted Ollama / LM Studio
- **AI agents** — assistants for data and test-log analysis; human-in-the-loop content pipeline

### `> FULL-STACK`

- **Next.js** apps with Tailwind, shadcn/ui, Zod — deployed on Vercel (GitOps)
- **Data** — PostgreSQL, Prisma, Supabase
- **Integrations** — Stripe & PayPal payment systems

---

### `> CORE STACK`

<!-- Infrastructure & virtualization -->
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=000)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=fff)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fff)
![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=fff)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=for-the-badge&logo=pfsense&logoColor=fff)
<br>
<!-- Monitoring · security · storage -->
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logo=zabbix&logoColor=fff)
![Wazuh](https://img.shields.io/badge/Wazuh-0050C8?style=for-the-badge&logo=wazuh&logoColor=fff)
![QNAP](https://img.shields.io/badge/QNAP-0C4DA2?style=for-the-badge&logo=qnap&logoColor=fff)
<br>
<!-- Automation · web · data -->
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=fff)
![Coolify](https://img.shields.io/badge/Coolify-080E2C?style=for-the-badge&logo=coolify&logoColor=fff)
![Next.js](https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=fff)
![Vercel](https://img.shields.io/badge/Vercel-000?style=for-the-badge&logo=vercel&logoColor=fff)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=000)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=fff)
<br>
<!-- AI -->
![Claude](https://img.shields.io/badge/Claude-code·cowork·design-D97757?style=for-the-badge&logo=claude&logoColor=fff)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=fff)
![LM Studio](https://img.shields.io/badge/LM_Studio-2A2A2A?style=for-the-badge&logo=lmstudio&logoColor=fff)
![AnythingLLM](https://img.shields.io/badge/AnythingLLM-1A1A1A?style=for-the-badge&logoColor=fff)

---

### `> PROJECTS`

**⚙️ Setup & Bootstrap**
- [`ubuntu-bench-bootstrap`](https://github.com/RobiSolutions/ubuntu-bench-bootstrap) — bash provisioning for a fresh Ubuntu dev/bench workstation (VS Code, dual-GitHub, KVM/QEMU, Docker)

**🧰 Diagnostic Toolkits**
- [`diag-tool`](https://github.com/RobiSolutions/diag-tool) — branded multi-boot USB toolkit (Ventoy, custom GRUB2 theme, 8-category ISO taxonomy)
- [`win-diag-toolkit`](https://github.com/RobiSolutions/win-diag-toolkit) — modular PowerShell diagnostics (Diag / Provision / Specialist / Bench)

**🤖 AI & Automation** &nbsp;`// flagship`
- [`n8n-content-pipeline`](https://github.com/RobiSolutions/n8n-content-pipeline) — multi-agent content system with Discord approval loop
- [`local-ai-kb`](https://github.com/RobiSolutions/local-ai-kb) — self-hosted RAG knowledge base (Ollama + AnythingLLM)

**🔒 Infra & Security**
- [`nextjs-security-headers`](https://github.com/RobiSolutions/nextjs-security-headers) — production CSP + security headers template (Observatory A grade)
- [`homelab-proxmox`](https://github.com/RobiSolutions/homelab-proxmox) — homelab architecture: pfSense, Docker, monitoring, IaC notes

---

### `> LIVE`

- [robisolutionsit.com](https://robisolutionsit.com) — portfolio & technical hub (Next.js)
- [qvertech.eu](https://qvertech.eu/) — deployed project

---

<div align="center">

### `> CONNECT`

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-111111?style=for-the-badge&logo=googlechrome&logoColor=00d9ff)](https://robisolutionsit.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=fff)](https://www.linkedin.com/in/robert-senenko-it/)
<!-- dev.to: podmień handle, gdy potwierdzisz konto -->
[![dev.to](https://img.shields.io/badge/DEV.TO-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=fff)](https://dev.to/)
<!-- Facebook: podmień na realny URL Page i podlinkuj dopiero, gdy Page ma już treść -->
[![Facebook](https://img.shields.io/badge/FACEBOOK-1877F2?style=for-the-badge&logo=facebook&logoColor=fff)](https://facebook.com/)

`contact:`

[![Telegram](https://img.shields.io/badge/Telegram-26A5E1?style=for-the-badge&logo=telegram&logoColor=fff)](https://t.me/RobiSolutionsIT)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=fff)](https://wa.me/48502316393)

`// presence initialized — waiting for handshake...`

</div>
