---
layout: default
title: Technical Log (English)
nav_order: 3
---

# 📘 Technical Log (English Version)

## Title: I Turned My Android into a Complete Development Environment with Termux, Ubuntu, and VS Code

This log documents step-by-step how Richard Salvatierra transformed his Android phone into a professional Linux development environment using open-source tools, automated scripts, and GitHub Pages with the "Just the Docs" theme.

---

## 🛠️ Tools Used

- **Termux** for terminal access on Android
- **proot-distro** to install Ubuntu
- **code-server** (Visual Studio Code Web)
- **Python**, **Node.js**, **Git**, **Zsh**, **Oh My Zsh**
- **ngrok** for remote tunnels
- **GitHub Pages** + **Jekyll** with the "Just the Docs" theme

---

## 🧭 Project Milestones

### ✅ Initial Setup
- Termux and base packages installed using `pkg`
- Ubuntu 24.04 installed via `proot-distro install ubuntu`
- Accessed using `proot-distro login ubuntu`

### 🧱 Development Environment
- Ubuntu updated
- `code-server` installed and running
- Installed Node.js, Python, Git, and Zsh
- Installed Oh My Zsh for enhanced terminal UX

### 🔐 Remote Access & Tunneling
- Manually installed and authenticated ngrok
- Scripts created to start VS Code and open tunnel with ngrok
- Access verified via browser

### 📦 Backup & Restore System
- Full backup saved in `~/ubuntu_backup`
- Scripts created: `startvsc.sh`, `verifica_entorno.sh`, `restaurar_backup.sh`
- Restored and tested successfully after reinstallation

### 📄 GitHub Pages Integration
- Repository `leptium.github.io` configured
- Jekyll theme "Just the Docs" installed
- `index.md` published with links to logs

---

## 🧪 Final Diagnostic Summary

| Component             | Status   |
|-----------------------|----------|
| Ubuntu                | ✅ Successfully installed |
| VS Code (code-server) | ✅ Running on localhost |
| Zsh + Oh My Zsh       | ✅ Active and customized |
| ngrok                 | ✅ Authenticated and functional |
| Management Scripts    | ✅ startvsc.sh, verifica_entorno.sh, restaurar_backup.sh |
| GitHub Pages          | ✅ Online with Just the Docs |

---

## ✍️ Next Steps

- [ ] Add more technical documentation for each section
- [ ] Include screenshots of the functional environment
- [ ] Translate new sections into Spanish for `bitacora-es.md`
- [ ] Publish weekly updates and improvements

---

🚀 *"Turning a limitation into an opportunity is the art of the self-taught engineer."*  
— Richard Salvatierra
