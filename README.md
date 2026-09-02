<div align="center">

# SourceSensei

**Solana protocol engineering · smart-contract security · DeFi infrastructure**

Rust · Anchor · Cairo · Solidity · Go · TypeScript

[LinkedIn](https://www.linkedin.com/in/sourcesensei/) · [X](https://x.com/SourceSenseii) · Available for protocol engineering, security reviews, and high-trust Web3 builds

</div>

I build and review blockchain systems where failures have financial consequences. My main lane is Solana protocol engineering and smart-contract security: Rust and Anchor programs, SPL token flows, PDAs, CPIs, vaults, authority models, and adversarial testing.

I also ship complete systems across Cairo/Starknet, Solidity/EVM, Go services, TypeScript/Next.js, PostgreSQL, wallet integrations, and AI-assisted engineering tools. I stay close to the trust model from the contract instruction through the backend, indexer, and user transaction flow.

## Recent public work

| Project | System | Evidence |
| --- | --- | --- |
| [CipherBid](https://github.com/SourceSenseiTheRealOne/cipherbid) | Cairo, Starknet, STRK20, Next.js | A funded Vickrey NFT auction with equalized collateral, sealed bids, second-price settlement, atomic NFT delivery, encrypted recovery, and private claims. The complete lifecycle ran on [Starknet mainnet](https://sourcesenseitherealone.github.io/cipherbid/auction/?id=1788040057342) with a [public transaction ledger](https://github.com/SourceSenseiTheRealOne/cipherbid/blob/main/docs/evidence/mainnet/transactions.md). |
| [SettleShield](https://github.com/SourceSenseiTheRealOne/settleshield) | Solidity, Foundry, Somnia, DreamDEX, Next.js | Bounded protection for pending crypto settlements using live Event Contract quotes, wallet-signed IOC orders, fill accounting, and on-chain receipts. The receipt contract and full lifecycle were [verified on Shannon](https://github.com/SourceSenseiTheRealOne/settleshield#verified-shannon-proof). |
| [Juntly](https://github.com/SourceSenseiTheRealOne/juntly) | Next.js, Go, Clerk, PostgreSQL, OpenAPI | A production-oriented local services marketplace with durable listings, private contact reveal, messaging, quotations, bookings, moderation, API contracts, backups, recovery procedures, and hardened runtime boundaries. |
| [Coach Connect Orbit](https://github.com/SourceSenseiTheRealOne/coach-connect-orbit) | Next.js Multi-Zones, Go/Revel, Clerk, tRPC, Ent | A football social network and marketplace scaffold with independently deployable frontend zones, a typed API path, explicit auth boundaries, Docker health checks, and a project-local Supabase boundary. |
| [Arch Indexer Go](https://github.com/SourceSenseiTheRealOne/arch-indexer-go) | Go, PostgreSQL, Redis, Arch Network | A protocol-neutral, read-only blockchain indexer foundation. It establishes bounded configuration, adapter boundaries, deterministic recovery architecture, race/vet/build gates, and an honest runtime refusal until ingestion is implemented. |

Current research includes a [paper-only Solana new-token bot](https://github.com/SourceSenseiTheRealOne/solana-hype-paper-bot) for bounded social-signal experiments, market-data analysis, and risk-controlled strategy evaluation.

## Selected private and client engineering

Some of my deeper work cannot be linked publicly. Recent assignments include:

- reviewing and hardening Solana/Anchor fundraising, token, and vault paths, including authority checks, PDA derivation, custody, callbacks, settlement invariants, and synthetic exploit regressions;
- engineering protocol transaction and indexing paths across testnet and mainnet, with state and receipt readback before release;
- building least-authority local automation that keeps credentials, sessions, and wallet actions outside autonomous workers.

## Engineering focus

| Area | What I work on |
| --- | --- |
| Solana and protocol security | Rust, Anchor, SPL Tokens, PDAs, CPIs, vaults, launch mechanics, governance, transaction composition, program audits, exploit reproduction, and invariant testing |
| Smart contracts and privacy | Cairo, Starknet, STRK20, Solidity, Foundry, EVM, commit/reveal systems, auctions, settlement, custody, recovery, and wallet boundaries |
| Blockchain infrastructure | Go, TypeScript, Node.js, PostgreSQL, Redis, WebSockets, JSON-RPC, indexers, event delivery, deterministic recovery, and operational tooling |
| Product delivery | Next.js, React, Clerk, Supabase, OpenAPI, Docker, GitHub Actions, browser verification, and secure wallet UX |
| Applied AI | Agent workflows, RAG, research automation, structured outputs, evaluation loops, and constrained tool access |

## How I engineer

- I map assets, authorities, trust boundaries, and failure states before I optimize the happy path.
- Contract and transaction work gets adversarial tests for bad authority, stale state, replay, account substitution, decimal mistakes, callback failure, and partial settlement.
- I separate read authority from write authority. Signers and service credentials stay behind the narrowest boundary that can do the job.
- "Deployed" means the expected bytecode, configuration, transaction receipts, state changes, and user route were read back from the target network.
- I state the limits. A scaffold is a scaffold, testnet is testnet, and an unaudited deployment is not production security.

## Work with me

I am a strong fit for Solana engineer, smart-contract security reviewer, protocol engineer, DeFi engineer, blockchain infrastructure, and senior Web3 full-stack roles. I am especially useful when one person needs to follow the security model across contracts, services, indexers, wallets, and frontend transaction flows.

For contract work, protocol builds, security reviews, or technical consulting, reach me on [LinkedIn](https://www.linkedin.com/in/sourcesensei/) or [X](https://x.com/SourceSenseii).
