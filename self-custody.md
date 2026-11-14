---
layout: default
title: "Self-Custody Disclosure"
version: 0.1.0-draft
effective: 2026-12-01
permalink: /self-custody/
lang: en
dir: ltr
---
# Self-Custody Disclosure

**DRAFT — not yet reviewed by qualified counsel.**

Drawbridge is a self-custodial wallet. Please read this carefully: it changes who is responsible for your funds.

## You alone control your assets
- Your recovery phrase (12 or 24 words) is generated on your device and is the master key to every account in the wallet.
- We never see it, store it, or back it up. We have no ability to access, freeze, move, or recover your funds, and we cannot reverse transactions.
- There is no "forgot password" and no company recovery backdoor. This is deliberate: it means no one at Drawbridge can be pressured, hacked or ordered into taking your assets.

## If you lose your recovery phrase
If you lose your phone **and** your recovery phrase, your funds are permanently lost. If you lose only your phone, you can restore the wallet on any compatible wallet using the phrase.

## If someone else gets your recovery phrase
They can take all your funds, from anywhere, without your device. If you think your phrase was exposed, create a new wallet and move your funds immediately.

## Optional passphrase
A passphrase creates a different, hidden wallet from the same phrase. Forgetting it means losing access to that wallet. We cannot recover it.

## Your device
The App encrypts its vault with keys protected by the Secure Enclave and your PIN, but a compromised or jailbroken device, malicious apps, or someone who knows your device passcode may still put funds at risk. Keep iOS updated and use a strong device passcode.

## Good practice
- Write the phrase on paper (or metal) and store it securely offline; consider a second copy in a separate place.
- Never type it into websites, share it, photograph it, or store it in cloud services or password managers you do not fully control.
- Use the in-app Recovery check to confirm your backup.
- Plan how trusted people could access your assets if something happens to you, without exposing your phrase today.
