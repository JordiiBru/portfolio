---
title: Projects
---

## Homelab

A self-hosted k3s Kubernetes cluster running on Proxmox, with a full GitOps workflow powered by ArgoCD. Monitoring with Prometheus and Grafana, media stack with Jellyfin, workflow automation with n8n, and more.

[More details in Hobbies](/hobbies/)

## El Meu Armari (My Closet)

As a fan of styling and color theory, I've always loved Sanzo Wada's [_Dictionary of Color Combinations_](https://sanzo-wada.dmbk.io/). So I built a wardrobe manager around it: catalogue your clothes, get outfit suggestions matched against the book's 348 palettes, and plan them on a calendar. Built with **Next.js**, **Prisma**, and **TypeScript**.

Public repo, open to contributions.

[View on GitHub](https://github.com/JordiiBru/elmeu-armari)

## KFC Optimizer

Started as a set of **n8n workflows** that scraped KFC promotions, parsed combo pricing, and calculated the cheapest order for what a group wants to eat. It now runs as a **Next.js** app self-hosted on my homelab, with a scheduled scraper, a SQLite catalog, and an optimizer that only recommends products it can classify. One of those absurd side projects that actually saves money.

[Try it out.](https://kfc.jordibru.cloud)

## Gasolineras Tracker

Price history for every petrol station in Spain, with each one compared against its town's average. It runs on the Spanish Ministry's open data: a scheduled job precomputes static JSON files and nginx serves them, so there is no backend at request time. Built with **Python**, **SQLite**, and **nginx**, self-hosted on the homelab.

[View on GitHub](https://github.com/JordiiBru/gasolineras-tracker)

---

## Dotfiles

My personal development environment configuration: shell, editor, tools, and system setup. Public but always evolving.

[View on GitHub](https://github.com/JordiiBru/dotfiles)

## Bachelor's Thesis

<span class="date">2024 · UPC-FIB · 9.3/10</span>

**From Repository to Deployment: Optimizing IaC Development and Management**

Examines Infrastructure as Code and its impact on platform and development teams. Covers theoretical foundations of IaC and its relationship with DevOps, followed by two technical tracks: building a GitOps-based auto-deployment repository, and implementing IaC at Mango to bring infrastructure closer to developers. Includes a CI/CD tool to evaluate merge request costs before applying real changes.

[Source](https://upcommons.upc.edu/entities/publication/9e53b67f-8097-485e-9143-bab48c0c7a42)

---

## Side projects & tooling

I like building small CLI tools and utilities, mostly in **Go**. Things like local development helpers, automation scripts, and anything that scratches an itch. Nothing too serious, just the kind of tooling that makes my day-to-day smoother.

[More projects on GitHub](https://github.com/JordiiBru?tab=repositories)

---

## This site

Built with **Astro**, deployed on my own [homelab](/hobbies/).

[View on GitHub](https://github.com/JordiiBru/portfolio)
