---
layout: default
title: "Data Processing Disclosure"
version: 0.1.0-draft
effective: 2026-12-01
permalink: /data-processing/
lang: en
dir: ltr
---
# Data Processing Disclosure

**DRAFT — not yet reviewed by qualified counsel.**

| Activity | Data | Where | When | Purpose |
|---|---|---|---|---|
| Key generation and signing | Recovery phrase, keys | On device only (Secure Enclave-protected vault) | When you create, unlock or sign | Operate your wallet |
| Balance cache, history, address book | Public addresses, amounts, labels | On device only | Always | Show your portfolio offline |
| Network log | Host, path, permission, outcome (no query strings) | On device only | Every online request | Transparency and auditing |
| Online session requests | IP address, public addresses, signed transactions | Endpoints you approve | Only during sessions | Read balances, estimate fees, broadcast |
| Price requests | Asset identifiers | Price source | Only during sessions with "Prices" | Show fiat values |
| QR scanning | Camera frames | On device, in memory | While scanning | Read payment codes |
| On-device explanations | Non-secret transaction summary | On device | When you tap "Explain" | Plain-language help |

No automated decision-making with legal effects, profiling, or data sales takes place. Optional future services that require server-side processing will be listed here, with retention periods, before they are offered.
