# KINHEX

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Solana](https://img.shields.io/badge/Solana-Web3-green.svg)](https://solana.com/)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/ontora-ai.svg)](https://github.com/yourusername/ontora-ai/issues)

[![Website](https://img.shields.io/badge/Website-KINHEX-blue?logo=google-chrome)](https://kinhex.run/)
[![Twitter](https://img.shields.io/badge/Twitter-KINHEX-blue?logo=twitter)](https://x.com/KINHEXLABS)

# Kinhex — Gesture-Based On-Chain Interaction Protocol

Kinhex transforms natural hand motion into blockchain commands.  
No clicks, no buttons — every gesture becomes on-chain execution.

---

## 🚀 What is Kinhex
Kinhex is an interaction protocol that allows users to perform on-chain actions through hand gestures tracked in real time.  
The protocol replaces traditional UI interactions with motion, enabling minting, swapping, voting, claiming, and more — all triggered by gestures.

---

## 🔄 How It Works
1. The camera detects hand movement and recognizes the gesture locally.
2. The gesture is converted into a cryptographic command mapped to an on-chain action.
3. The wallet signs and the blockchain completes execution — motion becomes command.

---

## ✨ Features
- Gesture-first Web3 interaction  
- Local hand-tracking (no video uploaded or stored)  
- Wallet signing preserved for full security  
- Works with standard webcams and phone cameras  
- Lightweight SDK for developers  
- Native Solana support, with multi-chain expansion planned

---

## 📦 Installation (SDK)
```bash
npm install @kinhex/sdk
```

---

## 🧩 Basic Usage
```
import { Kinhex } from "@kinhex/sdk";

const kinhex = new Kinhex();

kinhex.onGesture("PINCH", () => mintNFT());
kinhex.onGesture("FIST", () => vote(proposalId));
kinhex.onGesture("WAVE", () => swap(tokenA, tokenB));
```

---

## 📁 Folder Structure

```
/sdk
  core
  gestures
  mapping
  utils
/demo
  basic-mint-example
  gesture-swap
  livestream-demo
```

```
Kinhex does not bypass wallet permissions.
Every interaction still requires approval through the wallet signing flow.
Gesture recognition runs locally to ensure privacy and safety.
```



