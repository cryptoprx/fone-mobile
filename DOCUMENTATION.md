<div align="center">
  <img src="./assets/icon.png" alt="fONE Logo" width="90" style="border-radius: 18px;" />

  # fONE (FLIPPRX Mobile)
  ### Official Repository & Consumer Documentation

  [![XRPL Native](https://img.shields.io/badge/XRPL-Native%20Layer%201-blue.svg)](https://xrpl.org)
  [![Version](https://img.shields.io/badge/Version-Beta%20v1.0.0-orange.svg)](#version-metadata)
  [![Google Play](https://img.shields.io/badge/Google%20Play-Coming%20Soon-yellow.svg)](#installation--getting-started)
  [![iOS App Store](https://img.shields.io/badge/iOS%20App%20Store-Coming%20Soon-yellow.svg)](#installation--getting-started)
  [![Non-Custodial](https://img.shields.io/badge/Custody-Self--Custodial-green.svg)](#security--privacy-model)
  [![Hardware Enclave](https://img.shields.io/badge/Security-Hardware%20Enclave%20%2F%20TEE-purple.svg)](#hardware-backed-protection)
</div>

> **fONE** is a high-security, non-custodial mobile wallet and decentralized super-app built specifically for the **XRP Ledger (XRPL)**. Designed for speed, security, and everyday utility, fONE combines institutional-grade hardware key protection with native DEX & AMM trading, XLS-20 NFT audio & visual media playback, private on-chain messaging, and a 21-application decentralized ecosystem hub.

---

## Table of Contents
1. [Overview & Core Mission](#overview--core-mission)
2. [Security & Privacy Model](#security--privacy-model)
3. [Key Features & Capabilities](#key-features--capabilities)
4. [The 21 Native fApps Ecosystem](#the-21-native-fapps-ecosystem)
5. [Understanding the XRP Ledger](#understanding-the-xrp-ledger)
6. [Supported Account Formats & Standards](#supported-account-formats--standards)
7. [Installation & Getting Started](#installation--getting-started)
8. [Consumer Safety & Best Practices](#consumer-safety--best-practices)
9. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)
10. [Legal Disclaimer & Consumer Notice](#legal-disclaimer--consumer-notice)

---

## Overview & Core Mission

The XRP Ledger is one of the fastest, most scalable, and lowest-cost blockchains in existence, settling transactions in 3–5 seconds with near-zero energy consumption. 

**fONE** brings the full power of the XRP Ledger to your mobile device without compromising on privacy, self-sovereignty, or security. Unlike custodial applications where a third party holds your funds, fONE is **100% non-custodial**: your keys never leave your phone, and all operations settle directly on the decentralized ledger.

### Version Metadata
| Property | Detail |
| :--- | :--- |
| **Application Name** | `fONE` (FLIPPRX Mobile) |
| **Current Build** | `Beta v1.0.0` |
| **Release Status** | **Beta Testing** — Coming soon to Google Play Store & iOS App Store |
| **Official Download** | [https://flipprx.one/fone](https://flipprx.one/fone) |
| **Package / Bundle ID** | `one.flipprx.wallet` |
| **Target Platforms** | Android (API 24+) & iOS (15.0+) |
| **Deep Link URI Schemes** | `fone://`, `flipprx://` |
| **Primary Ledger** | XRP Ledger Mainnet (`s2.ripple.com`, `s1.ripple.com`, `xrplcluster.com`, `xrpl.ws`) |
| **Custody Model** | Self-Custodial / Non-Custodial |

---

## Security & Privacy Model

fONE is built from the ground up to protect your digital assets against physical extraction, remote compromise, and accidental loss.

### Hardware-Backed Protection
* **Apple Secure Enclave (iOS):** Your cryptographic keys are isolated inside Apple's dedicated hardware security chip (`WHEN_UNLOCKED_THIS_DEVICE_ONLY`), immune to operating system exploits or cloud backups.
* **Android StrongBox & TEE Keymaster (Android):** Utilizes hardware-isolated Trusted Execution Environments (TEE) and dedicated Secure Elements for all key storage and signing operations.
* **Zero Cloud Exposure:** Your seed phrases, secret numbers, and private keys are never transmitted over the internet, never backed up to iCloud or Google Drive, and never visible to FLIPPRX or any third party.

### Biometric Authentication & Session Security
* **Class 3 Hardware Biometrics:** Supports Face ID, Touch ID, and Android BiometricPrompt (Fingerprint/Face) to authorize payments, swaps, and confidential settings.
* **Salted PIN Fallback:** A dedicated 6-digit salted keypad fallback with progressive lockouts after failed attempts.
* **Auto-Lock & Memory Scrubbing:** The moment fONE transitions to the background or your device screen locks, active session buffers in volatile memory are immediately wiped, requiring biometric re-authentication to re-enter.

### Zero-Telemetry Privacy Policy
* **No User Accounts:** No email, phone number, or personal identity verification (KYC) is required to use fONE.
* **No Activity Tracking:** fONE does not log your IP address, balance history, or transaction destinations. Communication occurs via direct peer-to-peer WebSocket streams to decentralized XRPL validator nodes.

---

## Key Features & Capabilities

```
┌────────────────────────────────────────────────────────────────────────┐
│                        fONE MOBILE WALLET                             │
├────────────────────┬────────────────────┬──────────────────────────────┤
│  PORTFOLIO & ASSETS│    DEX & AMM SWAP  │   XLS-20 NFTS & AUDIO MEDIA  │
│  • Spendable vs.   │  • Instant Native  │   • Visual NFT Gallery       │
│    Reserved XRP    │    Liquidity Swaps │   • Embedded Music Player    │
│  • Token Portfolios│  • Custom Slippage │   • 1-Tap Gifting / Listing  │
│  • Live Fiat Feeds │  • Trustline Setup │   • Rarity & Trait Inspector │
├────────────────────┴────────────────────┴──────────────────────────────┤
│  MIMO: On-Chain Encrypted P2P Messaging (Zero Centralized Servers)     │
├────────────────────────────────────────────────────────────────────────┤
│  21 NATIVE fAPPS (Bridge, POS, Escrows, Checks, Order Books & More)   │
└────────────────────────────────────────────────────────────────────────┘
```

### 1. Smart Portfolio & Balance Transparency
* **True Balance Breakdown:** View your total balance alongside a clear distinction between **Spendable XRP** and **Locked Reserves** (Base Reserve + Owner Reserves), ensuring you never get surprised by on-chain reserve rules.
* **Issued Token Portfolios:** Real-time tracking of native XRPL tokens (such as FLIPPRX, RLUSD, MFLIP, ECP, JNT, FORKDAO, and custom tokens).
* **Live Market Conversions:** Real-time multi-currency valuations and market trends cached with 0ms latency on navigation.

### 2. Native XRPL DEX & AMM Swaps
* **Zero Middleman Swaps:** Execute decentralized token swaps directly through the XRP Ledger's native Automated Market Maker (AMM) pools and central limit order books.
* **Configurable Slippage Tolerance:** Adjust slippage parameters (0.5% to 5%) to protect against market volatility during active trading.
* **1-Tap Trustline Manager:** Add verified ecosystem token trustlines in one click, or safely remove zero-balance lines to reclaim reserved XRP back into your spendable balance.

### 3. XLS-20 NFT Suite & Web3 Music Player
* **Interactive Media Gallery:** High-resolution rendering of XRPL XLS-20 digital collectibles with IPFS gateway failover.
* **Embedded Audio Player:** Stream audio-enabled music NFTs directly inside the app, complete with playback controls, scrubbers, and persistent mini-dock controls.
* **Frictionless Gifting & Trading:** Transfer NFTs to friends with 1-tap zero-cost gifting or list them on the XRPL decentralized marketplace with custom royalties.

### 4. MIMO: On-Chain Encrypted Messaging
* **True Decentralized Chat:** Wallet-to-wallet private messaging transmitted directly across XRPL transaction memos.
* **End-to-End Encryption:** Messages are cryptographically sealed so that only the sender and recipient can decrypt the content.
* **Serverless & Censorship-Resistant:** Operates without centralized chat servers, phone numbers, or cloud databases.

### 5. Multi-Node Resilience Honeycluster
* **Zero-Downtime Connectivity:** Automatic intelligent failover across decentralized mainnet clusters (`s2.ripple.com`, `s1.ripple.com`, `xrplcluster.com`, `xrpl.ws`). If any server experiences network latency or rate limiting, fONE switches seamlessly to the fastest healthy node without interrupting your transaction.

---

## The 21 Native fApps Ecosystem

fONE includes a comprehensive suite of 21 built-in decentralized applications (fApps), providing a complete Web3 utility toolkit directly from your mobile dock:

| # | fApp Name | Category | Consumer Description |
|---|:---|:---|:---|
| 1 | **fBRIDGE** | Cross-Chain | Swap between 3,000+ cryptocurrencies (Bitcoin, Ethereum, Solana, and more) into XRPL assets, plus direct fiat on-ramp support. |
| 2 | **NFT Marketplace** | Collectibles | Browse, buy, and sell verified ecosystem digital collectibles and music NFTs on the decentralized ledger. |
| 3 | **Visual Limit Orders** | Trading | View real-time order book depth charts, bid/ask spreads, and place or cancel native DEX limit orders. |
| 4 | **LP Trading** | Yield & Liquidity | Provide liquidity to automated market maker (AMM) pools and manage your pool share deposits and withdrawals. |
| 5 | **Merchant POS** | Commerce | Turn your phone into a crypto Point-of-Sale terminal with live QR generation and instant on-chain payment detection. |
| 6 | **Escrow Manager** | Security | Create and manage time-locked or conditional escrows for deferred payments and milestone releases. |
| 7 | **XRPL Checks** | Payments | Issue, cash, or void decentralized digital checks that allow recipients to claim funds on their own schedule. |
| 8 | **Recycle & Sweep** | Optimization | Clean micro-dust tokens and close inactive trustlines to instantly reclaim your reserved XRP. |
| 9 | **Ledger Explorer** | Analytics | In-app block and transaction explorer to inspect any wallet address, transaction hash, or memo. |
| 10 | **Address Book** | Usability | Encrypted local contact directory to store verified recipient addresses, nicknames, and required destination tags. |
| 11 | **Proof of Flip** | Community | Verify your wallet's eligibility for community airdrops, rewards, and ecosystem snapshot allocations. |
| 12 | **Secure Notes** | Privacy | Encrypted offline personal notes vault protected directly by your device's hardware security chip. |
| 13 | **Price Converter** | Tools | Real-time multi-currency calculator spanning XRP, ecosystem tokens, top crypto assets, and major world currencies. |
| 14 | **Ledger Stats** | Analytics | Monitor macro network performance, live transactions-per-second (TPS), and validated ledger sequences. |
| 15 | **Domains Manager** | Identity | Manage on-chain account domains and verify `xrp-ledger.toml` project credentials. |
| 16 | **Wallet Guard** | Security | On-chain security posture auditor that checks your account key configurations, multi-signing setups, and permissions. |
| 17 | **Audits & Enclave** | Security | Hardware security verification tool that displays your phone's biometric readiness and cryptographic isolation status. |
| 18 | **fMUSIC & Radio** | Entertainment | Stream curated community tracks and live digital radio stations from over 100 countries in the background. |
| 19 | **Bonuses & Perks** | Rewards | Redeem ecosystem promo codes to unlock exclusive community benefits, VIP perks, and feature access. |
| 20 | **Burner Terminal** | Hygiene | Safely dispose of unsolicited spam tokens and airdrops by sending them to the verified ledger blackhole. |
| 21 | **Help & Support** | Assistance | In-app knowledge base, device diagnostic logs, and direct access to official support channels. |

---

## Understanding the XRP Ledger

To ensure a seamless user experience, consumers should be familiar with the fundamental rules of the XRP Ledger:

### 1. The Base Reserve (Account Activation)
* Every new wallet on the XRP Ledger requires a **Base Reserve** (currently **1.0 XRP**) to activate and exist on the ledger.
* This is a protocol-level requirement of the decentralized XRP Ledger network (not a fee charged by fONE).
* Your first deposit to a new wallet must be at least 1.0 XRP to activate the address. This 1.0 XRP remains locked on-ledger to prevent spam accounts and can be reclaimed if the account is ever deleted.

### 2. Owner Reserves (Trustlines, NFTs, & Offers)
* For every object you hold on the ledger—such as an active token **trustline**, an **open limit order**, or a **held escrow**—the ledger temporarily locks an **Owner Reserve** of **0.2 XRP**.
* **Owner reserves are never lost:** As soon as you remove a trustline with a zero balance or cancel an open order, that 0.2 XRP is immediately unlocked and returned to your spendable balance.
* Use the built-in **Recycle fApp** to quickly identify and remove empty trustlines to reclaim your XRP.

### 3. Destination Tags (Critical for Exchanges)
* **What is a Destination Tag?** A destination tag is a numerical ID (e.g., `10023491`) used by centralized exchanges to identify which customer account a deposit belongs to, since exchanges share one main deposit address.
* **Sending to an Exchange (Coinbase, Binance, Kraken, etc.):** You **MUST** include the Destination Tag provided by the exchange, or your deposit may be delayed or lost.
* **Sending to a Personal Wallet (like fONE):** Personal self-custody wallets do **NOT** require a destination tag unless the recipient specifically requests one.

---

## Supported Account Formats & Standards

fONE provides universal cross-wallet compatibility, allowing you to create a brand-new wallet or import an existing XRPL account from any major wallet:

1. **BIP-39 Mnemonic Recovery Phrases (12 or 24 Words):**
   * Standardized English word recovery phrases derived along the standard XRPL path (`m/44'/144'/0'/0/0`).
2. **XRPL Family Seeds (`s...`):**
   * Traditional base58 secret seeds starting with `s` (supporting both standard `secp256k1` and high-speed `ed25519` key algorithms).
3. **Xaman (Xumm) Secret Numbers:**
   * Standard 8 groups of 6 numeric digits (48 digits total) used widely across the XRPL ecosystem.
4. **Multi-Account Switching:**
   * Manage multiple wallets independently within fONE with custom nicknames, separate balances, and instant 1-tap switching.

---

## Installation & Getting Started

### Official Download Portal & App Store Availability
> [!TIP]
> 📲 **Download the Latest Beta:** The official Android Beta APK is live and available directly at **[https://flipprx.one/fone](https://flipprx.one/fone)**.

> [!NOTE]
> **Store Availability:** fONE is currently in **Beta v1.0.0**. We have not yet launched on public app stores. Official availability on both the **Google Play Store** and **Apple iOS App Store** is **Coming Soon**!
>
> * **Android Beta:** Available directly via standalone APK download at [flipprx.one/fone](https://flipprx.one/fone) (compatible with Android 7.0+).
> * **iOS Beta:** Apple TestFlight testing and App Store release will open upon conclusion of the initial beta review cycle (compatible with iOS 15.0+).

### First-Time Setup Walkthrough
1. **Launch fONE:** On cold boot, choose **Create New Wallet** or **Import Existing Wallet**.
2. **Back Up Your Recovery Credentials:** 
   * If creating a new account, write down your 12/24-word recovery phrase on physical paper.
   * **Never take a screenshot** or save your phrase in an unencrypted cloud note.
3. **Configure Biometrics & Passcode:**
   * Enable Face ID, Touch ID, or Fingerprint authentication for seamless, secure approvals.
   * Set a 6-digit backup PIN.
4. **Fund Your Account:**
   * Tap **Receive** on the main dashboard to display your public XRPL address and QR code.
   * Transfer at least 1.0 XRP from an exchange or existing wallet to activate your new account.
5. **Explore & Transact:**
   * You are now ready to send payments, trade on the DEX, explore the 21 fApps, and listen to music NFTs!

---

## Consumer Safety & Best Practices

Self-custody grants you complete financial freedom, which also means personal responsibility over your security. Follow these golden rules:

> [!CAUTION]
> **NEVER SHARE YOUR RECOVERY PHRASE OR SECRET NUMBERS.**
> No legitimate administrator, developer, or support staff member from FLIPPRX or any other project will EVER ask for your seed phrase or private keys. If anyone asks for them, they are attempting to steal your assets.

* **Store Keys Offline:** Keep physical, handwritten copies of your secret keys in a secure, fireproof location.
* **Verify Counterparty Addresses:** Always double-check the recipient address before hitting confirm. On-chain transactions on the XRP Ledger are final and irreversible.
* **Mind Destination Tags:** When sending funds to centralized exchanges, always ensure you copy and paste the correct Destination Tag.
* **Beware of Phishing:** Only download official fONE releases from verified channels, and never enter your secret phrase into any website or Discord/Telegram bot.

---

## Frequently Asked Questions (FAQ)

#### Q: What happens if I lose my phone?
**A:** Because fONE is self-custodial, your funds are safely recorded on the XRP Ledger blockchain—not on your physical device. As long as you have your 12/24-word recovery phrase or secret numbers, you can reinstall fONE (or any compatible XRPL wallet) on a new device and immediately restore full access to all your funds.

#### Q: Can FLIPPRX freeze my funds or reverse a transaction?
**A:** No. FLIPPRX has no administrative access, backdoor, or custody over your account. Transactions are processed directly by decentralized XRP Ledger validators according to open consensus rules.

#### Q: Why is a small amount of my XRP listed as "Reserved"?
**A:** This is a fundamental rule of the XRP Ledger protocol designed to keep the network free of spam. Every active account reserves 1.0 XRP, plus 0.2 XRP for each active trustline, open order, or escrow. As soon as you close an order or delete an empty trustline, the reserved XRP is unlocked and returned to your spendable balance.

#### Q: How do fees work on the XRP Ledger?
**A:** Standard transaction fees on the XRPL are fractions of a cent (typically around 0.000012 XRP), settling within 3–5 seconds.

#### Q: How do I contact official support?
**A:** For non-sensitive troubleshooting and assistance, use the built-in **Help & Support fApp** or reach out via official project channels. Remember: support will never request your secret recovery phrase.

---

## Legal Disclaimer & Consumer Notice

* **Self-Custodial Software:** fONE is provided as client-side software interface to the public, decentralized XRP Ledger. FLIPPRX does not act as a custodian, broker, or financial intermediary.
* **Cryptographic Asset Risk:** Cryptocurrency trading, liquidity provision, and digital asset ownership involve inherent market risk. Always exercise caution, maintain adequate backups, and verify transaction parameters before executing on-chain actions.
* **Open Network:** All transaction settlements and smart utilities are executed by independent, distributed XRPL validators across the globe.
