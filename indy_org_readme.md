# Hyperledger Indy

Welcome to **Hyperledger Indy**, a decentralized identity project of the [Linux Foundation Decentralized Trust](https://www.lfdecentralizedtrust.org).

Hyperledger Indy provides tools, libraries, and reusable components for decentralized identity. It helps developers build privacy-preserving identity systems using decentralized identifiers, verifiable credentials, zero-knowledge proofs, and distributed ledger technology.

You can find more information on the [Hyperledger Indy project page](https://www.lfdecentralizedtrust.org/projects/hyperledger-indy).

<!-- TODO: Add a Hyperledger Indy banner image here -->
<!-- ![Hyperledger Indy Banner](link-to-banner-image) -->

## What is Hyperledger Indy?

Hyperledger Indy is an open-source implementation of distributed ledger technology built specifically for decentralized identity.

Indy provides infrastructure for digital identities rooted in distributed ledgers, allowing identities to be interoperable across applications, organizations, administrative domains, and other silos.

Indy is designed to support privacy-preserving identity workflows where users can prove claims about themselves without revealing unnecessary personal information.

## Architecture

Hyperledger Indy is composed of several integrated parts:

- **Ledger Infrastructure** — A distributed ledger designed for decentralized identity metadata such as DIDs, schemas, credential definitions, and revocation registries.
- **Node and Consensus Components** — Software for running Indy ledger nodes and maintaining agreement across the network.
- **Client and Resolver Libraries** — Libraries for reading from and writing to Indy ledgers, resolving DIDs, and interacting with identity-related ledger data.
- **DID and Credential Specifications** — Specifications and supporting implementations for decentralized identifiers, verifiable credentials, and privacy-preserving credential exchange.

Together, these components let developers and organizations build decentralized identity networks and applications with ledger-backed trust, interoperability, and privacy-preserving credential workflows.

## What Hyperledger Indy Enables

Hyperledger Indy allows developers and organizations to:

- Build decentralized identity networks
- Issue and verify verifiable credentials
- Use decentralized identifiers for identity interactions
- Support privacy-preserving credential presentations
- Use zero-knowledge proofs for selective disclosure
- Manage schemas, credential definitions, and revocation registries
- Build identity systems that work across organizations and applications
- Support self-sovereign identity and user-controlled data sharing

Example use cases include:

- Digital identity wallets
- Verifiable credential ecosystems
- Public identity utility ledgers
- Decentralized trust registries
- Education and workforce credentials
- Healthcare and government identity workflows
- KYC and compliance workflows
- Cross-organization identity interoperability

## Repositories

| Repository | Description |
|---|---|
| [**indy**](https://github.com/hyperledger-indy/indy) | Top-level project repository with project overview, technical charter, maintainers, contributing information, security policy, and governance references. |
| [**governance**](https://github.com/hyperledger-indy/governance) | Governance materials and project configuration for Hyperledger Indy. |
| [**indy-node**](https://github.com/hyperledger-indy/indy-node) | Server portion of the Indy distributed ledger. |
| [**indy-plenum**](https://github.com/hyperledger-indy/indy-plenum) | Byzantine Fault Tolerant protocol implementation used by Indy Node. |
| [**indy-vdr**](https://github.com/hyperledger-indy/indy-vdr) | Library and proxy server for interacting with Indy ledger networks. |
| [**indy-shared-rs**](https://github.com/hyperledger-indy/indy-shared-rs) | Shared Rust data types and utilities for Indy projects. |
| [**indy-node-container**](https://github.com/hyperledger-indy/indy-node-container) | Container images and tooling for running Indy Node. |
| [**indy-did-method**](https://github.com/hyperledger-indy/indy-did-method) | Source repository for the `did:indy` DID Method specification. |

## Resources

The following documents will help you understand Hyperledger Indy's vision, workflows, and community.

- The [Hyperledger Indy project page](https://www.lfdecentralizedtrust.org/projects/hyperledger-indy) gives an overview of the project, documentation, videos, deployment resources, tutorials, and community links.
- The [Hyperledger Indy GitHub organization](https://github.com/hyperledger-indy) contains the Indy project repositories.
- The [indy repository](https://github.com/hyperledger-indy/indy) contains the project overview, technical charter, maintainers, contributing information, and security policy.
- The [governance repository](https://github.com/hyperledger-indy/governance) contains project governance materials.
- The [Indy documentation index](https://lf-hyperledger.atlassian.net/wiki/spaces/indy/pages/19464437/Documentation+Index) links to official Indy documentation.
- The [Indy Read the Docs site](https://hyperledger-indy.readthedocs.io/) provides additional project documentation.
- The [Indy DID Method specification](https://hyperledger.github.io/indy-did-method/) describes the `did:indy` DID method.
- Watch Hyperledger Indy videos through the [official Hyperledger Indy YouTube playlist](https://www.youtube.com/playlist?list=PL0MZ85B_96CFSb8YVK0GytaqH0VUcNNUV).
- Watch the introductory video: [Hyperledger Indy — What it is and how to get involved](https://www.youtube.com/watch?v=7ofbsH5J9Tc).
- Watch a recent community recording: [Hyperledger Indy Contributors Meeting — 2026/06/02](https://www.youtube.com/watch?v=Oniq_b7Yy9o).
- Our [Code of Conduct](https://www.lfdecentralizedtrust.org/code-of-conduct) describes expected behavior across the LFDT community.
- For security related issues, please follow the security policy in the relevant repository. Do not post security related content, issues, or discussions publicly in any repository.
- Hyperledger Indy repositories are generally licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), unless otherwise noted in a specific repository.

<!-- TODO: Add links once confirmed:
- Current community meeting calendar
- Direct Discord channel links
- Current maintainer list
- Contributor guide
- LFX Insights page
-->

## How to contribute

Hyperledger Indy welcomes developers, operators, researchers, identity architects, organizations, and privacy advocates interested in decentralized identity and verifiable credential infrastructure.

Good ways to get started:

1. Review the [indy repository](https://github.com/hyperledger-indy/indy).
2. Explore the [Indy documentation index](https://lf-hyperledger.atlassian.net/wiki/spaces/indy/pages/19464437/Documentation+Index).
3. Join community discussions on [LFDT Discord](https://discord.lfdecentralizedtrust.org). Channel: #indy
4. Attend community meetings. Indy community calls are open to everyone. These meetings are a good place to ask questions, discuss roadmap priorities, and learn how to contribute.

| Meeting | Frequency | Calendar Link |
|---|---|---|
| Indy Contributors Meeting | TBD | _TBD — Add LFX Calendar link_ |

Past meeting recordings and presentations can be accessed through:

- [LFX Individual Dashboard](https://openprofile.dev/)
- [LFDT Meeting Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust)
- [Hyperledger Indy YouTube playlist](https://www.youtube.com/playlist?list=PL0MZ85B_96CFSb8YVK0GytaqH0VUcNNUV)

For larger changes, please open an issue first so the community can discuss the design before implementation.

## Current Status

Hyperledger Indy is a **graduated** LFDT project. Indy continues to serve as a foundation for decentralized identity systems, verifiable credential networks, DID infrastructure, and privacy-preserving credential workflows.

## License

Hyperledger Indy repositories are generally licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), unless otherwise noted in a specific repository.
