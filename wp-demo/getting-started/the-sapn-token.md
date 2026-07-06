# The SAPN Token

| Token name              | Sapling Network                                |
| ----------------------- | ---------------------------------------------- |
| Ticker                  | **SAPN**                                       |
| Blockchain              | Solana (SPL)                                   |
| Contract (mint) address | `8hrr2aSkj4fCK57zuPn8BbCL2mqehENzbNvrSRSnBTSU` |
| Maximum supply          | **100,000,000 SAPN** (fixed forever)           |
| Decimals                | 9                                              |

#### 5.1 Fixed supply — verifiable on-chain

SAPN's supply can never increase. The token's **mint authority and freeze authority have been permanently revoked** on-chain, which any user can independently verify on Solana explorers. There is no mechanism — including for the team — to create additional tokens or freeze user accounts.

#### 5.2 Token history and the v1 → v2 migration

Sapling Network's origins predate this whitepaper: the original SAPN token (`E52bRrLGu1YFHBLNTWhdeGoYKyp1UYCTjB7XPoFgapYS`) was minted by the founding wallet in **September 2021**. Its on-chain metadata, however, was registered in that era through a third-party service that retained metadata update authority — an unacceptable long-term risk for the project's integrity.

In **July 2026**, the same founding wallet minted the current SAPN token with fully self-owned metadata, and the entire 100,000,000 supply of v1 was **permanently burned** (v1 supply on-chain: 0). No v1 tokens were ever sold or distributed, so no holder was affected. The complete history — 2021 origin, 2026 migration, burn transaction — is publicly auditable on-chain.
