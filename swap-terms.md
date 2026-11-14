---
layout: default
title: "Swap Terms"
version: 0.2.0-draft
effective: 2026-12-01
permalink: /swap-terms/
lang: en
dir: ltr
---
# Swap Terms

**DRAFT — swaps and bridges are switched off in this build. They are offered only in App Store regions listed in a signed service configuration, after provider terms and a legal opinion for that region are in place.**

## The service
Swaps exchange one asset for another, and bridges move value between networks, through independent third-party providers: **Jupiter** (Solana) and **LI.FI** (Ethereum, Base, Arbitrum, OP Mainnet, Polygon and BNB Smart Chain). Drawbridge never takes custody of your assets. The provider builds a transaction; the App checks it against the quote you saw and you sign it from your own wallet.

## Drawbridge fees
| Trade | Drawbridge fee |
|---|---|
| Swap under $10,000 | 0.50% |
| Swap $10,000 to $49,999 | 0.30% |
| Swap $50,000 and above | 0.20% |
| Stablecoin to stablecoin | 0.10% |
| Bridge | 0.25%, plus the bridge's own costs |
| Drawbridge Pro members | 50% off the fees above |

- The trade size is estimated from the last prices on your device. If no price is available, the standard 0.50% applies.
- No Drawbridge fee can exceed **1.00%**. This cap is built into the App and cannot be changed remotely.
- The fee is collected by the provider in the token it is charged in (Jupiter: the token you receive; LI.FI: the token you pay) and paid to a company account. It is shown as its own line, with its amount, before you confirm.
- If a provider route cannot carry the Drawbridge fee, you pay no Drawbridge fee on that route. The App says so.
- Sending, receiving and storing assets carry no Drawbridge fee.

## Other costs, shown separately
- **Provider fees.** For example, LI.FI currently charges its own 0.25% on each transaction. Provider fees are shown with the provider's name.
- **Network fees** go to the blockchain's validators.
- **Price impact** and **slippage tolerance**, with the **minimum amount you will receive**. If the price moves beyond your tolerance, the swap is cancelled and only the network fee is spent.

## Best net execution
Quotes are ranked solely by the amount you receive after all fees. What Drawbridge earns is not an input to ranking, so a route that pays Drawbridge more never outranks one that leaves you better off. The App rejects any quote whose Drawbridge fee differs from this schedule.

## Checks before you sign
The App refuses to sign a provider transaction unless: your account is the only signer and pays the network fee; the amount, slippage and Drawbridge fee match the quote; the fee goes to an approved company account; only approved programs or contracts are called; token approvals are for the exact amount; and a network simulation succeeds. These checks reduce, but do not remove, smart-contract and provider risk.

## Risks
Quotes expire quickly; prices move; transactions may fail or return less than expected within your slippage limit; smart contracts, bridges and liquidity sources can fail or be exploited; front-running (MEV) can affect execution; bridged assets can be delayed.

## Availability
Swaps and bridges may be unavailable in your region or for some assets. Provider terms may apply and are linked before first use.
