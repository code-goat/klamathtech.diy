---
title: "Android Privacy: From Stock to Sovereign"
date: "2026-06-29"
authors:
- "fern"
- "collective"
heroStyle: "background"
weight: 1
draft: false
description: "A guide to reclaiming your Android phone — from basic hardening to GrapheneOS — and why Android's openness is under serious threat."
tags: ["guides", "Skills", "Android", "Mobile Privacy"]
---

# Your Phone Is the Most Surveilled Device You Own

It knows where you are at all times. It contains your messages, photos, contacts, financial apps, and health data. It listens for wake words. It runs apps from dozens of corporations, each with their own data collection practices.

Most of us carry this device everywhere and hand it to our kids. Taking back some control over what it does is one of the most meaningful privacy steps you can take.

This guide covers Android specifically — both because Android is more configurable than iOS, and because Android's openness is currently under a serious, organized threat that every Android user should know about.

---

## First: The Threat to Android's Openness

Android has long been the more "open" of the two major mobile platforms. Unlike Apple's iPhone, Android has allowed users to install apps from outside the official store, run alternative app stores, and — for the technically inclined — replace the entire operating system with a more private alternative.

**That openness is being systematically dismantled.**

Starting in late 2026, Google is requiring all Android app developers to register centrally with Google, submit government-issued identification, agree to Google's terms, and pay a fee — **even for apps distributed entirely outside the Google Play Store**. Apps from non-compliant developers will be silently blocked on all certified Android devices worldwide. This affects F-Droid (the open-source app repository), independent developers, volunteer projects, and privacy tools created by people who cannot or will not expose their identity to Google's database.

A coalition of 71 digital rights organizations from 23 countries — including the EFF, the Free Software Foundation, Brave, Proton, F-Droid, and Tuta — signed an open letter opposing the policy. Their core argument: Google's existing OS-level security, app sandboxing, and permission systems have protected users for seventeen years. This new policy isn't about security. It's about control.

The campaign for Android openness is at **[keepandroidopen.org](https://keepandroidopen.org)**. It is worth reading, signing, and sharing.

**What you can do right now:**
- Install **F-Droid** on your Android device before this change takes effect — [f-droid.org](https://f-droid.org)
- Share [keepandroidopen.org](https://keepandroidopen.org) with other Android users

---

## Hardening a Standard Android Phone

Not everyone can or should flash a custom operating system. Here is what you can do on any Android phone to meaningfully improve your privacy.

### Review and Restrict App Permissions

Go to **Settings → Privacy → Permission Manager**. Work through each permission category:

- **Location:** Only grant "While using the app" — never "Always" — unless you have a specific reason. Revoke location from any app that doesn't clearly need it.
- **Microphone and Camera:** Revoke from any app you don't actively use for calling or video.
- **Contacts, Calendar, Storage:** Grant only to apps with an obvious need. Does a flashlight app need your contacts? No.

On Android 12+, a green indicator appears in the status bar when an app accesses your camera or microphone. Pay attention to when it appears.

### Disable Advertising ID Tracking

Go to **Settings → Privacy → Ads** and select **Delete advertising ID**. This removes the unique identifier that ad networks use to track you across apps.

### Turn Off Google's Data Collection

In **Settings → Google → Manage your Google Account → Data & Privacy**, you can pause:
- Web & App Activity
- Location History
- YouTube History

These are on by default and feed Google's advertising profile of you.

### Encrypted DNS

Your DNS queries — the requests your phone makes to look up every website — are readable by your carrier by default. Switch to an encrypted DNS provider:

Go to **Settings → Network & Internet → Private DNS** and enter `dns.quad9.net` (Quad9, a nonprofit) or `1dot1dot1dot1.cloudflare-dns.com` (Cloudflare).

### Lock Down the Lock Screen

- Use a PIN or passphrase, not a pattern (patterns leave smudge trails) and not biometrics alone (you can be compelled to provide your fingerprint; you cannot legally be compelled to provide a passphrase in most U.S. jurisdictions)
- Disable lock screen notifications, or set them to hide content: **Settings → Notifications → Notifications on Lock Screen → Hide silent conversations and notifications**

### Use an Open-Source App Store

**F-Droid** ([f-droid.org](https://f-droid.org)) is a free and open-source app repository containing only FOSS apps. Many privacy tools — including NewPipe (YouTube without tracking), Aegis (authenticator), Organic Maps (offline maps), and more — are available there. Install it now, before Google's policy change makes it harder.

---

## GrapheneOS: Maximum Privacy on Android

**GrapheneOS** is a privacy and security focused Android fork that can be installed on supported **Google Pixel** phones. It strips out Google's tracking infrastructure entirely while maintaining broad compatibility with Android apps.

GrapheneOS is the strongest option for Android privacy. It is what journalists, security researchers, and people in high-risk situations use. It is also genuinely usable as an everyday phone.

**What GrapheneOS offers:**
- No Google services by default (you can install sandboxed Google Play if you need specific apps — they run isolated, with no special system privileges)
- Hardened memory allocator and exploit mitigations beyond stock Android
- Network permission controls — you can block any app from accessing the internet entirely
- Storage scopes — apps can only see the files you explicitly grant them access to
- Verified boot ensuring your OS hasn't been tampered with
- Regular, fast security updates

**Get it:** [grapheneos.org](https://grapheneos.org)

**Supported devices:** GrapheneOS only supports Google Pixel phones (currently Pixel 6 through Pixel 9 series). This is because Pixels have the hardware security features GrapheneOS requires for verified boot. You do not need to use Google services — just the hardware.

### Is GrapheneOS Hard to Install?

The web-based installer at [grapheneos.org/install/web](https://grapheneos.org/install/web) has made installation much more accessible than it used to be. If you are comfortable following step-by-step instructions, it is manageable. If you want hands-on help, reach out to us — the Collective can help walk you through it.

Things you will need:
- A supported Pixel phone
- A computer with a USB port and Chrome or a Chromium-based browser (for the web installer)
- About an hour

### After Installing GrapheneOS

A few recommended first steps:

- **Set up profiles** — GrapheneOS supports multiple user profiles. You can have a "main" profile and a separate "Google apps" profile where sandboxed Play Services runs, keeping it isolated from your primary data.
- **Install Vanadium** — GrapheneOS's hardened browser, based on Chromium. Available in the GrapheneOS App Store.
- **Install the GrapheneOS App Store** for curated, security-reviewed apps.
- **Install F-Droid** for the broader open-source ecosystem.
- **Configure network permissions** — go through installed apps and disable internet access for any that don't need it.

---

## CalyxOS: A More Accessible Alternative

**CalyxOS** ([calyxos.org](https://calyxos.org)) is another privacy-focused Android fork, supporting a wider range of devices than GrapheneOS. It includes microG (a free reimplementation of Google Play Services) by default, which means more apps work out of the box without any Google services setup.

CalyxOS makes some security trade-offs compared to GrapheneOS in exchange for broader compatibility and easier setup. For most people who are not in high-risk situations, those trade-offs are reasonable.

---

## iOS: A Brief Note

If you use an iPhone: iOS is meaningfully better than stock Android for privacy in some ways — Apple's business model is less advertising-dependent than Google's, and iOS has strong on-device encryption. But iOS is a completely closed system. You cannot verify what it does, cannot replace it, and are entirely dependent on Apple's policies and compliance with government requests.

Apple has built-in capabilities to scan device content and has complied with law enforcement requests in numerous documented cases. For the strongest privacy, a custom Android OS on a Pixel remains the better choice for those who can manage it.

---

## Resources

- **[Keep Android Open](https://keepandroidopen.org)** — the campaign against Google's developer registration policy
- **[GrapheneOS](https://grapheneos.org)** — installation guide and documentation
- **[CalyxOS](https://calyxos.org)** — more accessible alternative
- **[F-Droid](https://f-droid.org)** — open-source Android app repository
- **[EFF's Surveillance Self-Defense — Android](https://ssd.eff.org)** — practical guides for hardening stock Android

---

> Want help with any of this in person — installing F-Droid, flashing GrapheneOS, reviewing your permissions? Come to a workshop or reach us at [contact@klamathtech.diy](mailto:contact@klamathtech.diy).
