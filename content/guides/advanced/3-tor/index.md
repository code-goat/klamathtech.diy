---
title: "2.03 Tor"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 3
draft: false
description: "Tor routes your traffic through multiple servers so no single point can connect who you are to what you're doing. Here's how it works and when to use it."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 3
---

# Tor — Anonymity Through the Network

A VPN hides your traffic from your ISP but hands it to a VPN provider instead. **Tor removes that tradeoff entirely.**

Tor routes your traffic through three volunteer-run servers (called relays), encrypting it in layers at each hop — like an onion. Each relay only knows the step before it and the step after. No single server can see both who you are and where you're going. Not even the Tor Project itself can see your traffic.

---

## How It Works

When you use Tor:

1. Your device connects to a **guard node** — it knows your IP, but not your destination
2. The guard passes your encrypted traffic to a **middle node** — it knows neither your IP nor your destination
3. The middle passes it to an **exit node** — it knows the destination, but not your IP

The result: the site you visit sees the exit node's IP. Your ISP sees that you are using Tor, but not what you are doing. No relay has the full picture.

---

## The Tor Browser

The easiest way to use Tor is the **Tor Browser** — a modified version of Firefox that routes all traffic through Tor and includes hardened privacy settings by default.

**Get it:** [torproject.org](https://www.torproject.org)

Available for Windows, Mac, Linux, and Android.

---

## Trade-offs

**Slower:** Traffic bouncing through three relays adds latency. Tor is not suitable for video streaming or activities where speed matters.

**Some sites block Tor:** Exit nodes are publicly listed, and some services block them. You can use **bridges** (unlisted relays) to get around this.

**Anonymity requires discipline:** Tor protects your network identity — it cannot protect you if you log into personal accounts, download files and open them outside Tor, or enable JavaScript on hostile sites. The Tor Browser sets safe defaults, but understanding the limits matters.

---

## What Tor Is Good For

- Sensitive research (health, legal, political) where you don't want your browsing tied to your identity
- Accessing sites blocked in your country or on your network
- Journalists and activists communicating with sources
- Accessing .onion sites (services that exist only inside the Tor network, with no exit node — fully end-to-end anonymous)

## What Tor Is Not Good For

- Logging into personal Google, Facebook, or other accounts (that identifies you regardless)
- High-bandwidth activities like video calls or large downloads
- Protection against someone who has compromised both your device and the exit node simultaneously (rare but theoretically possible)

---

## Tor and I2P

Tor is designed primarily for **accessing the regular internet anonymously**. I2P (covered in the next guide) is designed for **communication within a self-contained network**. They solve related but different problems. Many privacy-conscious people use both for different purposes.

---

> Next up: **[2.04 I2P →](/guides/advanced/4-i2p/)**

---

> Questions? [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
