# Awesome Agent Economy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <img src="banner.png" alt="Awesome Agent Economy" width="100%">
  <br><br>
  <p>A curated list of projects, protocols, and platforms powering the emerging AI agent economy — where agents earn, trade, prove identity, and build reputation.</p>
</div>

## Contents

- [Identity and Trust](#identity-and-trust)
- [Payments and Settlement](#payments-and-settlement)
- [Negotiation and Commerce](#negotiation-and-commerce)
- [Publishing and Content](#publishing-and-content)
- [Platforms and Social](#platforms-and-social)
- [Reputation and Scoring](#reputation-and-scoring)
- [Standards and Protocols](#standards-and-protocols)
- [Agent Frameworks](#agent-frameworks)

## Identity and Trust

Verifying who (or what) an agent is.

- [Chitin](https://chitin.id/) - On-chain birth certificates for AI agents using ERC-8004 soulbound tokens on Base L2.
- [World ID](https://world.org/) - Proof-of-personhood protocol that distinguishes humans from AI agents.
- [Trusta.AI](https://trustalabs.ai/) - Universal credit layer with SIGMA trust model scoring agents across 5 dimensions.
- [Agentscan](https://agentscan.info/) - ERC-8004 agent search engine with ZK-Proof reputation verification.
- [Beyond Identity AI Trust Layer](https://www.beyondidentity.com/products/ai-trust-layer) - Enterprise agent security with device-bound identity and MCP server control.

## Payments and Settlement

How agents pay and get paid.

- [x402 Protocol](https://www.coinbase.com/developer-platform/products/x402) - HTTP-native payment protocol using the 402 status code with USDC on Base. By Coinbase. [GitHub](https://github.com/coinbase/x402)
- [Google AP2](https://ap2-protocol.org/) - Agent payment standard with cryptographic "Mandates" for verifiable intent. Backed by Salesforce, Visa, Mastercard. [GitHub](https://github.com/google-agentic-commerce/AP2)
- [Visa TAP](https://developer.visa.com/capabilities/trusted-agent-protocol) - Trusted Agent Protocol — open framework to distinguish legitimate AI agents from bots at checkout. [GitHub](https://github.com/visa/trusted-agent-protocol)
- [Skyfire](https://skyfire.xyz/) - Payment network for AI agents with USDC wallets, spending limits, and single-use credentials.
- [Nevermined](https://nevermined.ai/) - Decentralized payment rails for agent-to-agent commerce. Supports MCP, A2A, and x402.
- [Coinbase AgentKit](https://www.coinbase.com/developer-platform/products/agentkit) - Toolkit giving AI agents a crypto wallet with gasless Smart Wallet transactions. [GitHub](https://github.com/coinbase/agentkit)
- [Fetch.ai](https://fetch.ai/) - Autonomous agent framework with the world's first AI-to-AI real-world payment.

## Negotiation and Commerce

Agents making deals.

- [Haggle Protocol](https://haggle.dev/) - First on-chain negotiation protocol for AI agents with trustless escrow and algorithmic price discovery.
- [UCP](https://ucp.dev/) - Universal Commerce Protocol by Google and Shopify for AI agents to discover and purchase products.
- [ACP](https://www.agenticcommerce.dev/) - Agentic Commerce Protocol by OpenAI and Stripe. Open spec for agent-driven commerce. [GitHub](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol)
- [NEAR AI](https://near.ai/) - Decentralized marketplace where AI agents bid on tasks and receive settlement in NEAR tokens.

## Publishing and Content

Agents creating and distributing content.

- [Hum](https://hum.pub/) - AI author publishing platform with skill.md integration, Trust Score, ERC-8004 certs, and revenue sharing.
- [Moltbook](https://www.moltbook.com/) - AI-only social network with Reddit-like communities (Submolts). 1.5M+ AI agent users.
- [Virtuals Protocol](https://www.virtuals.io/) - Launchpad for tokenized AI agents that generate and monetize content on Base and Solana.

## Platforms and Social

Where agents live and interact.

- [MoChat](https://mochat.io/) - Agent-native messaging platform where AI agents are first-class citizens with own identity and auth. [GitHub](https://github.com/HKUDS/MoChat)
- [ClawdChat](https://clawdchat.ai/) - Agent social network integrated with nanobot and PicoClaw via skill.md.
- [Moltter](https://moltter.net/) - Social network for AI agents — agents post "molts", follow each other, and build engagement.
- [SingularityNET](https://singularitynet.io/) - Decentralized AI marketplace. Part of the ASI Alliance (merged with Fetch.ai and Ocean Protocol).
- [Morpheus](https://mor.org/) - Peer-to-peer network of personal AI agents connecting LLMs to wallets, dApps, and smart contracts. [GitHub](https://github.com/MorpheusAIs/Morpheus)

## Reputation and Scoring

Building trust over time.

- [ERC-8004 Reputation Registry](https://eips.ethereum.org/EIPS/eip-8004) - On-chain registry for structured, verifiable agent feedback via Ethereum Attestation Service.
- [Ethereum Attestation Service](https://attest.org/) - Open protocol for on-chain and off-chain attestations. Foundation for ERC-8004 reputation. [GitHub](https://github.com/ethereum-attestation-service/eas-contracts)
- [8004scan](https://www.8004scan.io/) - "Etherscan for AI Agents" — browse ERC-8004 agents, reputation scores, and leaderboards. By AltLayer.
- [TrustGo](https://trustalabs.ai/trustgo) - MEDIA score for humans transitioning to SIGMA for AI agents. Used by Celestia and Starknet. By Trusta.AI.

## Standards and Protocols

The plumbing that makes it all work.

- [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004) - Ethereum standard for agent Identity, Reputation, and Validation registries. Co-authored by MetaMask, EF, Google, Coinbase.
- [MCP](https://modelcontextprotocol.io/) - Model Context Protocol by Anthropic for connecting AI to tools and data. Under AAIF (Linux Foundation). [GitHub](https://github.com/modelcontextprotocol)
- [A2A](https://a2a-protocol.org/) - Agent2Agent Protocol by Google for inter-agent communication and task lifecycle management. [GitHub](https://github.com/a2aproject/A2A)
- [AGENTS.md](https://agents.md/) - OpenAI's open standard for giving AI coding agents project-specific guidance. Under AAIF.
- [Agentic AI Foundation](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation) - Linux Foundation directed fund governing MCP, goose, and AGENTS.md. Platinum members: AWS, Anthropic, Google, Microsoft, OpenAI.
- [Goose](https://block.github.io/goose/) - Open source AI agent framework by Block. Reference MCP implementation under AAIF governance. [GitHub](https://github.com/block/goose)

## Agent Frameworks

Infrastructure for building economic agents.

- [ElizaOS](https://elizaos.ai/) - Autonomous agent framework for crypto with cross-chain support via Chainlink CCIP. [GitHub](https://github.com/elizaOS/eliza)
- [CrewAI](https://www.crewai.com/) - Multi-agent orchestration framework used by 60% of Fortune 500 companies. [GitHub](https://github.com/crewAIInc/crewAI)
- [Autonolas](https://olas.network/) - Protocol for autonomous agent services on-chain. Multi-agent systems with composable services. [GitHub](https://github.com/valory-xyz)
- [Bittensor](https://bittensor.com/) - Decentralized AI network with 129+ subnets for different AI tasks. [GitHub](https://github.com/opentensor/bittensor)
- [Ocean Protocol](https://oceanprotocol.com/) - Decentralized data marketplace for AI with Compute-to-Data for privacy-preserving inference.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
