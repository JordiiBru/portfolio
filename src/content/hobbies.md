---
title: Hobbies
---

## Homelab

I run a self-hosted Kubernetes cluster at home, built on a **Beelink SER5 Mini PC** (AMD Ryzen 7 5850U, 64GB DDR4, 2TB NVMe). The hypervisor is **Proxmox**, running four VMs that form a **k3s** cluster: one master and three workers.

Everything follows a strict **GitOps** workflow. Manifests live in a Git repo, **ArgoCD** syncs them automatically, and all changes go through pull requests. No manual kubectl apply, ever.

### What's running

- **Media stack.** Jellyfin, Jellyseerr, Radarr, Sonarr, Prowlarr, qBittorrent. A full self-hosted media server pinned to a dedicated worker node.
- **Services.** Uptime Kuma (status monitoring), KitchenOwl (groceries), Calibre (ebook library), and more.
- **Automation.** n8n as the workflow engine. Powers everything from Telegram bot interactions (torrent searches, recipe lookups) to KFC order optimization and homelab alerting integrations.
- **Networking.** Traefik as ingress controller, ExternalDNS with Cloudflare for automatic DNS, Tailscale for secure remote access, and a custom tunnel via Nubulus.
- **Monitoring.** Kube-Prometheus-Stack with Prometheus and Grafana dashboards for full cluster observability.
- **Storage.** Manual PersistentVolumes with HostPath, node-affinity-matched to pod placement. Simple and predictable.

## Home Assistant

My smart home setup runs on **Home Assistant OS** as a dedicated Proxmox VM. This is where my passion for automation goes beyond infrastructure and into everyday life.

Some things I have running or in the pipeline:

- **Laundry notifications.** Alerts when the washing machine finishes a cycle, based on power consumption patterns.
- **Commute optimization.** Training a model to recommend what time to leave home to avoid traffic on my way to work. A proper rabbithole.
- **Climate and energy.** Automated heating and cooling schedules based on presence, weather, and electricity pricing.

It's an endless project with infinite possibilities. Every time I solve one thing, I find three more to automate.

## Monitoring & bots

Both bots are named after characters from [The Fairly OddParents](https://en.wikipedia.org/wiki/The_Fairly_OddParents), because every infrastructure needs its magic.

- **Wanda.** A deterministic alerting bot. Handles predefined alerts from Prometheus and infrastructure events. Straight to Telegram, no surprises.
- **Cosmo.** My personal AI-powered SRE agent for the home cluster. Built on top of Claude, it monitors the infrastructure, diagnoses issues, runs read-only inspections, and creates tickets for follow-up work. It operates via Telegram and CLI sessions with full context of the cluster state. Cosmo is multidisciplinary: beyond infrastructure, it also helps me with fitness tracking, nutrition, and other areas, each with its own context window.

