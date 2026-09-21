<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1a1b26&fontColor=7aa2f7&height=200&section=header&text=Alexandre&fontSize=52&fontAlignY=38&desc=Homelab%20%C2%B7%20IA%20locale%20%C2%B7%20Cybers%C3%A9curit%C3%A9&descSize=17&descAlignY=60" alt="Alexandre" />

Passionné d'infrastructure, d'open source et d'IA, je construis et documente mon homelab sur une **architecture Zero Trust**, et je développe mon propre assistant vocal : **Jarvis**.
Ici : mes configs, mes essais et ce que j'apprends en route.

📍 Normandie &nbsp;·&nbsp; 🎓  Bac+5 *Manager en Infrastructures et Cybersécurité des SI*

[![GitHub](https://img.shields.io/badge/GitHub-x3noux11-1a1b26?style=for-the-badge&logo=github&logoColor=7aa2f7)](https://github.com/x3noux11)

</div>

## Jarvis, mon assistant vocal

Un assistant vocal personnel intégré à ma domotique, que je fais évoluer en continu.

- **Domotique :** intégration avec Home Assistant
- **Interaction :** détection de wake word, mémoire persistante (SQLite)
- **Modèles :** passerelle **LiteLLM** qui route vers plusieurs fournisseurs (Groq, Cerebras, Mistral, DashScope), ce qui permet de comparer et de changer de modèle sans toucher au reste

## Mon homelab

Mon GitHub sert à documenter et versionner les briques de mon infrastructure personnelle.

**Réseau & sécurité**
- **Pare-feu & routage :** OPNsense, Kea DHCP, commutation MikroTik CRS, segmentation en VLAN (LAN en place, IoT en cours)
- **Exposition sécurisée :** Cloudflare Tunnel, Traefik en reverse proxy, accès distant via NetBird / Headscale
- **Identité & protection :** Authentik (SSO, MFA, Passkeys FIDO2/WebAuthn), CrowdSec, PKI interne (step-ca), DNS filtrant (AdGuard Home) avec split-horizon

**Virtualisation & stockage**
- **Hyperviseur :** Proxmox VE (VM Debian, conteneurs LXC), GPU passthrough (RX 580) pour Jellyfin
- **Sauvegarde :** Proxmox Backup Server sur ZFS RAIDZ1 (en cours de mise en place)
- **Observabilité :** Prometheus, Grafana, Loki, Alloy, Uptime Kuma

**Services auto-hébergés**
- Nextcloud, Immich, Forgejo, Home Assistant, Vaultwarden, Jellyfin + suite Arr, n8n, FreshRSS, SearXNG, LanCache

**IA locale**
- Ollama (dont Qwen-VL) et LiteLLM, exploration de k3s / Kubernetes sur ARM

## Boîte à outils

<div align="center">

**Réseau & sécurité**<br>
![OPNsense](https://img.shields.io/badge/OPNsense-1a1b26?style=flat-square&logo=opnsense&logoColor=7aa2f7)
![Cloudflare](https://img.shields.io/badge/Cloudflare-1a1b26?style=flat-square&logo=cloudflare&logoColor=7aa2f7)
![CrowdSec](https://img.shields.io/badge/CrowdSec-1a1b26?style=flat-square&logo=crowdsec&logoColor=7aa2f7)
![Authentik](https://img.shields.io/badge/Authentik-1a1b26?style=flat-square&logo=authentik&logoColor=7aa2f7)
![Traefik](https://img.shields.io/badge/Traefik-1a1b26?style=flat-square&logo=traefikproxy&logoColor=7aa2f7)

**Systèmes & virtualisation**<br>
![Proxmox](https://img.shields.io/badge/Proxmox_VE-1a1b26?style=flat-square&logo=proxmox&logoColor=7aa2f7)
![Docker](https://img.shields.io/badge/Docker-1a1b26?style=flat-square&logo=docker&logoColor=7aa2f7)
![Debian](https://img.shields.io/badge/Debian-1a1b26?style=flat-square&logo=debian&logoColor=7aa2f7)
![Linux](https://img.shields.io/badge/Linux-1a1b26?style=flat-square&logo=linux&logoColor=7aa2f7)
![Home Assistant](https://img.shields.io/badge/Home_Assistant-1a1b26?style=flat-square&logo=homeassistant&logoColor=7aa2f7)

**IA, langages & outils**<br>
![Python](https://img.shields.io/badge/Python-1a1b26?style=flat-square&logo=python&logoColor=7aa2f7)
![Bash](https://img.shields.io/badge/Bash-1a1b26?style=flat-square&logo=gnubash&logoColor=7aa2f7)
![SQLite](https://img.shields.io/badge/SQLite-1a1b26?style=flat-square&logo=sqlite&logoColor=7aa2f7)
![Ollama](https://img.shields.io/badge/Ollama-1a1b26?style=flat-square&logo=ollama&logoColor=7aa2f7)
![n8n](https://img.shields.io/badge/n8n-1a1b26?style=flat-square&logo=n8n&logoColor=7aa2f7)
![Markdown](https://img.shields.io/badge/Markdown-1a1b26?style=flat-square&logo=markdown&logoColor=7aa2f7)

</div>

## Statistiques GitHub

<div align="center">

![Followers](https://img.shields.io/github/followers/x3noux11?style=flat-square&color=1a1b26&labelColor=1a1b26&logo=github&logoColor=7aa2f7)
![Stars](https://img.shields.io/github/stars/x3noux11?style=flat-square&color=1a1b26&labelColor=1a1b26&logo=github&logoColor=7aa2f7)

</div>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=1a1b26&height=100&section=footer" width="100%" alt="" />
