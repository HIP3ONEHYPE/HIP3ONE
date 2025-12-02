# VEEPAY

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Solana](https://img.shields.io/badge/Solana-Web3-green.svg)](https://solana.com/)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/ontora-ai.svg)](https://github.com/yourusername/ontora-ai/issues)

[![Website](https://img.shields.io/badge/Website-VEEPAY-blue?logo=google-chrome)](https://veepay.life/)
[![Twitter](https://img.shields.io/badge/Twitter-VEEPAY-blue?logo=twitter)](https://x.com/VEEPAYONX)

# VEEPAY — The First x402-Enabled MCP Server on Solana

**VEEPAY** is a next-generation infrastructure that allows autonomous AI agents to **pay on-chain, gain permissions, and execute real transactions on Solana** via a secure x402 endpoint.  
It transforms blockchain access from uncontrolled execution into a **verifiable, pay-per-action, auditable automation layer**.

---

## 🚀 What VEEPAY Enables
AI agents can:
- Pay using SOL or USDC
- Unlock MCP capabilities through x402 payment validation
- Simulate and execute on-chain actions
- Leave a full audit trail for every operation

In short — **agents no longer request access; they earn it through payment.**

---

## 🧠 Core Architecture
VEEPAY is built on five integrated layers:

| Layer | Description |
|-------|-------------|
| x402 Payment Gateway | Pay-to-access authentication using Solana payments |
| MCP Server Layer | Exposes controlled blockchain tools such as `getBalance`, `simulateTx`, `submitTx` |
| Solana Execution Engine | Builds, simulates, and broadcasts real transactions |
| Policy & Security Core | Enforces agent permissions, spending limits, and key protection |
| Observability & Audit Layer | Logs and hashes every action for replayable transparency |

---

## ⚙️ Key Features
- x402-based on-chain authentication  
- Full MCP compatibility for AI tool calling  
- Short-lived access tokens with scope control  
- Transaction simulation before execution  
- Rate limiting, spend limits, and action policies  
- Complete audit log and replayable proofs

---

## 🪙 How It Works (Lifecycle)
1. The agent requests access → receives a `402 Payment Required` response  
2. The agent pays on-chain using SOL/USDC  
3. VEEPAY verifies the payment and issues a short-lived token  
4. The agent calls MCP tools (read / simulate / execute)  
5. All actions and transactions are logged and hashed for auditing

**Pay → Verify → Execute → Record**

---

## 🔒 Security Model
- Wallet-signature identity validation  
- KMS/HSM integration for key safety (no exposed signing keys)  
- Log hashing for tamper-proof auditing  
- Per-agent policies: spend caps, tool permissions, and rate limits  
- Protection against replay attacks and uncontrolled execution

---

## 📦 Recommended Stack
- **Backend:** Rust / Node.js / Python (flexible)  
- **Blockchain:** Solana + Anchor Framework  
- **Storage:** PostgreSQL + Redis  
- **Security:** KMS or HSM for signing logic  
- **Monitoring:** Prometheus + Grafana + Loki/ELK  

---

## 📌 Status
VEEPAY is under active development and progressive open-sourcing.  
The dashboard for users with limited coding experience is **coming soon** and will be updated on the website.

---

## 📄 License
VEEPAY is an open infrastructure project.  
Contributions, forks, and audits are welcome.

---

### 🔥 Tagline
**Pay. Verify. Execute.  
VEEPAY makes Solana truly machine-accessible.**
