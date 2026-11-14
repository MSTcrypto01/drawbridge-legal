---
layout: default
title: "Recovery Policy"
version: 0.1.0-draft
effective: 2026-12-01
permalink: /recovery/
lang: en
dir: ltr
---
# Recovery Policy

**DRAFT — not yet reviewed by qualified counsel.**

## The only recovery method is your recovery phrase
Drawbridge has no company backup, no social or identity-based recovery, and no administrative override. Support staff can never recover a wallet and will never ask for your phrase.

## Interoperability (open standards)
Drawbridge uses BIP-39 phrases (English wordlist) and these derivation paths, so you can restore in other compatible wallets:
- Bitcoin: BIP-84 native SegWit, `m/84'/0'/account'/change/index` (Testnet4: coin type 1)
- Ethereum and EVM chains: `m/44'/60'/0'/0/index` (one account per index)
- Solana: SLIP-0010 Ed25519, `m/44'/501'/account'/0'`

## Recovery check
Use Security → Recovery check to confirm your written phrase restores this wallet. The check compares a non-reversible fingerprint on your device and stores nothing you type.

## Lost or stolen device
Your funds remain on the blockchains. Restore on a new device with your phrase. If the old device might be unlocked by someone else, move your funds to a new wallet.

## Exposed phrase
Assume any exposed phrase is compromised. Create a new wallet and transfer your assets immediately.
