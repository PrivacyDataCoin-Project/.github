<!--
  GitHub organization profile README
  https://github.com/PrivacyDataCoin-Project
  Brand: navy #05060d · blue #1e30f3 · cyan #3bc7ff · pink #e21e80
-->

<div align="center">

  <img src="./banner.png" alt="Privacy Data Coin" width="1280" />

  <br />

  **Private by default.** Wallet transfers hide sender, receiver, amount, and asset type.

  [Website](https://privacydatacoin.com/) ·
  [Docs](https://docs.privacydatacoin.com/) ·
  [Trade](https://trade.privacydatacoin.com/) ·
  [Oracle](https://oracle.privacydatacoin.com/) ·
  [Explorer](https://explorer.privacydatacoin.com/) ·
  [Funding](https://funding.privacydatacoin.com/)

  [![Website](https://img.shields.io/badge/Website-privacydatacoin.com-1e30f3?style=for-the-badge&labelColor=05060d)](https://privacydatacoin.com/)
  [![Docs](https://img.shields.io/badge/Docs-docs.privacydatacoin.com-3bc7ff?style=for-the-badge&labelColor=05060d)](https://docs.privacydatacoin.com/)
  [![Release](https://img.shields.io/github/v/release/PrivacyDataCoin-Project/PDC?style=for-the-badge&label=PDC&color=e21e80&labelColor=05060d)](https://github.com/PrivacyDataCoin-Project/PDC/releases/latest)

</div>

---

## About

Privacy Data Coin (PDC) is a confidential blockchain. Blocks are produced by **RandomARQ** proof of work and **Zarcanum** proof of stake. There is **no premine**. Confidential assets (e.g. BTCX, ARQX) use the same sealed transfer path as native PDC.

This organization holds the protocol, wallet UI, public site, docs, explorer, Companion SDK, tips/funding tools, and the Trade / oracle stack.

## Ecosystem (live)

| Surface | URL |
| --- | --- |
| Website | https://privacydatacoin.com/ |
| Docs | https://docs.privacydatacoin.com/ |
| Trade | https://trade.privacydatacoin.com/ |
| Oracle | https://oracle.privacydatacoin.com/ |
| Explorer | https://explorer.privacydatacoin.com/ |
| Funding | https://funding.privacydatacoin.com/ |

## Public repositories

| Repository | Role |
| --- | --- |
| [PDC](https://github.com/PrivacyDataCoin-Project/PDC) | Protocol, daemon (`pdcd`), CLI wallet (`simplewallet`), desktop app. Branch: `master`. |
| [pdc_ui](https://github.com/PrivacyDataCoin-Project/pdc_ui) | Wallet UI embedded in the desktop application. |
| [PrivacyDataCoin-Project.github.io](https://github.com/PrivacyDataCoin-Project/PrivacyDataCoin-Project.github.io) | Source of [privacydatacoin.com](https://privacydatacoin.com/). |
| [pdcdocs](https://github.com/PrivacyDataCoin-Project/pdcdocs) | English documentation → [docs.privacydatacoin.com](https://docs.privacydatacoin.com/). |
| [pdc-explorer](https://github.com/PrivacyDataCoin-Project/pdc-explorer) | Block explorer → [explorer.privacydatacoin.com](https://explorer.privacydatacoin.com/). |
| [pdc_web3](https://github.com/PrivacyDataCoin-Project/pdc_web3) | TypeScript SDK + **PDC Companion** browser extension. |
| [pdc-funding](https://github.com/PrivacyDataCoin-Project/pdc-funding) | Community funding → [funding.privacydatacoin.com](https://funding.privacydatacoin.com/). |
| [pdc-tipbot](https://github.com/PrivacyDataCoin-Project/pdc-tipbot) | Custodial tip bot (Telegram + Matrix). |
| [RandomARQ](https://github.com/PrivacyDataCoin-Project/RandomARQ) | RandomARQ proof-of-work related code. |

## Trade & oracle stack

Bridgeless Trade (BTCX / ARQX wraps, P2P book) and the signed USD oracle live in this org as dedicated repos (`pdc_trade_frontend`, `pdc_trade_backend`, `oracle`, plus messenger / tip tooling). Some repositories are private; public surfaces are linked in the ecosystem table above.

Current desktop / protocol release: **[latest PDC release](https://github.com/PrivacyDataCoin-Project/PDC/releases/latest)**.

## Lead developer

[ArqTras](https://github.com/ArqTras) leads development. That account can push directly; everyone else contributes through a pull request.

## Build from source

```bash
git clone --recursive https://github.com/PrivacyDataCoin-Project/PDC.git
```

Dependencies and build steps: [PDC README](https://github.com/PrivacyDataCoin-Project/PDC/blob/master/README.md).
