<div align="center">

# Abstraxn

**Identity, wallets, payments, and policy. One SDK for autonomous agents.**

[![npm version](https://img.shields.io/npm/v/@abstraxn/agent-kit.svg?color=3ECF8E&label=%40abstraxn%2Fagent-kit)](https://www.npmjs.com/package/@abstraxn/agent-kit)
[![License: MIT](https://img.shields.io/badge/license-MIT-3ECF8E.svg)](https://opensource.org/licenses/MIT)
[![Docs](https://img.shields.io/badge/docs-docs.abstraxn.com-3ECF8E)](https://docs.abstraxn.com/)
[![Built on](https://img.shields.io/badge/built%20on-EVM%20%C2%B7%20ERC--4337-0f172a)](https://docs.abstraxn.com/guides/getting-started/supported-chains)
[![Status](https://img.shields.io/badge/status-live-d97706)](https://abstraxn.com/)
[![Follow on X](https://img.shields.io/twitter/follow/AbstraxnX?style=social)](https://x.com/AbstraxnX)

[Website](https://abstraxn.com/) · [Dashboard](https://dashboard.abstraxn.com/) · [Docs](https://docs.abstraxn.com/) · [Demo](https://demo.abstraxn.com/) · [Agent Hub](https://agent.abstraxn.com/) · [Blogs](https://abstraxn.com/blogs)

</div>

---

Abstraxn is a modular, chain-agnostic infrastructure layer that lets AI agents hold an identity, control a wallet, pay for services, and operate inside enforceable guardrails. Infrastructure, not application. Chain-agnostic, token-agnostic, custodian-neutral.

Agent frameworks solved reasoning. They did not solve action. Abstraxn is the layer beneath the agent that supplies identity, wallet, payments, and policy through a single SDK and dashboard.

---

## The Four Powers

| Power | Standard / Rail | Status |
| :--- | :--- | :--- |
| **Identity** | ERC-8004 | Live |
| **Wallet** | ERC-4337, EIP-7702 (Abstraxn WaaS) | Live |
| **Payments** | x402, MPP | Live |
| **Policy** | Enforcement at the signing layer | Live (core controls); broader guardrails in development |

**Identity** gives agents a resolvable, on-chain identity counterparties can verify before transacting.

**Wallet** provisions ERC-4337 smart accounts per user and per agent. Passkey and social recovery, no seed phrases, one address across supported EVM chains.

**Payments** covers HTTP-native machine payments via x402 across 50+ pre-integrated services, plus MPP settlement. USDC is the best-supported path, not a hardcoded default.

**Policy** enforces address allowlists, denylists, and per-transaction limits at signing time.

---

## Supporting Infrastructure

Bundler, Paymaster, Relayer, and a catalog of 50+ MCP integrations for data, browser automation, comms, and tooling. 100+ EVM-compatible chains. Primary production targets: Ethereum, Base, Arbitrum, Polygon.

---

## SDKs

| Package | Description |
| :--- | :--- |
| [`@abstraxn/agent-kit`](https://www.npmjs.com/package/@abstraxn/agent-kit) | Agent Kit: identity, wallets, x402 payments, and MCP tools |
| [`@abstraxn/server-signer`](https://www.npmjs.com/package/@abstraxn/server-signer) | Server-side wallet signing for backend integrations |
| [`@abstraxn/signer-react`](https://www.npmjs.com/package/@abstraxn/signer-react) | React components and hooks for embedded wallets |
| [`@abstraxn/relayer`](https://www.npmjs.com/package/@abstraxn/relayer) | EVM relayer for gasless and relayed transactions |
| [`@abstraxn/solana-relayer`](https://www.npmjs.com/package/@abstraxn/solana-relayer) | Solana transaction build, sign, and relay |
| [`@abstraxn/cli`](https://www.npmjs.com/package/@abstraxn/cli) | CLI for Agent Kit MCP, agents, and Web3 tooling |

---

## Get involved

- Read the [Getting Started guide](https://docs.abstraxn.com/guides/getting-started)
- Explore the [Agent Kit overview](https://docs.abstraxn.com/guides/ai/agent-kit-overview)
- [Start a 30-day free trial](https://abstraxn.com/) or open the [Dashboard](https://dashboard.abstraxn.com/)
- Try the [demo](https://demo.abstraxn.com/) or manage agents in [Agent Hub](https://agent.abstraxn.com/)
- Follow [@AbstraxnX](https://x.com/AbstraxnX) · [LinkedIn](https://www.linkedin.com/company/102879467/) · [Blog](https://abstraxn.com/blogs)

---

<div align="center">

**Superpowering the agent economy.**

© Abstraxn · [Terms](https://abstraxn.com/terms-of-service) · [Privacy](https://abstraxn.com/privacy-policy) · [X](https://x.com/AbstraxnX) · [LinkedIn](https://www.linkedin.com/company/102879467/)

</div>
