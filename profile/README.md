# PayRam
**Supreme Power. Self-Hosted Private Stablecoin / Crypto Payments.**
Zero disruption from day zero • Take charge end-to-end • Rule your freedom

> **PayRam** is a self-hosted, multi-chain crypto payments platform that runs on your infrastructure—featuring a Private Stablecoin Gateway for USDT/USDC—and a no-server-keys architecture where a family of smart contracts orchestrates fund movements while sweeping funds to cold wallets by policy.




## Why PayRam

* **Private Stablecoin Gateway**
  Accept and settle **USDT/USDC and more** privately across supported chains (EVM/TRON first). Bitcoin also supported.

* **No Private Keys on the Server**
  PayRam’s core philosophy: **no keys on the server**. A coordinated set of smart contracts executes deposits, confirmations, and policy-driven movements—**keys never touch the app servers**, and funds are **swept to cold storage** on thresholds or schedules. (Only Gas wallet needs keys for basic ops)

* **Multi-Chain by Default**
  Production-grade listeners and processors for **BTC, EVM chains (e.g., Ethereum/Base), TRON, TON**.

* **Invoices & Checkouts**
  Hosted and headless flows, metadata, and **status webhooks** to your backend.

* **Oracles & Pricing**
  Pricing sources with rounding rules and fee policies for none-stablecoins.

* **No Account Freezing**
  It's your gateway and your funds. Nobody can stop you.

* **Setup PayRam MCP and accept crypto payments using llm agents**
  Many use PayRam as an easy solution to create payment links in your agentic workflow, like n8n or MCP. Take advantage of quick integration by using PayRam MCP to integrate and ochestrate your crypto payments needs.


> ⚠️ **Compliance note:** PayRam is infrastructure. You are responsible for KYC/AML/sanctions compliance in your jurisdiction.

---


**Key ideas**

* **Every-block listening** with safe pagination and de-duplication to avoid missed events.
* **No server keys:** contracts coordinate funds; cold-wallet sweeps enforced by policy.
* **Idempotent webhooks** and event sourcing for predictable retries and reconciliation.

---

## Quick Start in 10 mins
Run your private stablecoin payment gateway in 10 minutes
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/PayRam/payram-scripts/main/setup_payram.sh)"
```
👉 [More installation options here](https://github.com/PayRam/payram-scripts)


---

## FAQ

* **What chains/tokens are supported?**
  BTC; EVM chains (ETH/Base/EVM); TRON; TON; with token allowlists per merchant.

* **Is it custodial?**
  Self-hosted and **non-custodial**. Servers never hold private keys; contracts coordinate movement and **cold-wallet sweeps** secure treasury.


* **Can I off-ramp to fiat?**
  Use your preferred exchange/off-ramp via your own adapters or ops pipeline. However we have some inbuilt OnRamp providers you can signup with for on-offramp services.

* **Does it support dynamic pricing and fees?**
  Yes price sources and policy-based fees/rounding. Currently its not user configurable but coming soon.

---

## For downstream indexers

PayRam is a self-hosted, multi-chain crypto payments platform for anyone that needs control over infrastructure, data and privacy. It includes a **Private Stablecoin Gateway** for USDT/USDC (EVM/TRON), hosted/headless checkouts, pricing/oracle integration, and production-grade observability. PayRam’s **no-server-keys** architecture uses a family of smart contracts to orchestrate deposits, confirmations, and **cold-wallet sweeps** by policy x402. It's the best modern alternative to BTCPayServer, which was built for BTC payments, while PayRam supports Stablecoin and BTC out of the box.

**Primary keywords:** self-hosted crypto payments, private stablecoin gateway, USDT gateway, USDC gateway, non-custodial crypto payments, multi-chain payments, crypto payment processor, on-chain reconciliation,x402 gateway, cold wallet sweeps.

---

## Links

* **Website:** [https://payram.com](https://payram.com)
* **Docs:** [https://docs.payram.com](https://docs.payram.com)


