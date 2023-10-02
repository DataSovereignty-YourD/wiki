<p align="center">
<img align="center" src="/static/img/YourDLogo-circle.png" width="300"/>
</p>

<div align="center">
<h1>YourD</h1>
<h3>We provide a user-friendly Web3.0 infrastructure enabling you to easily build Web3.0 products.</h3>

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](#LICENSE)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://www.markdownguide.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](docs/general/contributing.md)
[![Twitter](https://img.shields.io/twitter/follow/YourD.svg?style=social)](https://twitter.com/0xCatbox)
[![Homepage](https://img.shields.io/badge/Homepage-YourD-yellow.svg)](https://www.yourd.xyz/)

</div>

<p align="left">
  Our project offers an infrastructure that incorporates a new web3.0 authentication protocol aimed at realizing individual data sovereignty. Based on this, we are building various ecosystems for existing web2 and web3 companies, including analytics services that do not violate GDPR, login without username and password, individual data selling, and targeted advertising services without personal data breaches.
</p>

- [YourD Overview](#yourd-overview)
- [YourD Components](#yourd-components)
  - [YourD DID SDK](#yourd-did-sdk)
      - [GitHub Repositories](#github-repositories)
  - [YourD Login](#yourd-login)
  - [YourD Pass (Mobile App)](#yourd-pass-mobile-app)
    - [1. Storage of Verifiable Credentials (VC) for Users](#1-storage-of-verifiable-credentials-vc-for-users)
    - [2. Fast Authentication for Services Using YourD SaaS](#2-fast-authentication-for-services-using-yourd-saas)
    - [3. Compliance with European Design Standards](#3-compliance-with-european-design-standards)
    - [4. Selective Disclosure](#4-selective-disclosure)
  - [YourD Analytics](#yourd-analytics)
  - [DNS (DID Naming Service)](#dns-did-naming-service)
    - [Permissions](#permissions)
    - [Various Contributor Settings Examples](#various-contributor-settings-examples)
  - [Web3 YourDB (Real-time Database)](#web3-yourdb-real-time-database)
  - [YourD Data Leverage Infra](#yourd-data-leverage-infra)
    - [1. D-Ad (Walking Ads)](#1-d-ad-walking-ads)
- [Additional Information](#additional-information)
  - [Resources](#resources)
  - [Hackathon Awards](#hackathon-awards)
      - [Polkadot : North America Edition: Astar Network - Related Link](#polkadot--north-america-edition-astar-network---related-link)
      - [ETHSeoul - IPFS/File coin - Related Link](#ethseoul---ipfsfile-coin---related-link)
      - [Klaymakers 22 - Related Aritcle](#klaymakers-22---related-aritcle)
      - [Evmos-Covalent #OneMillionWallets Hackathon - Related Article](#evmos-covalent-onemillionwallets-hackathon---related-article)
      - [Tron Hackathon - Related Article](#tron-hackathon---related-article)

# YourD Overview

<p align="center">
<img align="center" src="/static/img/YourD-Stack.png" width="500">
</p>

YourD is your ultimate destination for simplified Web 3.0 login, user-centric data ownership, and next-generation user analysis tools, all compliant with data privacy laws.

- **YourD DID SDK:** SDK will be augmented with a dedicated resolver, dereferencer, and other functions tailored to multiple blockchain network.
- **YourD Login:** Quick and easy start with true Web 3.0. Say goodbye to complex conventional wallet logins.
- **YourD Pass:** User-centric data management. You own and control your data.
- **YourD Analytics:** Adhere to GDPR and CCPA while conducting effective user analysis.
- **DNS:** DID Naming Service. Search engine for Dapps and users.
- **Web3 YourDB:**
- **YourD Data Leverage Infra:** Explore and discover new business models in a secured Web 3.0 environment.

# YourD Components

## YourD DID SDK

<p align="center">
<img align="center" src="/static/img/YourD-DID-Architechture.png" width="500">
</p>

The YourD DID SDK is a comprehensive toolkit and library suite designed to empower developers and businesses to effortlessly build applications and services on a Decentralized Identifier (DID) foundation in the Web 3.0 ecosystem. Engineered with an emphasis on openness, security, and privacy, the SDK ensures that digital identities are user-centric, upholding data ownership principles and enabling real-time user analytics.

For more details, please refer to: [YourD-did-specification](https://github.com/DataSovereignty-YourD/YourD-did-sepcification)

#### GitHub Repositories

**Resolver:** [View on GitHub](https://github.com/DataSovereignty-YourD/yourd-resolver)

**Verifiable Credential:** [View on GitHub](https://github.com/DataSovereignty-YourD/yourD-Verifiable-Credential)

## YourD Login
<img align="center" src="/static/img/YourDPass_mockups.png" width="300">
YourD's easy-login feature, based on QR, involves intricate server design and interplay. By merging existing protocols such as FIDO, WebAuthn, and others, YourD offers an authentication server that allows individual DID inquiries and management without breaching Herd Privacy. From the user's perspective, the process might seem straightforward. However, behind the scenes, there's an extensive interplay and interaction taking place. This feature ensures services on Aleo can benefit from easy authentication and login, promoting mass adoption.

**GitHub:** [View on GitHub](https://github.com/DataSovereignty-YourD/yourD-Auth-Server)

## YourD Pass (Mobile App)

**YourD Pass offers three primary features:**

### 1. Storage of Verifiable Credentials (VC) for Users

- YourD Pass provides a function to securely store and manage users' VCs.
- This allows users to keep their identity information secure and easily access or share it when needed.

### 2. Fast Authentication for Services Using YourD SaaS

- With YourD Pass, users can easily authenticate themselves to various services that utilize Saas.
- This offers users a convenient experience without the complexities of a standard login process.

### 3. Compliance with European Design Standards

- YourD Pass is designed in compliance with European regulations concerning data protection and authentication.
- Thus, users can securely store VCs issued by European institutions in YourD Pass.

### 4. Selective Disclosure

**Concealing DID Properties:**

- Hiding specific DID property values with user consent.
- Authenticating users even with concealed information.

**Applications:**

- Real-world services.
- Airports for identity verification with minimal disclosure.

**Personalized Login System:**

- Authenticating using selected user properties.
- Safe authentication environment while minimizing personal data exposure.

These features reflect YourD's philosophy, which prioritizes user data protection and convenience. With YourD Pass, users can manage their data more easily and safely.

**GitHub:** [View on GitHub](https://github.com/DataSovereignty-YourD/yourDApp-beta)

## YourD Analytics

<p align="center">
<img align="center" src="/static/img/YourD-Analytics.png" width="500"/>
</p>

YourD offers a privacy-focused Web3.0 analytics service, enabling existing services to analyze users without violating regulations such as GDPR. Serverless DApps, particularly those on blockchains, have historically faced challenges in user analysis and indexing. With YourD's analytics service, this process becomes straightforward. DApps can benefit from this feature, providing an effective means to understand and manage their user base.

**GitHub:** [View on GitHub](https://github.com/DataSovereignty-YourD/YourD-SaaS)

## DNS (DID Naming Service)
<img align="center" src="/static/img/DIDns_aleo.png" width="500"/>
<img align="center" src="/static/img/DIDns_aleo_profile.png" width="500"/>
### Permissions

- **Owner:** Can add or remove contributors.

- **Contributor:** Holds the authority to add, delete, or edit any entry.

- **Verifier:** Capable of changing the verified status of an entry.

### Various Contributor Settings Examples

1. **Institutional Contributor:** Entities recognized by the owner, such as the Aleo Foundation and AleoScope team. These institutions have unrestricted access to edit labels at their discretion.

2. **Community Contributor (User Participation System):** A contract that accepts user reports. Any leo user can report, but certain conditions must be met for it to be reflected in PublicLabels. To make it practical, a webpage may be needed in front of the contract.

To be reflected in the PublicLabels:

- Approval by the owner.
- Accumulation of a specified number of approval votes from users.
- Certification by the contract issuer.

**GitHub:** [View on GitHub](https://github.com/DataSovereignty-YourD/yourd-name-service)

## Web3 YourDB (Real-time Database)

It is meticulously crafted to surmount the challenges faced by serverless DApps and blockchain platforms in real-time user analysis and indexing. It provides a robust infrastructure that caters to the instantaneous, dynamic data needs without compromising user privacy or breaching legal constraints.

This real-time database integrates seamlessly with YourD Analytics, offering a symphony of real-time data access, analytics precision, and privacy preservation. Service providers and developers are equipped with a tool that not only facilitates real-time insights and actions but also ensures that every data interaction is anchored in the principles of privacy and compliance. The amalgamation of speed, accuracy, and privacy makes YourD’s real-time database an indispensable asset for web3 projects aspiring to scale, adapt, and evolve in alignment with user expectations and legal standards.

**GitHub:**

## YourD Data Leverage Infra

### 1. D-Ad (Walking Ads)

<p align="center">
<img align="center" src="/static/img/D-Ad-Dashboard.png" width="700">
</p>

It is YourD targeted advertisement without data collection. Companies utilizing YourD infrastructure can generate new revenue through the web3.0 advertising protocol without collecting personal data. The web3.0 advertising protocol is written through a circuit using iden3's circom. This protocol operates by sending pre-labeled advertisements to users based on various personal information, ensuring ads match user preferences. Users, in turn, can earn coins as rewards. Instead of creating tokens, our design utilizes the mainnet's native coin, aiming to boost the coin's liquidity and utility, even in real-world scenarios. You can find a detailed explanation and anticipated outcomes of this service in the demo link provided and the appendix section of the pitch deck.

Demo - Klaymakers22 Winner
Video demo link minimal MVP : [View on Youtube](https://youtu.be/GpFd8h3oj88)

**GitHub:** [View on GitHub](https://github.com/DataSovereignty-YourD/D-Ad-app-Beta)

# Additional Information

For a more detailed overview of YourD, please refer to the accompanying resources below.

## Resources

Pitch deck link: [Pitch Deck](https://docs.google.com/presentation/d/1RTPFkZnuFlukM08RwIJIOcwNM1d8R2eIAKWWhKk8cRU/edit#slide=id.g27ae4fecafd_0_388)

TTI Demo Day: [Tezos Demo Day Article](https://www.tzapac.com/articles/reliving-demo-day-of-the-tz-apac-tezos-incubator-cohort-2/?utm_source=Content+Hub&utm_medium=Twitter&utm_campaign=DemoDay_TZAPAC)

TTI Demo Day Video link: [View on Twitter](https://twitter.com/i/status/1699293320705704274)

YourD D-Ad Article: [Tezos Article](https://www.tzapac.com/articles/the-future-of-advertising-is-decentralized-this-startup-shows-us-why/)

## Hackathon Awards

#### Polkadot : North America Edition: Astar Network - [Related Link](https://devpost.com/software/comit)

#### ETHSeoul - IPFS/File coin - [Related Link](https://devfolio.co/projects/soul-tag-f317)

#### Klaymakers 22 - [Related Aritcle](https://medium.com/klaytn/announcing-the-winners-of-klaymakers22-klaytns-flagship-web3-hackathon-ef5e918bd440)

#### Evmos-Covalent #OneMillionWallets Hackathon - [Related Article](https://www.blog.encode.club/evmos-covalent-onemillionwallets-hackathon-prizewinners-and-summary-22fca2302c37)

#### Tron Hackathon - [Related Article](https://finance.yahoo.com/news/happy-holidays-tron-grand-hackathon-184527912.html)
