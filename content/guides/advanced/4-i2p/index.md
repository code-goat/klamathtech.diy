---
title: "2.04 I2P"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 4
draft: false
description: "I2P is a self-contained anonymity network built for peer-to-peer communication and community-run services — a different tool than Tor for different purposes."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 4
---

# I2P — A Self-Contained Anonymity Network

**I2P** (the Invisible Internet Project) is an anonymity network with a different design philosophy than Tor. Where Tor is built primarily to let you access the regular internet anonymously, I2P is a **self-contained network** — a "darknet" where services and communication live entirely inside the network itself.

---

## How I2P Differs From Tor

| | Tor | I2P |
|---|---|---|
| Primary purpose | Access the regular internet anonymously | Run services and communicate within I2P |
| Routing method | Onion routing (layered encryption, 3 hops) | Garlic routing (bundles multiple messages together) |
| Exit to regular internet | Yes (via exit nodes) | Limited (via "outproxies") |
| Hidden services | .onion sites | Eepsites (.i2p addresses) |
| Contributes to network | Optional | Default — your node routes others' traffic |
| Setup complexity | Easy (Tor Browser) | Moderate |

The key difference: **I2P routes other people's traffic through your node by default**, which strengthens the network for everyone. You are not just a consumer of the anonymity network — you are part of it. This is more aligned with the Collective's values around community-owned infrastructure.

---

## What I2P Is Good For

**Peer-to-peer file sharing** — I2P includes **i2psnark**, a built-in BitTorrent client. Transfers happen entirely inside the network, with no IP addresses exposed to external trackers.

**Hidden services (eepsites)** — Websites and services that exist only inside I2P, accessible only to I2P users. These can be run by communities, collectives, or individuals without exposing a server's location or IP.

**Encrypted internal communication** — I2P has built-in encrypted email (I2P-Bote) and messaging tools designed for network-internal use.

**Community infrastructure** — Because anyone can run services inside I2P, it's a natural fit for collectively-run infrastructure that doesn't depend on any company's servers.

---

## What I2P Is Not Good For

- Browsing the regular internet anonymously (use Tor for that)
- Quick setup — I2P takes more configuration than Tor Browser
- Accessing mainstream websites (most aren't available inside I2P)

---

## Getting Started

**Get I2P:** [geti2p.net](https://geti2p.net)

I2P runs as a background application on your computer and provides a local web interface (usually at `127.0.0.1:7657`) for configuration and using its services.

After installation:
1. Let the router run for a few minutes to integrate into the network and find peers
2. Explore the built-in applications via the router console
3. For browsing internal I2P sites, configure your browser to use I2P's built-in HTTP proxy (port 4444 by default)

The I2P documentation at geti2p.net is thorough and worth reading before diving in.

---

## I2P and the Collective

I2P's model — where participants contribute to the network rather than just consuming it — aligns naturally with our values around community-owned infrastructure. Running an I2P node is a small contribution to a global network that exists outside corporate control. If the Collective sets up I2P-internal services (a community bulletin board, file sharing, or communication tools), we'll announce it through the mailing list.

---

> Next up: **[2.05 SimpleX Chat →](/guides/advanced/5-simplex/)**  
> Encrypted messaging with no user identifiers at all.

---

> Questions? [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
