---
title: "2.01 Threat Modeling"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 1
draft: false
description: "Before choosing tools, know what you're protecting and from whom. This is how security professionals think."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 1
---

# Start With Threat Modeling

Before installing Tor or switching to a secure operating system, ask yourself: **what am I trying to protect, from whom?**

This is called **threat modeling**, and it is how security professionals think. The right level of privacy protection depends entirely on your specific situation. Using high-friction tools you do not need creates burden without benefit. Using tools that do not match your threat leaves you exposed.

---

## The Four Questions

**1. What do you want to keep private?**
Financial information? Health data? Organizing conversations? Your physical location? Your identity? The content of your communications? Your network of contacts?

**2. From whom?**
These are very different adversaries requiring different tools:
- Advertisers and data brokers (very common threat — Privacy 101 handles most of this)
- Your internet provider
- Your employer or school
- A stalker or abusive partner
- Law enforcement with a warrant
- A government with broad surveillance powers

**3. What would happen if it were exposed?**
Embarrassment? Financial harm? Loss of employment? Legal jeopardy? Physical danger? The answer shapes how much friction is worth accepting.

**4. How much inconvenience will you tolerate?**
Higher security tools often mean slower connections, more steps, and fewer compatible services. Security you do not use is no security at all.

---

## Common Threat Profiles

**Everyday person** — concerned about data brokers, targeted advertising, ISP surveillance, and account compromise. **Privacy 101 is sufficient.** Add a VPN for untrusted networks.

**Activist or organizer** — concerned about surveillance of political activity, infiltration of groups, and potential law enforcement interest. Add Signal (with best practices), consider Tor for sensitive research, think carefully about group communication security.

**Journalist or source** — protecting the identity of sources is often the primary concern. Tor Browser, SecureDrop, Tails, Signal, and compartmentalization of identities.

**Survivor of stalking or domestic violence** — threat is often a known individual with physical access to your devices. Device encryption, separate accounts, careful location privacy, and a safety plan that includes tech are critical. [The Safety Net project](https://www.techsafety.org/) has specialized resources.

**Whistleblower** — protecting identity from a well-resourced adversary (employer, government). Tails, Tor, SecureDrop, and ideally working with a journalist who has experience in this area.

---

## One More Thing: Compartmentalization

Security thinking often involves keeping different parts of your life separate — different browsers for different purposes, different devices, different accounts. This is called **compartmentalization**.

The more compartments, the harder it is to connect dots across them. The more compartments, the more effort to maintain. Find the level that matches your actual situation.

---

> Next up: **[2.02 VPNs →](/guides/advanced/2-vpn/)**

---

> Questions? [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
