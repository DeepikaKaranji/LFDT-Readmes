# Trust Over IP

Welcome to **Trust Over IP (ToIP)**, a digital trust project of the [Linux Foundation Decentralized Trust](https://www.lfdecentralizedtrust.org).

Trust Over IP provides a robust, common standard and complete architecture for Internet-scale digital trust. It combines cryptographic assurance at the machine layers with human accountability at the business, legal, and social layers.

You can find more information on the [Trust Over IP project page](https://www.lfdecentralizedtrust.org/projects/trust-over-ip).

<!-- TODO: Add a Trust Over IP banner image here -->
<!-- ![Trust Over IP Banner](link-to-banner-image) -->

## Welcome to the Trust Over IP (ToIP) Github

ToIP was founded in May 2022 to develop a protocol stack (the ToIP stack) modeled after the same four layers as the TCP/IP stack. Both are designed to support Internet-scale infrastructure. The main differences are:

- The ToIP stack addresses security, privacy, and trust establishment gaps not addressed in the TCP/IP stack.
- The ToIP stack is a dual stack of technology protocols and governance controls because both are required to achieve trust.

The repos hosted here represent three generations of evolution of ToIP deliverables:

1. Repos started before 2023 contain deliverables produced by the first generation of WGs and TFs. These were largely exploratory or advisory.
2. Repos dating from ~2023 started to transition into deliverables intended to become full ToIP Approved Deliverables. These began using the first standard ToIP specification template (based on the ISO spec model).
3. Repos created in 2026 now mostly represent deliverables intended to become full ToIP Approved Deliverables. Those devoted to ToIP technical specifications use the new ToIP specification template (based on the IETF RFC model).

## What is Trust Over IP?

Trust Over IP defines an architecture for Internet-scale digital trust.

The ToIP stack is modeled after the four-layer structure of the TCP/IP stack, but it addresses a different problem: how people, organizations, devices, services, and digital agents can establish trust online.

ToIP combines two complementary halves:

- **Technology protocols** — Cryptographic and technical mechanisms that support trustworthy digital interactions.
- **Governance controls** — Business, legal, policy, and social rules that make trust ecosystems accountable and interoperable.

Together, these two halves form a four-layer architecture for decentralized digital trust infrastructure.

## Architecture

Trust Over IP is organized around a four-layer, dual-stack architecture:

- **Layer 1: Utility Layer** — Foundational infrastructure such as networks, ledgers, identifiers, cryptographic utilities, and registries.
- **Layer 2: Agent Layer** — Software agents, wallets, services, and endpoints that exchange trusted data and messages.
- **Layer 3: Credential Exchange Layer** — Protocols and workflows for issuing, holding, presenting, verifying, and revoking credentials and other trustworthy data.
- **Layer 4: Ecosystem Layer** — Governance frameworks, trust registries, business rules, policies, and ecosystem-specific controls.

Each layer has both a technology side and a governance side because technical interoperability alone is not enough to establish trust at Internet scale.

## What Trust Over IP Enables

Trust Over IP helps communities, organizations, and ecosystems:

- Define digital trust architectures
- Create interoperable trust frameworks
- Develop technical specifications for trusted digital interactions
- Connect decentralized identifiers, verifiable credentials, wallets, agents, and trust registries
- Establish governance frameworks for digital trust ecosystems
- Support trusted data exchange across organizations and jurisdictions
- Build reusable standards, protocols, and implementation guidance
- Improve security, privacy, and accountability in digital interactions

Example use cases include:

- Digital identity ecosystems
- Verifiable credential networks
- Trust registries and trust lists
- Digital wallets and credential exchange
- Supply chain trust
- Regulatory technology and compliance workflows
- Agent-to-agent digital trust
- Cross-border and cross-sector trust frameworks

## Repositories

The Trust Over IP GitHub organization contains many repositories representing working groups, task forces, specifications, models, tools, and deliverables.

| Repository | Description |
|---|---|
| [**kswg-did-method-webs-specification**](https://github.com/trustoverip/kswg-did-method-webs-specification) | DID method specification for `did:webs`. |
| [**tswg-did-x509-method-specification**](https://github.com/trustoverip/tswg-did-x509-method-specification) | DID method specification work related to X.509. |
| [**tswg-tsp-specification**](https://github.com/trustoverip/tswg-tsp-specification) | Trust Spanning Protocol specification. |
| [**kswg-keri-specification**](https://github.com/trustoverip/kswg-keri-specification) | Key Event Receipt Infrastructure specification work. |
| [**kswg-acdc-specification**](https://github.com/trustoverip/kswg-acdc-specification) | Authentic Chained Data Containers specification work. |
| [**kswg-cesr-specification**](https://github.com/trustoverip/kswg-cesr-specification) | Composable Event Streaming Representation specification work. |
| [**tswg-trust-registry-protocol**](https://github.com/trustoverip/tswg-trust-registry-protocol) | Trust Registry Query Protocol specification work. |
| [**dtgwg-trust-tasks-tf**](https://github.com/trustoverip/dtgwg-trust-tasks-tf) | Trust Tasks work for transport-agnostic task management. |
| [**aimwg-tsp-enabled-ai-agent-protocols**](https://github.com/trustoverip/aimwg-tsp-enabled-ai-agent-protocols) | TSP-enabled AI agent protocols specification work. |

<!-- TODO: Confirm which repositories should be highlighted as official first-starting points for new contributors. -->

## Resources

The following documents will help you understand Trust Over IP's vision, workflows, deliverables, and community.

- The [Trust Over IP project page](https://www.lfdecentralizedtrust.org/projects/trust-over-ip) gives an overview of the project, architecture, objectives, benefits, and community links.
- The [Trust Over IP website](https://www.trustoverip.org/) describes ToIP's mission, model, work, design principles, events, and working groups.
- The [Trust Over IP GitHub organization](https://github.com/trustoverip) contains ToIP repositories for specifications, working groups, task forces, models, tools, and deliverables.
- The [Trust Over IP wiki](https://lf-toip.atlassian.net/wiki/) contains working group materials, meeting notes, deliverable information, and community documentation.
- The [ToIP Technology Architecture](https://trustoverip.org/our-work/technology-architecture/) describes the technical architecture work of the project.
- The [Trust Over IP model](https://trustoverip.org/toip-model/) explains the four-layer model that combines cryptographic trust and governance.
- The [Trust Over IP deliverables page](https://trustoverip.org/our-work/deliverables/) provides access to ToIP deliverables and specification work.
- The [Trust Over IP working group activity page](https://trustoverip.org/about/working-group-activity/) describes active working groups and participation areas.
- Watch Trust Over IP videos through the [LFDT YouTube playlists page](https://www.youtube.com/c/Hyperledger/playlists), which includes a Trust Over IP playlist.
- Watch the Trust Over IP 5th Anniversary Virtual Symposium: [Day 1](https://www.youtube.com/watch?v=1bOR7aEiz6k) and [Day 2](https://www.youtube.com/watch?v=MwnBALA8ygs).
- Our [Code of Conduct](https://www.lfdecentralizedtrust.org/code-of-conduct) describes expected behavior across the LFDT community.
- For security related issues, please follow the LFDT security reporting process. Do not post security related content, issues, or discussions publicly in any repository.
- Trust Over IP repositories may contain different licenses depending on whether they are specifications, documents, templates, or code. Please check the license file in each repository before reuse.

<!-- TODO: Add links once confirmed:
- Current community meeting calendar
- Direct Discord channel links
- Current maintainer list
- Current specification template guidance
- LFX Insights page
- Project charter
-->

## How to contribute

Trust Over IP welcomes contributors interested in digital trust architecture, governance, decentralized identity, verifiable credentials, trust registries, digital wallets, secure protocols, and ecosystem interoperability.

Good ways to get started:

1. Review the [Trust Over IP GitHub organization](https://github.com/trustoverip).
2. Explore the [Trust Over IP website](https://www.trustoverip.org/) and [wiki](https://lf-toip.atlassian.net/wiki/).
3. Join community discussions on [LFDT Discord](https://discord.lfdecentralizedtrust.org). Channel: #toip-general
4. Attend community meetings. ToIP community calls and working group meetings are open to participants interested in advancing Internet-scale digital trust.
5. Choose a working group, task force, or repository that matches your area of interest.
6. Open issues for bugs, documentation gaps, specification questions, or feature ideas.
7. Submit pull requests with clear descriptions and links to related issues or working group discussions.

| Meeting | Frequency | Calendar Link |
|---|---|---|
| ToIP Community / Working Group Meetings | Varies by working group | _TBD — Add LFX Calendar or ToIP meeting calendar link_ |

Past meeting recordings and presentations can be accessed through:

- [LFX Individual Dashboard](https://openprofile.dev/)
- [LFDT Meeting Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust)
- [LFDT YouTube playlists](https://www.youtube.com/c/Hyperledger/playlists)

For larger changes, please open an issue first so the community can discuss the design before implementation.

## Current Status

Trust Over IP is an active LFDT project focused on Internet-scale digital trust architecture, technical specifications, governance frameworks, working group deliverables, and community collaboration.

The project continues to evolve its deliverables from exploratory working group outputs toward full ToIP Approved Deliverables, including specifications that use newer ToIP templates based on established standards models.

## License

Trust Over IP repositories may contain specifications, governance materials, documentation, templates, and code. Licenses may vary by repository.

Please check the `LICENSE`, `NOTICE`, or repository-specific governance files before reusing content.
