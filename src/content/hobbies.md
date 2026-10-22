---
title: Hobbies
---

## Homelab

Self-hosted Kubernetes cluster at home. **Beelink SER5** with upgraded 64GB RAM, 2TB NVMe, and an external DAS with 2x4TB drives. **Proxmox** as hypervisor, running four VMs that form a **k3s** cluster: one master, three workers.

Full **GitOps** workflow. Manifests in Git, **ArgoCD** syncs automatically, all changes through pull requests, and **Renovate** keeps images and charts up to date.

### What's running

- **Media stack.** Jellyfin, Jellyseerr, Radarr, Sonarr, Prowlarr, qBittorrent.
- **Services.** KitchenOwl, Calibre, El Meu Armari, Gasolineras Tracker, and more.
- **Automation.** n8n as the workflow engine. Telegram bot interactions (torrent searches, recipe lookups), alerting integrations.
- **Networking.** Traefik, ExternalDNS with Cloudflare, Tailscale, [Nubulus tunnel](https://docs.nubulusnetwork.es/services/tunnels/home/).
- **Monitoring.** Kube-Prometheus-Stack with Prometheus and Grafana. **Gatus** checks every endpoint and alerts to Telegram.

---

## Home Assistant

**Home Assistant OS** running as a dedicated Proxmox VM. Automation beyond infrastructure, into everyday life.

- **Laundry notifications.** Alerts when the washing machine finishes based on power consumption.
- **Commute optimization.** Training a model to recommend when to leave home to avoid traffic.

And more! Every time I solve one thing, I find three more to automate.

---

## Monitoring & bots

Named after characters from [The Fairly OddParents](https://en.wikipedia.org/wiki/The_Fairly_OddParents), because every infrastructure needs its magic.

- **Wanda.** Deterministic alerting bot. Predefined alerts from Prometheus straight to Telegram.
- **Cosmo.** AI-powered agent built on Claude and running on [Hermes](https://hermes-agent.nousresearch.com/). Monitors the cluster, diagnoses issues, runs read-only inspections, and opens issues and pull requests. Operates via Telegram and CLI. Cosmo is multidisciplinary: beyond infrastructure, it handles fitness tracking, nutrition, and other areas, each with its own context window.

---

## Custom keyboards

I build mechanical keyboards from scratch. Picking every component, lubing switches and stabilizers, tuning the sound profile.

My current rotation:

- **Office.** Neo65, Gateron Oil Kings, PC plate, lubed Durock V2 stabilizers.
- **Gaming.** Tofu60 Redux, BM60 PCB, HMX Macchiato switches, PC plate, lubed Durock V2 stabilizers.
