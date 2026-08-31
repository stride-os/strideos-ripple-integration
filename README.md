# STRIDE OS - Ripple Integration Services

**Making Stablecoins Bankable.**

STRIDE OS is an orchestration middleware layer that enables regulated banks and financial service providers to accept, redeem, and settle regulated stablecoins — compliantly, and without rebuilding their core infrastructure.

---

## About This Repository

This repository contains the microservices within STRIDE OS that interface with Ripple's product suite. Integrations may include Ripple WaaS, Ripple Mint, Ripple Custody, Ripple Payments, and Ripple Prime, depending on the requirements of each bank deployment.

It is being shared as part of STRIDE's participation in the **Ripple x Brinc Hong Kong Fintech Innovation Programme (HFIP)**.

---

## Overview

STRIDE OS sits between a bank's existing core systems and the ecosystem of services required to support regulated stablecoin operations: custody and wallet providers, on-chain analytics, travel rule and AML compliance tools, and stablecoin issuers and redemption systems.

Banks connect once to STRIDE OS. STRIDE OS manages everything else.

This model — which we call **Dual-Rail Banking** — allows banks to run fiat and stablecoin rails in parallel, giving their customers access to regulated stablecoins through the interfaces they already use, with no change to how the bank's core systems operate.

---

## Ripple Integration Scope

The following Ripple products and services are within scope for integration, subject to bank requirements and deployment configuration.

| Ripple Product | Potential Role in STRIDE OS |
|---|---|
| Ripple WaaS | Customer-facing wallet provisioning and RLUSD transaction management |
| Ripple Mint | RLUSD issuance and redemption via API |
| Ripple Custody | Institutional reserve management and XRP gas automation |
| Ripple Payments | Cross-border payment routing across 60+ corridors |
| Ripple Prime | Initial RLUSD reserve acquisition and XRP sourcing via OTC |

---

## Status

Source code will be added to this repository as development progresses.

For partnership enquiries or integration discussions, please contact us at [contact@stride.sc](mailto:contact@stride.sc) or visit [stride.sc](https://stride.sc).

---

*STRIDE OS is developed and maintained by STRIDE OS LIMITED, incorporated in Hong Kong.*
