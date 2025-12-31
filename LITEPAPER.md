# GrokMultiverse Lite Paper

[![Phase 01](https://img.shields.io/badge/Phase_01-Points_Farming_LIVE-%F0%9F%9F%A2?style=for-the-badge&logo=solana)](https://grokmultiversedashboard.netlify.app/) 
[![Phase 02](https://img.shields.io/badge/Phase_02-NFT_Minting_LIVE-%F0%9F%94%A5?style=for-the-badge&logo=solana&logoColor=orange)](https://grokmultiversedashboard.netlify.app/) 
[![Phase 03](https://img.shields.io/badge/Phase_03-Mainnet_NFT_Locked-808080?style=for-the-badge&logo=solana)](https://grokmultiversedashboard.netlify.app/) 
[![Program](https://img.shields.io/badge/Program-Verified-00D1B2?style=for-the-badge&logo=solana)](https://explorer.solana.com/address/9NQgnCaAD9QYTDQsMyK2izR2mpFVcukjBKRpb3roBRLp?cluster=devnet)
[![Roadmap Status](https://img.shields.io/badge/Status-Shipping_Fast-9945FF?style=for-the-badge&logo=rocket)](https://grokmultiversedashboard.netlify.app/)











**Version 1.0 – Public Release**

---

## 1. Executive Summary

**GrokMultiverse** is a phased, on-chain ecosystem built on Solana that rewards early users through transparent participation mechanisms including task-based engagement, referral incentives, NFT ownership, and a points-driven token airdrop.

The project emphasizes **fair distribution**, **on-chain verifiability**, and **progressive decentralization** through a clearly defined phase system. All critical eligibility conditions are enforced on-chain, while selected off-chain signals (such as NFT trading volume) are integrated through admin-verified updates.

---

## 2. Vision & Objectives

The core objectives of GrokMultiverse are:

- Establish a **fair-launch ecosystem** without private sales
- Reward **real participation**, not capital dominance
- Maintain **full on-chain transparency**
- Use **phased unlocks** for controlled ecosystem growth
- Separate **testing (Devnet)** from **value-carrying assets (Mainnet)**

---

## 3. Ecosystem Architecture

GrokMultiverse is powered by a **single upgradeable Solana program** built using the Anchor framework.

The program manages:

- User participation accounts (PDAs)
- Referral tracking
- Task verification and point accrual
- NFT mint eligibility and supply limits
- Phase locking and unlocking
- Token vault and airdrop distribution

The same logic is deployed across **Devnet and Mainnet**, with environment-specific configuration and program IDs.

---

## 4. Phase-Based Lifecycle

GrokMultiverse progresses through **six on-chain enforced phases**:

### Phase 1 – Points Farming & Referral
Users earn points through:
- Initial wallet interaction
- Completing community and social tasks
- Direct referrals

### Phase 2 – Devnet NFT Mint (Early Bird)
Eligible users mint a **Devnet Early Bird NFT**, acting as a participation credential.

Minting access is controlled using tiered eligibility enforced on-chain.

### Phase 3 – Mainnet NFT Mint
Only Devnet NFT holders can mint the **Mainnet NFT**, limited to one NFT per wallet.

### Phase 4 – NFT Trading Enablement
NFT trading is enabled via metadata unlock, allowing secondary trading platforms such as Magic Eden.

### Phase 5 – Tokenomics & Documentation
Full tokenomics and technical disclosures are released.

### Phase 6 – Token Launch & Airdrop
Eligible users claim tokens based on verified participation metrics.

---

## 5. Referral & Badge System

Each user receives a unique referral identifier derived from their wallet address.

- Direct referrals only (no multi-level rewards)
- Each successful referral grants **500 points**
- Badge levels are calculated based on total referral count

Badge levels are stored on-chain and reflected in user profiles and NFT metadata.

---

## 6. Task & Point System

Users earn points through verifiable actions:

| Action | Points |
|------|--------|
| Initial wallet interaction | 1,000 |
| Social task completion | 100 per task |
| Referral | 500 per referral |

**Total base task points:** 1,400

All task completions and point balances are stored in the user’s on-chain PDA.

---

## 7. NFT Framework

### Devnet NFT
- Purpose: testing, access control, eligibility tracking
- No royalties
- Fully visible metadata
- Maximum supply: **500,000**

### Mainnet NFT
- Eligibility: Devnet NFT holders only
- One NFT per wallet
- Royalties: **7%**
- Metadata revealed after Phase 3 unlock
- Maximum supply: **500,000**

NFTs are minted using **Metaplex Token Metadata** with verified collections.

---

## 8. Tokenomics

**Token Symbol:** GMV  
**Total Supply:** 21,000,000

| Allocation | Percentage |
|----------|------------|
| Community Airdrop | 40% |
| Team (5-Year Vesting) | 40% |
| Maintenance | 10% |
| Marketing | 9% |
| Donation | 1% |

No seed, private, or public presales are conducted.

---

## 9. Airdrop Distribution Model

### Eligibility Requirements

To claim the airdrop, users must:
- Hold a Mainnet NFT
- Complete all base tasks (≥ 1,400 points)
- Achieve ≥ $100 verified NFT trading volume
- Not have claimed previously
- Be in Phase 6

### Distribution Formula

```text
UserAirdrop =
(UserPoints × 8,400,000) / TotalSystemPoints

---

# Post-Airdrop Utility

Even after the airdrop phase concludes, the **GrokMultiverse ecosystem** continues to thrive by providing long-term value and engagement opportunities to its community.  

## Key Drivers

1. **NFT Utility & Trading**
   - Mainnet NFT holders can trade on Magic Eden and secondary marketplaces.
   - NFT ownership, rarity, and tier-based badges create ongoing value and engagement.

2. **Points & Gamified Engagement**
   - Tasks, referrals, and leaderboard rankings continue to incentivize user participation.
   - Badge upgrades and achievement recognition maintain community activity.

3. **Token Utility**
   - Tokens can be used for governance: vote on future NFT releases or project upgrades.
   - Access exclusive features, events, or staking rewards for token holders.

4. **Community Growth**
   - Referrals and participation loops drive organic growth and adoption.
   - Active members influence ecosystem development and future roadmap phases.

5. **Dashboard & Tools**
   - On-chain and off-chain metrics (points, NFT stats, leaderboards) keep users engaged.
   - Provides visibility into achievements and progress within the ecosystem.

## Sustainability Summary

| Feature | Post-Airdrop Fuel |
|---------|------------------|
| NFT Mint | Secondary market trading, rarity-driven value |
| Points / Tasks | Leaderboards, badges, engagement loops |
| Token | Governance, staking, access to exclusive features |
| Dashboard | Continuous user interaction and metrics |
| Referral | Community-driven growth and adoption |

> **Insight:** The airdrop acts as an initial kickstart. Long-term ecosystem sustainability relies on **NFT utility, token utility, community participation, and gamified engagement** to maintain growth and activity.
