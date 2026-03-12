# AuditReady — ISO 27001:2022 Audit Preparation Tool

![ISO 27001:2022](https://img.shields.io/badge/ISO%2027001-2022-2e6da4?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-0d7377?style=flat-square)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-6d28d9?style=flat-square)
![No dependencies](https://img.shields.io/badge/dependencies-none-success?style=flat-square)

A fully offline, single-file browser tool to help organisations track and prepare evidence for an **ISO 27001:2022** certification audit. No backend, no login, no data ever leaves your browser.

---

## 🖼️ Overview

AuditReady walks you through all **93 controls** across the four ISO 27001:2022 Annex A themes and helps you record what evidence you have collected for each one. A live dashboard tracks your overall readiness score in real time.

---

## ✨ Features

- **Full ISO 27001:2022 control coverage** — all 93 Annex A controls across Organisational, People, Physical and Technological themes
- **Evidence checklist per control** — each control has pre-defined evidence items with practical examples (e.g. specific tools, document names, screenshots)
- **Live readiness dashboard** — circular score ring + per-theme progress bars that update as you tick off evidence
- **Cross-cutting overlap tracker** — identifies 24 common evidence types (MFA, SIEM, Patch Management, Encryption, etc.) that satisfy multiple controls at once, helping you spot efficiency gains
- **Search & filter** — full-text search across all controls and evidence items; filter by theme (Organisational / People / Physical / Technological) or by completion status
- **Notes per control** — free-text notes field on every control for auditor comments, gaps, or owner names
- **Persistent local storage** — your progress is automatically saved to your browser and survives page reloads
- **Export to JSON** — download a full snapshot of your audit progress for backup or sharing
- **Import from JSON** — restore a previously exported snapshot
- **Reset** — clear all progress and start fresh with a single click
- **Zero dependencies** — pure HTML, CSS and vanilla JavaScript; works entirely offline

---

## 🚀 Getting Started

### Option 1 — Run locally (simplest)

1. Download `auditready.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. Start ticking off evidence — progress is saved automatically

### Option 2 — Host on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set the source branch to `main` and folder to `/root`
4. Your tool will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/auditready.html
   ```

> **Tip:** Rename the file to `index.html` to get a cleaner URL without the filename.

---

## 📁 File Structure

```
.
└── auditready.html   # The entire tool — one self-contained file
```

Everything (HTML, CSS, JavaScript, control data) lives in a single file. No build step, no npm, no frameworks.

---

## 🗂️ ISO 27001:2022 Themes Covered

| Theme | Controls | Examples |
|---|---|---|
| **Organisational** | 5.1 – 5.37 | Policies, Risk Management, Supplier Security, Incident Response |
| **People** | 6.1 – 6.8 | Screening, Training, Disciplinary Process, Remote Working |
| **Physical** | 7.1 – 7.14 | Physical Access, Clear Desk, Equipment Disposal, CCTV |
| **Technological** | 8.1 – 8.34 | Endpoint Protection, Encryption, SIEM, Vulnerability Management, SDLC |

---

## 🔁 Cross-Cutting Evidence Tracker

The **Overlaps** tab highlights 24 recurring evidence types that appear across multiple controls simultaneously, such as:

- Multi-Factor Authentication (MFA)
- Centralised Logging & SIEM
- Patch & Vulnerability Management
- Encryption (at rest & in transit)
- Penetration Testing & Security Audits
- Backup, Recovery & Redundancy
- Supplier & Third-Party Security
- GDPR & Data Protection
- …and more

This helps you avoid duplicating effort and quickly see which investments in tooling give you the widest control coverage.

---

## 💾 Data & Privacy

All data is stored exclusively in your **browser's local storage**. Nothing is transmitted to any server. This makes AuditReady safe to use with sensitive audit information.

To back up your progress, use the **Export JSON** button. To restore it on another machine or browser, use **Import JSON**.

---

## 🛠️ Browser Support

Any modern browser with ES6+ support:

- Chrome / Edge 88+
- Firefox 85+
- Safari 14+

---

## 📄 License

MIT — free to use, modify and distribute.

---

## 🤝 Contributing

Contributions are welcome. If a control mapping is incorrect, an evidence example is outdated, or you'd like to add a new feature, please open an issue or submit a pull request.

---

## ⚠️ Disclaimer

This tool is designed to assist with audit preparation. It does not guarantee ISO 27001 certification and should be used alongside advice from a qualified ISO 27001 Lead Auditor or consultant.
