# SourceSensei

Software engineer working across Go backends, React/Next.js applications and smart contracts.

I'm interested in how systems behave at their boundaries: who can change state, what a failed request leaves behind, and how to recover without repeating a side effect.

`Go` · `Rust` · `Python` · `TypeScript` · `PostgreSQL` · `Docker` · `AWS` · `Solidity` · `Cairo` · `Anchor` ·

## Selected projects

### [Confidential Payments](https://github.com/SourceSenseiTheRealOne/hackathon-projects-base-confidential-payments-prototype)

Contractor-payment concept with a separate encrypted-allocation escrow experiment. The local escrow model accounts for the amount returned by a confidential transfer, including zero-value results, rather than assuming a successful call moved funds.

Next.js, TypeScript, Solidity, Foundry, Inco Lightning. **Concept UI and local contract experiment; no deployed payment flow.**

### [CipherBid](https://github.com/SourceSenseiTheRealOne/cipherbid)

Sealed-bid NFT auctions with equal collateral caps, second-price settlement and atomic NFT delivery. Bids become public at reveal; signing stays with the wallet, with encrypted recovery for bid credentials.

Cairo, Starknet, STRK20, Next.js, TypeScript. **Hackathon deployment**, with a [recorded mainnet lifecycle](https://github.com/SourceSenseiTheRealOne/cipherbid/blob/main/docs/evidence/mainnet/transactions.md); unaudited.

### [Solana Market Research](https://github.com/SourceSenseiTheRealOne/solana-market-research)

Read-only market-data pipeline with deterministic admission rules, serializable PostgreSQL transactions and durable retry leases. Paper positions are database records; there is no wallet integration, signing or trade execution.

Go, PostgreSQL, Ent, React, Vite. **Local, paper-only research software.**

### [Vila](https://github.com/SourceSenseiTheRealOne/vila)

Local-services marketplace with Go-owned authorization, consent-gated contact access and transactional quotation acceptance. An OpenAPI contract connects the Next.js frontend to the backend; identity and business permissions remain separate.

Go, PostgreSQL, Ent, Next.js, TypeScript, Clerk. **Pre-launch product**; public deployment and live payment acceptance remain unverified.

### [Linha Voice Lab](https://github.com/SourceSenseiTheRealOne/linha-voice-lab)

Local voice-agent dashboard with durable call intent, consent-gated retention and provider cleanup readback. Ambiguous call creation is not retried automatically. The control plane is local; optional Retell/Twilio voice processing runs in the cloud.

Go, SQLite, Next.js, TypeScript, Retell, Twilio. **Experimental test product**, not production-ready.

## Working notes

- Model state transitions and authorization in the service or contract, not just the UI.
- Put transactions around invariants; give retries explicit limits and recovery rules.
- Test failure paths alongside the happy path, including duplicate events, stale state and partial provider failures.
- Keep local tests, browser checks and live execution evidence distinct.

[LinkedIn](https://www.linkedin.com/in/sourcesensei/) · [X](https://x.com/SourceSenseii)
