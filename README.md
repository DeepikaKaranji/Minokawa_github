# Minokawa

Welcome to **Minokawa**, a zero-knowledge-native smart contract language project of the [Linux Foundation Decentralized Trust](https://www.lfdecentralizedtrust.org).

Minokawa is a domain-specific smart contract language purpose-built for zero-knowledge execution. It helps developers build smart contracts that combine privacy, verifiability, and usability in a single framework.

You can find more information on the [Minokawa project page](https://www.lfdecentralizedtrust.org/projects/minokawa).

<!-- TODO: Add a Minokawa banner image here -->
<!-- ![Minokawa Banner](link-to-banner-image) -->

## What is Minokawa?

Minokawa enables developers to write privacy-preserving smart contracts without manually building zero-knowledge circuits.

Minokawa originated from the **Compact** smart contract language and associated tooling. Under LFDT stewardship, Compact becomes Minokawa and continues as an open source project for zero-knowledge-native smart contract development.

Minokawa is designed to support applications where sensitive data can remain private unless intentionally disclosed, while still providing cryptographic guarantees that computations were performed correctly.

## Architecture

Minokawa is composed of three integrated parts:

- **Language** — A TypeScript-like domain-specific language designed for zero-knowledge contract development. It supports rich data types, public and private function scopes, modularity, and privacy-safe access to off-chain data.
- **Compiler** — Transforms Minokawa contracts into JavaScript modules, TypeScript types, source maps, and zero-knowledge proof artifacts.
- **Runtime** — A JavaScript / TypeScript library that executes contracts, manages proofs, and enforces runtime type safety between off-chain private data and on-chain logic.

Together, these components let developers focus on application logic instead of manually wiring together circuits, proof generation, and contract integration.

## What Minokawa Enables

Minokawa allows developers to:

- Build smart contracts where data can remain private unless intentionally disclosed
- Use native zero-knowledge capabilities without writing circuits manually
- Compose public and private logic in one smart contract framework
- Implement selective disclosure for compliance and privacy-sensitive workflows
- Create applications that preserve digital agency and user privacy
- Build verifiable applications with stronger privacy guarantees
<!--Needs to be vetted by maintainers>
Example use cases include:

- Private voting
- Confidential asset tokenization
- Decentralized identity and KYC workflows
- Selective disclosure
- Private data marketplaces
- Whistleblowing and confidential reporting systems
- Compliance workflows with auditable guarantees
<-->

## Repositories

| Repository | Description |
|---|---|
| [**compact**](https://github.com/LFDT-Minokawa/compact) | The main technical repository for the Compact / Minokawa programming language, compiler, runtime, documentation, examples, editor support, tests, and toolchain. |
| [**governance**](https://github.com/LFDT-Minokawa/governance) | Governance materials and project configuration for Minokawa. |

## Resources

The following documents will help you understand Minokawa's vision, workflows, and community.

- The [Minokawa project page](https://www.lfdecentralizedtrust.org/projects/minokawa) gives an overview of the project, architecture, and use cases.
- The LFDT blog post [Compact smart contract language is now Minokawa](https://www.lfdecentralizedtrust.org/blog/compact-smart-contract-language-is-now-minokawa-newest-lf-decentralized-trust-project) explains the project's origin and transition to LFDT.
- The [Compact documentation](https://docs.midnight.network/compact) provides language and developer documentation.
- Watch Minokawa videos through the [LFDT Minokawa video page](https://www.lfdecentralizedtrust.org/projects/minokawa#videos) and the [LFDT YouTube channel](https://www.youtube.com/@lfdecentralizedtrust).
- Watch the Minokawa meetup recording: [Making Zero-Knowledge Smart Contract Development Accessible, Secure & Practical](https://www.youtube.com/watch?v=AT2eO_8yDz8).
- Our [Code of Conduct](https://www.lfdecentralizedtrust.org/code-of-conduct) describes expected behavior across the LFDT community.
- For security related issues, please follow the LFDT security reporting process. Do not post security related content, issues, or discussions publicly in any repository.

## How to contribute

Minokawa welcomes developers, researchers, cryptographers, organizations, and privacy advocates interested in zero-knowledge smart contracts and privacy-preserving applications.

Good ways to get started:

1. Review the [compact repository](https://github.com/LFDT-Minokawa/compact).
2. Join community discussions on [LFDT Discord](https://discord.lfdecentralizedtrust.org) Channel: #minokawa
3. Attend community meetings. Minokawa community calls are open to everyone. These meetings are a good place to ask questions, discuss roadmap priorities, and learn how to contribute.

| Meeting | Calendar Link |
|---|---|
| Minokawa Community Call | https://zoom-lfx.platform.linuxfoundation.org/meeting/92376999403?password=23e83ac5-4334-4da3-9e07-2afb5065fa28  |

Past meeting recordings and presentations can be accessed through:

- [LFX Individual Dashboard](https://openprofile.dev/)
- [LFDT Meeting Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust)


For larger changes, please open an issue first so the community can discuss the design before implementation.

## Current Status

Minokawa is an **incubating** LFDT project. The project has an established codebase and tooling through Compact, and the community is working to grow participation, improve documentation, expand examples, and evolve the language, compiler, and runtime.

## License

Minokawa repositories are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

