---
layout: default
title: "Third-Party Provider Disclosure"
version: 0.2.0-draft
effective: 2026-12-01
permalink: /third-party/
lang: en
dir: ltr
---
# Third-Party Provider Disclosure

**DRAFT — not yet reviewed by qualified counsel.**

Drawbridge contacts third parties **only during online sessions you open**, and only the hosts shown on the session screen. These providers are independent of us, can see your IP address and the public data you request, and have their own terms and privacy policies. You can replace any blockchain endpoint with your own node in Settings → Endpoints.

## Default endpoints in this build
| Purpose | Provider (host) |
|---|---|
| Bitcoin and Bitcoin Testnet4 data & broadcast | mempool.space |
| Ethereum / Sepolia | ethereum-rpc.publicnode.com / ethereum-sepolia-rpc.publicnode.com |
| Base / Base Sepolia | mainnet.base.org / sepolia.base.org |
| Arbitrum / Arbitrum Sepolia | arb1.arbitrum.io / sepolia-rollup.arbitrum.io |
| OP Mainnet / OP Sepolia | mainnet.optimism.io / sepolia.optimism.io |
| Polygon / Amoy | polygon-bor-rpc.publicnode.com / rpc-amoy.polygon.technology |
| BNB Smart Chain / testnet | bsc-dataseed.bnbchain.org / bsc-testnet-dataseed.bnbchain.org |
| Solana / Devnet | api.mainnet-beta.solana.com / api.devnet.solana.com |
| USD prices (asset ids only) | api.coingecko.com |

## Fallback endpoints
When a default endpoint is rate-limited, refuses a request or does not answer, the App tries the public alternatives
below, in order, for that network only. Each must first show that it serves the expected network (chain id or genesis
block) before any of its data is used. They are listed on the session screen with the other hosts, so a session can
contact them only if you approve it. If you replace an endpoint with your own node, no fallback is used for that network.

| Network | Fallback hosts |
|---|---|
| Bitcoin | blockstream.info |
| Ethereum | eth.drpc.org |
| Base | base-rpc.publicnode.com, base.drpc.org |
| Arbitrum | arbitrum-one-rpc.publicnode.com, arbitrum.drpc.org |
| OP Mainnet | optimism-rpc.publicnode.com, optimism.drpc.org |
| Polygon | polygon.drpc.org |
| BNB Smart Chain | bsc-rpc.publicnode.com, bsc.drpc.org |

## Platform providers
Apple provides the App Store, TestFlight, Face ID, the Secure Enclave and on-device language models. The App contains no third-party analytics, advertising, or crash-reporting SDKs.

## No endorsement
Listing a provider is not an endorsement. Providers can be unavailable, rate-limited, inaccurate, or change their practices.
