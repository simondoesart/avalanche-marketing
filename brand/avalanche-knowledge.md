# Avalanche Knowledge Base (for marketers)

Snapshot date: July 2026. For anything time-sensitive, ALWAYS verify live — see "Live documentation lookup" below.

## Live documentation lookup (use this instead of trusting this snapshot)

- Any page on **build.avax.network** returns clean raw markdown if you append `.md` to the URL. Example: `https://build.avax.network/docs/primary-network.md`
- Index of all docs/academy/blog/integration pages: `https://build.avax.network/llms.txt`
- Entire documentation in one file (large): `https://build.avax.network/llms-full.txt`
- When a claim needs a technical fact (finality time, chain ID, staking minimum, consensus detail), fetch the live doc page and cite it rather than relying on memory.

## The tech, in marketer terms

- **Avalanche** is a heterogeneous network of blockchains: instead of every app sharing one chain, purpose-built chains coexist and interoperate. This is the "thousands of purpose-built L1s" story.
- **Primary Network** = a special Avalanche L1 running three chains:
  - **C-Chain** (Contract Chain): EVM-compatible smart contracts. Chain ID 43114. This is where most DeFi/apps live.
  - **P-Chain** (Platform Chain): validators, staking, L1 creation/coordination.
  - **X-Chain** (Exchange Chain): digital asset creation/trading.
- **Validators** stake at least 2,000 AVAX to secure the Primary Network. Uptime requirement raised to 90% (ACP-267).
- **Avalanche L1s** (formerly "subnets"): sovereign networks with their own rules, gas token, validator set, fee markets, and compliance controls (KYC/AML-checked validators, geo requirements, private chains). The institutional pitch: multi-tier permissioning, privacy, custom gas/staking, blocktime configurability.
- **Consensus**: Snow* family (Snowball/Snowman/Avalanche). Sub-second transaction finality — "settles in seconds, not days." Sub-second blocks arriving via ACP-226 dynamic minimum block times.
- **Interoperability**: Avalanche Interchain Messaging (ICM, a.k.a. Warp) — native cross-L1 communication without bridges → "interoperability without counterparty risk."
- **EVM compatibility**: any EVM app deploys seamlessly; existing wallets, audit firms, smart-contract libraries work natively.
- **AVAX token**: pays fees, secures the platform, fuels custom blockchain operations. Fees on C-Chain are burned.

## Proof points & flagship names (verify recency before citing)

- **Institutions**: BlackRock, Franklin Templeton, Apollo, Citi, Kinexys (J.P. Morgan), WisdomTree, Securitize, Dinari (first SEC-registered, FINRA-regulated tokenized equities network), Republic, OpenTrade, Nonco (institutional FX onchain), Intain + FIS (Digital Liquidity Gateway), state of Wyoming.
- **2026 institutional momentum**: Avalanche Payments Collective — 28 organizations, stablecoin settlement + global payout infrastructure + 24/7 money movement (Jun 2026). Progmat migrated $2B+ of tokenized securities (Japan's largest tokenized securities platform, Feb 2026). Fosun Wealth's FUSD yield-bearing RWA stablecoin (Feb 2026). Tassat's Lynq bank-grade settlement layer (Apr 2026). Kite mainnet — agent identity & payments, 1.9B interactions (Apr 2026). Asia momentum: Seoul, Bangkok, Tokyo financial institutions.
- **Consumer/gaming**: FIFA, Off The Grid (Gunzilla), MapleStory (Nexon), Beam, Tixbase, SI Tickets; music royalties in seconds via Record Financial & 11am.
- **DeFi ecosystem**: Aave, Uniswap, Euler, Benqi, LFJ, Dexalot, Pharaoh.
- **Events**: Avalanche Summit New York, Sep 16–17, 2026.

## Key properties to lean on in copy

Reliability/uptime (mainnet has never gone down — verify phrasing with brand team before external use), sub-second finality, near-zero fees (sub-cent or configurable), EVM compatibility, horizontal scalability via L1s, built-in compliance controls, native interoperability, eco-footprint (sustainability.avax.network).

## Site & channel map

- Marketing site: **avax.network** (migrating to **avalanche.com** — use avalanche.com in new brand creative; check with web team on live-link readiness)
- Solutions pages: /institutions, /enterprise, /defi, /gaming, /nft, /infrastructure, /payments, evergreen.avax.network
- Builder hub/docs: build.avax.network (docs, academy, grants, console, integrations, stats)
- Blog: avax.network/about/blog · Newsletter: Snow Report
- Social: X @avax · LinkedIn /company/avalancheavax · YouTube /Avalancheavax · Discord discord.gg/avax · Reddit r/Avax · Arena arena.social/avax
- Ecosystem: core.app/discover · Explorer: subnets.avax.network · Status: status.avax.network
- Ava Labs (company): avalabs.org · GitHub: github.com/ava-labs

## Positioning shorthand

Built for Business. Target: institutions, banks, enterprises, fintechs, asset managers, plus consumer brands that need production-grade infrastructure. Avalanche = the credible, reliable, compliance-ready chain that real businesses run in production — infrastructure, not hype.
