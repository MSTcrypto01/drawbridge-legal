---
layout: default
title: "Privacy Policy"
version: 0.3.0-draft
effective: 2026-12-01
permalink: /privacy/
lang: en
dir: ltr
---
# Privacy Policy

**DRAFT — not yet reviewed by qualified counsel. Not for production use.**

Drawbridge is designed so that we do not need your personal data. This policy explains what stays on your device, what leaves it, and when.

## 1. What we do not collect
- No account, name, email, phone number or password.
- No analytics, advertising identifiers, tracking, crash-report uploads, or remote configuration.
- No recovery phrases, private keys, PINs or biometric data — ever.

## 2. Data stored only on your device
- **Secrets** (your encrypted wallet vault, PIN-derived key material, optional authenticator secret) are stored in the iOS Keychain, bound to this device and never synced to iCloud.
- **Wallet data** (public addresses, cached balances and prices with timestamps, transaction records, address book, settings, consent records, and the network activity log) is stored in the app's private storage with iOS Data Protection and excluded from device backups.
- **Camera**: used only to scan QR codes. Frames are processed in memory and never stored or transmitted.
- **Face ID / Touch ID** is handled entirely by iOS. The App receives only a success or failure result.
- **On-device explanations** use Apple's on-device language model when available. Prompts contain only a non-secret summary of the transaction and never leave your device.

You can delete all of this at any time with Settings → Erase this device, or by deleting the App.

## 3. Data that leaves your device (only in online sessions you open)
During an online session the App contacts only the hosts listed on the session screen, for the permissions you selected:
- **Blockchain endpoints** (default public endpoints or your own) receive your IP address and the public addresses or transactions being queried or broadcast. Public blockchain data is, by design, visible to everyone.
- **Price source** receives only the list of asset identifiers (for example "bitcoin"), never your addresses.
These providers are independent third parties with their own privacy policies (see the Third-Party Provider Disclosure). Opening a block-explorer link opens Safari and shares the transaction ID with that site.

## 3a. Optional services (only where offered, and only when you use them)
- **Swaps and bridges.** To build your transaction, the provider you choose (Jupiter or LI.FI) receives your IP address, your public wallet address and the trade details (assets, amount, slippage tolerance) during a session that includes the swap permission. Drawbridge does not receive this data. The provider's own privacy policy applies.
- **Service settings.** When you check for service updates, the App downloads a signed settings file from Drawbridge. The request contains no address, identifier or device data. Our server sees your IP address as part of the connection. **Counsel decision required:** log retention period.
- **Drawbridge Pro.** Purchases are handled by Apple through In-App Purchase; Drawbridge never receives your Apple ID or payment details. The App checks your subscription on the device with Apple's signed receipts, and no Drawbridge server receives purchase events. Apple gives us sales and tax reports in App Store Connect that do not identify you. If we ever receive Apple's subscription notifications on a server, this policy will say so first.
- **App Store region.** The App reads your App Store storefront country on the device to decide which optional services may be shown. It is not sent to us.

## 3b. If you contact us
If you email support at **drawbridge.wallet@outlook.com**, we receive your email address and whatever you write or attach, through our email provider (Microsoft Outlook.com). We use it only to answer you and to keep the complaint records described in the Support and Complaints Policy, for the period in the Data Retention Policy. The App never sends us anything itself: the "Email support" button opens your own mail app with a message you can read and change first. Never include your recovery phrase, passphrase, PIN or private keys.

## 4. Legal bases and roles
For the basic wallet we do not process your personal data on our systems. Where optional services are offered in the future (for example, support or paid features), we will process only the minimum data needed, explain it before you use the service, and rely on contract performance, legal obligation or legitimate interests as applicable under the EU/UK GDPR, the Saudi Personal Data Protection Law (PDPL), and other laws.

## 5. Your rights
Depending on where you live (including under GDPR, UK GDPR, the PDPL and US state laws such as the CCPA/CPRA), you may have rights to access, correct, delete, restrict or port your data and to object to processing. Because the basic wallet keeps data only on your device, you exercise most of these directly in the App. We do not sell or share personal information for cross-context behavioral advertising.

## 6. Security
Data is protected with the Secure Enclave, the Keychain, authenticated encryption and iOS Data Protection. No system is perfectly secure; see the Self-Custody Disclosure for your role.

## 7. Children
The App is not directed to anyone under 18.

## 8. Changes and contact
Material changes are versioned and presented for acceptance. Questions about this policy or your data: **drawbridge.wallet@outlook.com** (see also the Support and Complaints Policy). **Counsel decision required:** data controller identity, representative (EU/UK) and DPO requirements per launch market.
