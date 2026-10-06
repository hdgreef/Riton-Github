# Riton MindMap

<p align=center><img src=https://github.com/hdgreef/Riton-Github/blob/main/docs/images/markmap.png alt='Riton's Mind' width='30%'></p>

Run it here : [Markmap](https://markmap.js.org/repl)

```
---
title: Riton Mind
markmap:
  colorFreezeLevel: 2
  maxWidth: 300
  initialExpandLevel: all

  embedAssets: true
  activeNode:
    placement: center
---

## ![3D Print](https://github.com/VoronDesign/Voron-Stealthburner/raw/main/Images/Voron_Stealthburner.JPG)
### **RitonVoron1**
#### [Github Voron 1](https://github.com/hdgreef/RitonVoron1)
#### **TO DO** 
- [ ] StealthChanger
- [ ] StealthMax
- [ ] UKAM
#### **DONE**
- [x] ~~TopHat~~


### **RitonVoron2**
#### [Github Voron 2](https://github.com/hdgreef/RitonVoron2)
#### **TO DO** 
- [ ] UKAM
#### **DONE**
- [x] Back to Klippain 

### **RitonVZ**
#### **TO DO**
- [ ] Klippain
#### **DONE**

### **To Print**
#### **TO DO**
1. [ ] Audrey - Hance
2. [ ] Ninon - Support Lampe


## ![CNC](https://docs.v1e.com/img/lr3/LR3_Fancy%20%286%29.jpg)
### **LR3**
#### **TO DO**
- [ ] Define Table size
- [ ] Cut Alu profile to XXmm
- [ ] Put GT2 Belt 10mm
#### **DONE**
- [x] Order V1E µP


## ![Linux](https://tse2.mm.bing.net/th/id/OIP.klBVUD2x6Nv-WstmOTzz6AHaEK?r=0&pid=Api)
### **AcerBuntu**
#### **TO DO**
#####
- [x] [Cockpit](https://cockpit-project.org/running.html) (Gestion des conteneurs, éventuellement Portainer)
  - [x] [MonCockpit](https://localhost:9090)
  - [x] Cockpit App (cockpit-podman, cockpit-storage, cockpit-networkmanager, cockpit-machines (VM), cockpit-pcp (CPU performance))
  - [ ] Cockpit App non-installées (cockpit-files, cockpit-tailscale)
- [x] Podman  (Docker alt)
  - [x] [Flatpak & FlatHub install](https://flathub.org/fr/setup/Ubuntu)
  - [x] Podman Desktop + Compose (via FlatHub)
  - [x] Podman Containers (via cockpit-podman)
- [x] UFW (ou iptables (complexe)) (Firewall pour bloquer les ports inutiles)
- [x] Tailscale (ou WireGuard (complexe)) (Réseau VPN)
- [ ] NPM (Nginx Proxy Manager) ou Traefik + Let's Encrypt via Certbot (https)
- [ ] Netdata (Monitoring data)
- [ ] Fail2Ban 
- [ ] Servarr
- [ ] Plex/Jellyfin
- [ ] Pi-Hole
- [ ] Syncthing
- [ ] VaultWarden (Gestion MDP, BitWarden alt)
- [ ] rsync ou BorgBackup (sauvegarde)
#### **Optional**
- [ ] HomeAssistant
- [ ] NextCloud (Drive alt)
- [ ] AppFlowy (Notion alt)
- [ ] Taiga (Gestion Projet Agile)
- [ ] Node-RED (Automatisation domotique)
#### **DONE**


### **RitonPi**
#### **ToDo**
- [ ] OpenMediaVault (NAS)
#### **Done**
- [x] RpiOS 64bits
- [x] Install git, python3,-pip,-venv, Nodejs, npm, curl, wget

## ![SLA](https://eu.elegoo.com/cdn/shop/files/saturn-4-ultra-16k-right-side-open.jpg?v=1743676935)
#### **Plan**
#### **TO DO**

      
## ![Piano](https://tse2.mm.bing.net/th/id/OIP.OvYZjc7T8rhp9wezDZmMLAHaE7?r=0&pid=Api)
#### **TO DO**
#### **DONE**
```

--- 
```
Home Lab Network
├── 🖥️ Gateway: RPi 5 8Go
│   ├── 🔒 Sécurité & Gestion
│   │   ├── UFW Firewall
│   │   ├── Fail2Ban
│   │   ├── SSH Clés
│   │   ├── Cockpit
│   │   └── Tailscale
│   ├── 🌐 Services Core
│   │   ├── OMV NAS
│   │   ├── Pi-hole DNS
│   │   ├── Vaultwarden
│   │   └── Nginx Proxy Manager
│   └── 🎬 Services Médias
│       ├── Plex / Jellyfin
│       └── Servarr Stack
├── 🔌 Réseau Local: Switch
│   ├── PC Linux: Acer Aspire S5 Ubuntu
│   ├── PC Windows: Lenovo Windows 11
│   ├── Voron 1: RPi4 + Octopus
│   ├── Voron 2: RPi4 + Manta 8P
│   └── VzBot: RPi3b + SKR v1.3
├── 📶 Réseau Sans Fil / WAN
│   ├── Fairphone 4
│   └── Bambulab P1S AMS
└── 🤔 RPi 3b: À définir

``` 
