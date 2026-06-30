---
title: "2.06 Secure Operating Systems"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 6
draft: false
description: "Your OS is the foundation everything else runs on. Linux, Tails, and Qubes OS — what they are and when each makes sense."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 6
---

# Secure Operating Systems

Every app, every browser, every file runs on top of your operating system. If the OS is compromised — or is itself doing surveillance — everything above it is undermined.

**Windows** and **macOS** both collect telemetry: usage data sent back to Microsoft and Apple by default. Both are closed-source, meaning their behavior cannot be fully independently audited. Both comply with law enforcement requests.

The alternative is Linux and its specialized derivatives.

---

## Linux — The Foundation

**Linux** is a family of free, open-source operating systems. Unlike Windows and macOS, the source code is publicly available and auditable. Linux does not have a business model that depends on collecting your data.

Common, accessible starting points:
- **Linux Mint** — closest to a Windows-like experience, recommended for first-time Linux users
- **Ubuntu** — widely used, large support community
- **Fedora** — slightly more cutting-edge, strong security defaults

Linux runs well on most computers from the past decade — including hardware that Windows 11 refuses to support. Our [UpRiv\|Upcycle](/projects/upcycle/) program installs Linux on refurbished computers for exactly this reason. If you have received a computer through our program, it is already running Linux.

---

## Tails — Leave No Trace

**Tails** is a Linux-based operating system designed for a specific purpose: **leave no trace on the computer you use it on.**

Tails runs from a USB drive. When you plug it in and boot from it, it loads entirely into RAM. When you shut it down, it leaves nothing behind on the host computer — no files, no browsing history, no account information. It routes all traffic through Tor automatically.

Tails is designed for:
- Journalists and sources who need to communicate without leaving traces
- Whistleblowers
- People using a shared, untrusted, or potentially compromised computer
- High-surveillance environments where device seizure is a real risk

**Get Tails:** [tails.boum.org](https://tails.boum.org) — includes a detailed installation guide

The installation process creates a "persistent storage" option encrypted with a passphrase — allowing you to save specific files and settings across sessions, while everything else still disappears on shutdown.

---

## Qubes OS — Isolation Through Compartmentalization

**Qubes OS** takes a different approach. Rather than running everything in a single operating environment, Qubes runs **different activities in isolated virtual machines** (called qubes) that cannot interact with each other.

For example:
- One qube for browsing untrusted sites
- One qube for banking
- One qube for sensitive work documents
- One qube for communication

If malware infects your browsing qube through a malicious website, it is trapped there. It cannot access your documents, your banking, or your communications. The compromise is contained.

Qubes is considered by many security researchers to be the most secure desktop OS available. Edward Snowden uses it. It is also demanding:
- Requires a powerful computer (16GB+ RAM recommended)
- Significant learning curve
- Not suitable as a first Linux experience

**Get Qubes OS:** [qubes-os.org](https://www.qubes-os.org)

---

## Which Should You Use?

| Situation | Recommendation |
|---|---|
| Everyday privacy-conscious use | Linux Mint or Ubuntu |
| Received a Collective computer | Already running Linux — you're set |
| Need to work on a potentially compromised machine | Tails from USB |
| High-risk situation, sophisticated adversary | Qubes OS |
| Need to leave absolutely no trace | Tails |

---

## Further Resources

- **[Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org)** — guides tailored to specific threat models
- **[Security in a Box](https://securityinabox.org)** — tools and tactics for human rights defenders  
- **[Privacy Guides](https://www.privacyguides.org)** — maintained, community-reviewed tool recommendations

---

> Next up: **[2.07 Mobile Devices →](/guides/advanced/7-mobile/)**

---

> Questions? [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
