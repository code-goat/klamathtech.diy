---
title: "2.07 Mobile Devices"
date: "2025-04-20"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 7
draft: false
description: "Smartphones are the hardest devices to secure. GrapheneOS, CalyxOS, and what to do if you can't replace your OS."
tags: ["guides", "Skills", "Advanced"]
series: ["Advanced Privacy"]
series_order: 7
---

# Mobile Devices

Smartphones are the most privacy-hostile devices most people own. They:

- Know your location at all times via GPS, cell towers, and Wi-Fi
- Contain your messages, photos, contacts, financial apps, and health data
- Run operating systems controlled entirely by Apple or Google
- Carry sensors that can be accessed by apps (microphone, camera, accelerometer)
- Are always connected and rarely powered off

The operating systems on most phones — iOS and standard Android — are closed-source, phone home to their parent companies, and comply with law enforcement requests. For high-sensitivity situations, replacing the OS is the most effective option.

---

## We Have a Dedicated Android Guide

For a full walkthrough — from basic stock Android hardening all the way through GrapheneOS installation — including the current threat to Android's openness from Google's new developer registration policy:

**[→ Android Privacy: From Stock to Sovereign](/guides/android/)**

The guide covers:
- Reviewing and restricting app permissions on any Android phone
- Disabling advertising ID tracking
- Encrypted DNS setup
- F-Droid installation (open-source app store — install this before Google's policy change makes it harder)
- GrapheneOS: what it offers, which devices it supports, how to install it
- CalyxOS as a more accessible alternative
- A note on iOS for comparison

---

## Quick Summary

**GrapheneOS** ([grapheneos.org](https://grapheneos.org)) is the strongest option for Android privacy. It removes Google's tracking infrastructure, hardens the OS against exploits, and adds per-app network and storage permissions. It runs on supported Google Pixel phones (Pixel 6 through Pixel 9 series). The web installer has made installation significantly more accessible.

**CalyxOS** ([calyxos.org](https://calyxos.org)) supports a wider range of devices and includes microG (a free reimplementation of Google Play Services) by default, meaning more apps work out of the box. It makes slightly different security trade-offs than GrapheneOS in exchange for broader compatibility.

**Standard Android** can be meaningfully hardened without replacing the OS. See the [Android guide](/guides/android/) for specifics.

**iOS** is a closed system. Apple is less advertising-dependent than Google, which makes iOS better than standard Android for everyday privacy. But iOS cannot be audited, modified, or replaced. Apple has built-in capabilities to scan device content and has complied with numerous law enforcement requests. For the strongest privacy, a custom Android OS on a Pixel remains the better choice.

---

## You've Reached the End of Advanced Privacy

If you have worked through this series alongside [Privacy 101](/guides/privacy101/), you have a thorough foundation. The right next step depends on your situation — return to [Threat Modeling](/guides/advanced/1-threat-model/) if you want to revisit which tools actually match your needs.

---

> Questions, or want hands-on help with any of this? Reach us at [contact@klamathtech.diy](mailto:contact@klamathtech.diy) or come to a workshop.

> Stay connected through our mailing list:
{{< subscribe-form >}}
