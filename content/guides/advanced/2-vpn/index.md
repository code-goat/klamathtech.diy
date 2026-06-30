---
title: "2.02 VPNs"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 2
draft: false
description: "VPNs are widely misunderstood. Here's what they actually do, what they don't do, and when they're worth using."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 2
---

# VPNs — What They Do and Don't Do

VPNs are one of the most marketed privacy tools on the internet — and one of the most misunderstood. Influencer sponsorships claim they make you "completely anonymous" and protect you from "hackers." Most of this is exaggerated or flat-out wrong.

Here is what VPNs actually do.

---

## What a VPN Is

A **Virtual Private Network (VPN)** creates an encrypted tunnel between your device and a VPN server. Your internet traffic flows through that tunnel, so:

- The websites you visit see the VPN server's IP address, not yours
- Your internet provider sees that you are connected to a VPN, but not which sites you visit
- Someone monitoring the network you're on (hotel Wi-Fi, coffee shop, school) cannot see your traffic

---

## What a VPN Helps With

- **Preventing your ISP from logging and selling your browsing history** — ISPs in the U.S. are legally allowed to sell this data. A VPN stops them from seeing it.
- **Using untrusted networks safely** — public Wi-Fi at hotels, airports, cafes. Your traffic is encrypted before it hits the local network.
- **Circumventing geographic restrictions** — some content is blocked by country; a VPN in a different country can work around this.
- **Hiding your general location** from websites you visit.

---

## What a VPN Does NOT Do

- **Make you anonymous.** The VPN provider can see all your traffic. You are shifting trust from your ISP to the VPN company. If that company logs data or complies with legal requests, your privacy is gone.
- **Protect you when logged in.** Google, Facebook, and other services identify you by your account, regardless of your IP address.
- **Encrypt traffic to websites.** HTTPS already does this for any modern site. A VPN adds an extra layer, but it is not providing the core encryption.
- **Stop tracking.** Cookies, browser fingerprinting, and logged-in accounts track you independent of your IP.

---

## When to Use One

A VPN makes sense if:
- You regularly use public Wi-Fi
- You want to prevent your ISP from logging your browsing
- You are in a country or on a network that censors internet access
- Your threat model includes ISP-level surveillance but not government-level adversaries

A VPN does **not** replace Tor for anonymity. A VPN does not protect against a well-resourced adversary who can compel the provider to hand over logs.

---

## What We Recommend

Choose a VPN with a **no-logs policy that has been independently audited** — not just claimed. Two well-regarded options:

**Mullvad** — accepts cash and cryptocurrency, requires no email address to sign up, has been audited and had servers seized by police (who found nothing because of the no-logs policy). [mullvad.net](https://mullvad.net)

**ProtonVPN** — from the same company as Proton Mail, based in Switzerland. Has a free tier. Open-source. [protonvpn.com](https://protonvpn.com)

**Avoid free VPNs.** Free VPN services almost always monetize your data — the opposite of the protection you want. The exception is ProtonVPN's free tier, which is legitimately free and does not log.

---

> Next up: **[2.03 Tor →](/guides/advanced/3-tor/)**  
> For stronger anonymity than a VPN can provide.

---

> Questions? [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
