---
title: "1.04 Password Manager"
date: "2025-04-20"
authors:
- "fern"
- "collective"
image_style: "background"
heroStyle: "background"
weight: 4
draft: false
description: "Stop reusing passwords. One data breach can unlock your whole digital life."
tags: ["guides", "Skills", "Privacy 101"]
series: ["Privacy 101"]
series_order: 4
---

# The Password Problem

Here is how most accounts get hacked: not through movie-style hacking, but through a company you signed up with years ago getting breached, and your username and password leaking to the internet. Hackers then try those same credentials on your email, your bank, your social media accounts. If you used the same password, they get in.

This is called **credential stuffing**, and it is responsible for the vast majority of personal account takeovers.

The solution is to use a different, strong password for every single account. The catch: no human can remember hundreds of different passwords. That is what a **password manager** is for.

---

## What a Password Manager Does

A password manager is a secure, encrypted vault that stores all your passwords. You only need to remember one password — the master password to unlock the vault. The password manager generates, stores, and autofills strong, unique passwords for every site you use.

The result:
- Every account has a different password (so one breach doesn't cascade)
- Every password is long and random (so it can't be guessed)
- You don't have to remember any of them (so you'll actually use them)

---

## What We Recommend

### Bitwarden — Free, Open-Source, Best All-Around

**Bitwarden** is a free, open-source password manager. Its code is publicly audited, which means security researchers can verify it works as claimed. It syncs across all your devices, works in any browser, and has apps for both Android and iPhone.

The free tier is fully functional for individual use. There is a paid tier ($10/year) that adds features like advanced two-factor authentication and encrypted file storage, but you do not need it to start.

**Get it:** [bitwarden.com](https://bitwarden.com)

**How to get started:**
1. Create an account at bitwarden.com
2. Install the browser extension (available for Firefox, Brave, Chrome, Edge, and Safari)
3. Install the mobile app on your phone
4. Start adding your accounts — either by importing from your browser's saved passwords, or by adding them one at a time as you log in

**Set a strong master password** — this is the one password you must remember. Make it a passphrase: four or five random words strung together (like `correct-horse-battery-staple`). It's long and memorable.

### KeePassXC — Offline, No Cloud

**KeePassXC** is a free, open-source password manager that stores your vault as a file on your own device — no cloud sync, no external server. It is the best choice if you prefer not to trust any company with your vault, or if you have limited or unreliable internet access.

The trade-off is that syncing across devices requires extra steps (you can store the vault file on a USB drive, or use a self-hosted sync service like Nextcloud).

**Get it:** [keepassxc.org](https://keepassxc.org)

---

## What About the Browser's Built-In Password Manager?

Chrome, Firefox, and Safari all offer to save passwords. These are significantly better than reusing passwords, and if using one is the difference between you reusing passwords and not, use it.

However, dedicated password managers offer more security: they are encrypted with your master password (the browser often ties saved passwords to your OS login), they work across all browsers and apps, they include breach monitoring, and they are not tied to a company that might change its policies.

Think of the browser's password manager as a stepping stone — use it now, graduate to Bitwarden when you're ready.

---

## Two-Factor Authentication (2FA)

While you're setting up a password manager, enable **two-factor authentication** on your most important accounts — especially email, banking, and social media. This adds a second step (usually a code from an app on your phone) that an attacker would need even if they had your password.

Use an authenticator app rather than SMS text message codes when possible — texts can be intercepted through SIM-swap attacks. Good free options: **Aegis** (Android, open-source), **Raivo** (iPhone).

---

> Next up: **[1.05 Email →](/guides/privacy101/5-email/)**  
> Your email is the master key to your digital life — here's how to protect it.

---

> Questions or want hands-on help setting up a password manager? Come to one of our workshops or reach us at [contact@klamathtech.diy](mailto:contact@klamathtech.diy)
