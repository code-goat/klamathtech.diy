---
title: "2.05 SimpleX Chat"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 5
draft: false
description: "SimpleX Chat has no user identifiers — no phone number, no username, no account. Here's how it works and when it matters."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 5
---

# SimpleX Chat — Messaging Without Identifiers

Signal is excellent. But Signal requires a phone number — a real-world identifier tied to your carrier, your identity, and potentially your location history. If your threat model includes someone who can obtain your phone number and connect it to your communications, Signal's anonymity has a ceiling.

**SimpleX Chat** removes that ceiling.

---

## What Makes SimpleX Different

SimpleX has **no user identifiers**. Not a phone number. Not a username. Not an email address. There is no account in the traditional sense.

Instead, it uses **one-time queue addresses** for each conversation. To connect with someone:
1. One person generates a connection link (a one-time address)
2. The other person uses that link to connect
3. The link can be discarded afterward

Each conversation happens through a separate queue. Even if SimpleX's servers were compromised, there is no identifier to connect your different conversations to each other — because none exists.

This is categorically different from Signal, where all your conversations are linked to a single phone number that exists in Signal's records.

---

## End-to-End Encryption

SimpleX uses strong end-to-end encryption (double ratchet protocol, similar to Signal) for all messages. Metadata — who talked to whom, when — is also protected, because the server only processes anonymous queue addresses, not user accounts.

---

## Self-Hosting

SimpleX allows you to run your own **SimpleX Relay server**, giving a community full control over the infrastructure that passes messages between members. Your messages never touch SimpleX's company servers unless you choose to use them.

This is a natural fit for a collective that wants to own its communication infrastructure. A community-run SimpleX relay means:
- No dependency on a company
- No third party that could be compelled to hand over data (though there's nothing to hand over anyway)
- Infrastructure that stays in community hands

---

## Trade-offs

**Newer, fewer features** than Signal — no voice/video calls as of this writing, smaller user base, fewer integrations.

**Connection setup is slightly more manual** — generating and sharing a link rather than just entering a phone number.

**Less community adoption** — the "but nobody I know uses it" problem applies more strongly than with Signal. Start with Signal; move specific high-sensitivity conversations to SimpleX when it matters.

---

## Get SimpleX

**[simplex.chat](https://simplex.chat)** — available for Android, iPhone, and desktop (Linux, Mac, Windows)

SimpleX is open-source. Source code is available for review at github.com/simplex-chat.

---

> Next up: **[2.06 Secure Operating Systems →](/guides/advanced/6-os/)**

---

> Questions? [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
