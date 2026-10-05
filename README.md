# 🆔 Awesome Decentralized Identity & Verifiable Credentials 🔐

![Awesome Decentralized Identity Banner](assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials?style=flat-square" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials?style=flat-square" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 📌 Overview & SEO Summary 🚀

A comprehensive, curated directory of **Self-Sovereign Identity (SSI)** solutions, **W3C Verifiable Credentials (VC)** software, **Decentralized Identifiers (DIDs)**, **OpenID for Verifiable Credentials (OID4VC)**, **SD-JWT**, and digital wallet platforms. This list empowers developers, enterprise security architects, and identity professionals to choose the best open-source identity tools and commercial SaaS platforms for modern zero-trust verification and user-controlled data privacy.

---

## 📖 Table of Contents 📑

- [☁️ SaaS & Hosted Platforms](#️-saas--hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [❤️ Support & Sponsorship](#-support--sponsorship)
- [📊 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## ☁️ SaaS & Hosted Platforms 🌐

> **📊 Sector Market Size & Dynamics**: The global decentralized identity market is estimated at **~$2.5 Billion in 2026** and projected to reach **~$12.0 Billion by 2032** (CAGR ~30%). The market is currently **moderately fragmented**; while tech giants like Microsoft offer enterprise distribution (Microsoft Entra Verified ID), specialized identity providers (Trinsic, Dock, SpruceID, cheqd, walt.id) maintain strong developer footholds across specific identity protocols, zero-knowledge proofs, and sovereign credential wallet ecosystems. No single provider dominates a winner-take-all landscape.

The table below lists key SaaS identity providers sorted in descending order by enterprise size, annual revenue, or total funding valuation:

| Company / Product 🏢 | Product Description 📝 | Pricing (Starting Paid Tier) 💰 | Free Tier / Free Trial Limits 🆓 | Company Size / Valuation 📈 |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Entra Verified ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-verified-id)** 🟦 | Decentralized identity service integrated with Microsoft Entra ID. Issues & verifies W3C VCs with Face Check biometric liveness verification. | **Face Check**: $0.45 per verification transaction; Enterprise EA custom volume tiers. | **Free Issuance & Basic Verification**: Included with standard Azure AD / Entra ID free accounts. Face Check has no free monthly tier. | **~$281B Annual Revenue** (Microsoft Corp Parent) |
| **[Evernym / Avast](https://www.evernym.com/)** 🛡️ | Enterprise SSI platform pioneer; creator of Sovrin network tools & mobile wallet infrastructure. | **Custom Enterprise Plan**: Quote required; baseline setup starts at ~$1,500/month. | **30-Day Free Trial**: Sandbox environment access with up to 100 test credential issuances. | **~$900M Revenue** (Avast / Gen Digital Parent) |
| **[SpruceID](https://www.spruceid.com/)** 🌲 | Toolkit provider for decentralized identity, Tezos/Ethereum DID resolution, and verifiable enterprise credentials. | **Developer Pro**: $250/month; Enterprise custom SLAs available. | **Free Developer Sandbox**: Up to 500 credential verifications/month on testnet networks. | **$41.8M Total Raised** (Series A Funding) |
| **[walt.id Managed SaaS](https://walt.id/)** 🆔 | Managed cloud platform providing Issuer, Verifier, and Wallet APIs for SD-JWT, W3C VC, and mDL ISO 18013-5 formats. | **Cloud Pro**: €2,500/month; Managed Enterprise custom quotes. | **14-Day Free SaaS Trial**: Full access to cloud APIs and admin portal; unlimited community open-source self-hosting. | **Private / VC-Backed** (Leading European Identity Provider) |
| **[Dock](https://www.dock.io/)** ⚓ | Blockchain-anchored verifiable credential platform for instant verification, issuing, and digital certificates. | **Standard Plan**: $350/month; Premium Plan: $1,000/month. | **Free Tier**: 50 credential workspaces and up to 100 verifications forever without credit card. | **Private / Tokenized Platform** (Dock Network) |
| **[Trinsic](https://trinsic.id/)** ⚡ | Developer infrastructure and SDKs for issuing verifiable credentials, passkeys, and digital identity wallets. | **Build Plan**: $99/month; Growth Plan: $499/month. | **Free Developer Plan**: Up to 100 active credentials and 1,000 verification API calls/month. | **Private / Y Combinator Backed** |
| **[cheqd](https://cheqd.io/)** 🪙 | Decentralized identity network for issuing credentials with built-in trust payment and monetization rails. | **cheqd Studio Build**: $50/month; Grow Plan: $200/month; On-chain DID creation: ~$2.00/write. | **3-Month Free Trial**: Full cheqd Studio SaaS access; testnet identity creation is 100% free. | **Private Network** (CHEQ Token Infrastructure) |
| **[Indicio](https://indicio.tech/)** ✈️ | Enterprise SSI infrastructure & Indicio Proven suite powering decentralized travel, healthcare, and government identity. | **Indicio Mainnet Node Subscription**: ~$5,000/year; Custom Cloud SaaS tier. | **14-Day Enterprise Demo**: Access to Indicio Testnet and Proven Mobile Wallet sandbox. | **Private / Backed by SITA & NEC X** |
| **[Privado ID](https://privado.id/)** 🔐 | Zero-knowledge identity protocol (formerly Iden3) leveraging Circom ZK proofs for absolute data minimization. | **Enterprise Node SaaS**: $300/month for managed ZK issuer nodes. | **100% Free Open-Source Protocol**: Free self-sovereign mobile wallet app and local verification SDKs. | **Private Protocol / Polygon Ecosystem Spin-off** |
| **[Mattr](https://mattr.global/)** 🌐 | Verifiable data platform providing cloud APIs and digital wallet SDKs for decentralized identity workflows. | **Mattr VII Starter**: $450/month; Enterprise custom licensing. | **30-Day Developer Trial**: Sandbox cloud tenant with up to 250 credential issuances. | **Private Identity Platform** |

---

## 🔓 Open-Source GitHub Projects 🛠️

Below is a curated collection of production-grade open-source libraries, SDKs, and platforms for Decentralized Identity and Verifiable Credentials, sorted by GitHub Stars_Counts in descending order:

| Open-Source Project 📦 | Description & Capabilities 💡 | GitHub_Stars ⭐ |
| :--- | :--- | :--- |
| **[hyperledger/aries](https://github.com/hyperledger/aries)** 🏛️ | Infrastructure for blockchain-rooted, peer-to-peer decentralized identity, credential exchange (Issue Credential / Present Proof), and secure messaging protocols. | [![Stars](https://img.shields.io/github/stars/hyperledger/aries?style=social&color=white)](https://github.com/hyperledger/aries/stargazers) |
| **[uport-project/veramo](https://github.com/uport-project/veramo)** 🦁 | Modular JavaScript/TypeScript framework for verifiable data, W3C DIDs, and Verifiable Credentials. Successor to uPort, supporting KMS and multi-DID drivers. | [![Stars](https://img.shields.io/github/stars/uport-project/veramo?style=social&color=white)](https://github.com/uport-project/veramo/stargazers) |
| **[spruceid/didkit](https://github.com/spruceid/didkit)** 🛠️ | Cross-platform Rust toolkit & SDKs (FFI bindings for Android, iOS, WASM) for issuing, presenting, and verifying W3C DIDs and Verifiable Credentials. | [![Stars](https://img.shields.io/github/stars/spruceid/didkit?style=social&color=white)](https://github.com/spruceid/didkit/stargazers) |
| **[walt-id/waltid-identity-monorepo](https://github.com/walt-id/waltid-identity-monorepo)** 🆔 | Comprehensive Kotlin/Java/TypeScript stack for Decentralized Identity & Wallets. Supports OID4VC, SD-JWT VC, W3C VCs, and mDL ISO 18013-5 standards. | [![Stars](https://img.shields.io/github/stars/walt-id/waltid-identity-monorepo?style=social&color=white)](https://github.com/walt-id/waltid-identity-monorepo/stargazers) |
| **[decentralized-identity/did-core-specs](https://github.com/decentralized-identity/did-core-specs)** 📜 | W3C Decentralized Identifiers (DIDs) v1.0 core architecture, data model, and specification repositories managed by DIF. | [![Stars](https://img.shields.io/github/stars/decentralized-identity/did-core-specs?style=social&color=white)](https://github.com/decentralized-identity/did-core-specs/stargazers) |
| **[Sphereon-Opensource/SIOP-OID4VP](https://github.com/Sphereon-Opensource/SIOP-OID4VP)** 🔄 | OpenID for Verifiable Presentations (OID4VP) & Self-Issued OpenID Provider v2 (SIOPv2) TypeScript library for verifiers and wallet holders. | [![Stars](https://img.shields.io/github/stars/Sphereon-Opensource/SIOP-OID4VP?style=social&color=white)](https://github.com/Sphereon-Opensource/SIOP-OID4VP/stargazers) |
| **[Sphereon-Opensource/OID4VC](https://github.com/Sphereon-Opensource/OID4VC)** 📜 | OpenID for Verifiable Credential Issuance (OID4VCI) & Presentation modules implementing latest OpenID Foundation specifications. | [![Stars](https://img.shields.io/github/stars/Sphereon-Opensource/OID4VC?style=social&color=white)](https://github.com/Sphereon-Opensource/OID4VC/stargazers) |
| **[Sphereon-Opensource/SSI-SDK](https://github.com/Sphereon-Opensource/SSI-SDK)** 🧰 | Modular TypeScript Self-Sovereign Identity SDK supporting key management, DID resolution, W3C credentials, and wallet capabilities. | [![Stars](https://img.shields.io/github/stars/Sphereon-Opensource/SSI-SDK?style=social&color=white)](https://github.com/Sphereon-Opensource/SSI-SDK/stargazers) |
| **[trustbloc/vcs](https://github.com/trustbloc/vcs)** 🔒 | High-performance Go implementation of Verifiable Credential Service APIs for issuer and verifier roles supporting OID4VCI and OID4VP. | [![Stars](https://img.shields.io/github/stars/trustbloc/vcs?style=social&color=white)](https://github.com/trustbloc/vcs/stargazers) |
| **[animo/paradym-wallet](https://github.com/animo/paradym-wallet)** 📱 | Open-source mobile digital identity wallet built with React Native for holding and presenting W3C Verifiable Credentials and OpenID credentials. | [![Stars](https://img.shields.io/github/stars/animo/paradym-wallet?style=social&color=white)](https://github.com/animo/paradym-wallet/stargazers) |

---

## 🤝 How to Contribute 🛠️

Contributions are welcome and greatly appreciated! 💖

1. **Fork** the repository.
2. Create your feature branch (`git checkout -b feature/amazing-identity-tool`).
3. Add or update entries in `README.md` following the exact table structure.
4. Ensure factual descriptions, exact starting pricing tiers, explicit free tier/trial limits, and working links.
5. **Commit** your changes (`git commit -m 'Add Amazing Identity Tool'`).
6. **Push** to the branch (`git push origin feature/amazing-identity-tool`).
7. Open a **Pull Request**.

---

## ❤️ Support & Sponsorship 💖

If this repository helped you discover decentralized identity software, saved research time, or assisted your enterprise implementation, please consider supporting the project:

- 🌟 **Star the repository** to boost visibility on GitHub!
- 🔀 **Fork & Share** with fellow security engineers and SSI developers.
- ☕ **Buy Me a Coffee / Sponsor**: Support ongoing maintenance via [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

---

## 📊 Star History 📈

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Decentralized-Identity-Verifiable-Credentials&type=date&legend=top-left)

---

## ⚠️ Disclaimer 📜

- This repository is a **community-curated directory** provided for educational and informational purposes only.
- Decentralized identity systems handle sensitive identity claims and biometric attributes. Implementers must ensure compliance with regional identity privacy frameworks including **GDPR**, **eIDAS 2.0**, **CCPA**, and **HIPAA**.
- All pricing and free tier/trial details are accurate as of October 2026 based on public vendor specifications, but may change. Always verify terms directly with individual platform providers.

---

<p align="center">
  <b>Maintained by <a href="https://github.com/ishandutta2007">Ishan Dutta</a> and the open-source SSI community.</b>
</p>
