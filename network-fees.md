---
layout: default
title: "Network Fee Disclosure"
version: 0.1.0-draft
effective: 2026-12-01
permalink: /network-fees/
lang: en
dir: ltr
---
# Network Fee Disclosure

**DRAFT — not yet reviewed by qualified counsel.**

Every blockchain transaction pays a **network fee** to the validators or miners that process it. Drawbridge does not receive any part of network fees and charges **0%** for sending, receiving, or storing assets. The review screen always shows the complete fee breakdown, including a "Drawbridge fee: None" line, before you sign.

## How fees are estimated
- **Bitcoin**: fee = transaction size (virtual bytes) × fee rate (sat/vB). Drawbridge enables Replace-By-Fee so a stuck transaction can be bumped. Very small change amounts below the dust limit are added to the fee instead of creating unspendable outputs; this is shown in the fee.
- **Ethereum and EVM chains**: the review shows the **maximum** fee (gas limit × max fee per gas). You usually pay less: the actual fee is gas used × (base fee + priority fee). Unused allowance is never charged.
- **OP-Stack networks (Base, OP Mainnet)**: an additional **L1 data fee** for posting data to Ethereum is shown as its own line.
- **Solana**: a base fee per signature plus an optional priority fee. If a recipient has no account for a token, a refundable-style **rent deposit** (about 0.002 SOL) is paid to create it and shown separately.

## Important
- Fees are set by the network and can change between preview and confirmation. Previews expire and must be refreshed.
- Failed transactions can still consume fees.
- Transactions prepared offline use cached fee data that may be outdated.
