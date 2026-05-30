---
title: Hobbies
---

## Homelab

Self-hosted Kubernetes cluster at home. **Beelink SER5** with upgraded 64GB RAM, 2TB NVMe, and an external DAS with 2x4TB drives. **Proxmox** as hypervisor, running four VMs that form a **k3s** cluster: one master, three workers.

Full **GitOps** workflow. Manifests in Git, **ArgoCD** syncs automatically, all changes through pull requests.

### What's running

- **Media stack.** Jellyfin, Jellyseerr, Radarr, Sonarr, Prowlarr, qBittorrent.
- **Services.** Uptime Kuma, KitchenOwl, Calibre, and more.
- **Automation.** n8n as the workflow engine. Telegram bot interactions (torrent searches, recipe lookups), KFC order optimization, alerting integrations.
- **Networking.** Traefik, ExternalDNS with Cloudflare, Tailscale, Nubulus tunnel.
- **Monitoring.** Kube-Prometheus-Stack with Prometheus and Grafana.

## Home Assistant

**Home Assistant OS** running as a dedicated Proxmox VM. Automation beyond infrastructure, into everyday life.

- **Laundry notifications.** Alerts when the washing machine finishes based on power consumption.
- **Commute optimization.** Training a model to recommend when to leave home to avoid traffic.
- **Climate and energy.** Schedules based on presence, weather, and electricity pricing.

Every time I solve one thing, I find three more to automate.

## Monitoring & bots

Named after characters from [The Fairly OddParents](https://en.wikipedia.org/wiki/The_Fairly_OddParents), because every infrastructure needs its magic.

- **Wanda.** Deterministic alerting bot. Predefined alerts from Prometheus straight to Telegram.
- **Cosmo.** AI-powered SRE agent built on Claude. Monitors the cluster, diagnoses issues, runs read-only inspections, and creates tickets. Operates via Telegram, CLI, and [paseo.sh](https://github.com/JordiiBru/homelab) for autonomous agent sessions. Cosmo is multidisciplinary: beyond infrastructure, it handles fitness tracking, nutrition, and other areas, each with its own context window.

## Custom keyboards

I build mechanical keyboards from scratch. Picking every component, lubing switches and stabilizers, tuning the sound profile.

My current rotation:

- **Office.** Neo65, Gateron Oil Kings, PC plate, lubed Durock V2 stabilizers.
- **Gaming.** Tofu60 Redux, BM60 PCB, HMX Macchiato switches, PC plate, lubed Durock V2 stabilizers.
