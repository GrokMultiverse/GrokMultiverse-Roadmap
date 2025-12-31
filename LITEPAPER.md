# GrokMultiverse Lite Paper 🌌

[![Phase 01](https://img.shields.io/badge/Phase_01-Points_Farming_LIVE-%F0%9F%9F%A2?style=for-the-badge&logo=solana)](https://grokmultiversedashboard.netlify.app/) 
[![Phase 02](https://img.shields.io/badge/Phase_02-NFT_Minting_LIVE-%F0%9F%94%A5?style=for-the-badge&logo=solana&logoColor=orange)](https://grokmultiversedashboard.netlify.app/) 
[![Phase 03](https://img.shields.io/badge/Phase_03-Mainnet_NFT_Locked-808080?style=for-the-badge&logo=solana)](https://grokmultiversedashboard.netlify.app/) 
[![Program](https://img.shields.io/badge/Program-Verified-00D1B2?style=for-the-badge&logo=solana)](https://explorer.solana.com/address/9NQgnCaAD9QYTDQsMyK2izR2mpFVcukjBKRpb3roBRLp?cluster=devnet)
[![Roadmap Status](https://img.shields.io/badge/Status-Shipping_Fast-9945FF?style=for-the-badge&logo=rocket)](https://grokmultiversedashboard.netlify.app/)

---

**Version 1.0 – Public Release**

---

## 1. Executive Summary
**GrokMultiverse** is a phased, on-chain ecosystem on Solana that rewards early users through task-based engagement, referral incentives, NFT ownership, and a points-driven token airdrop.

All GMV tokens are **minted directly via our own smart contract**, with full on-chain transparency. No seed rounds, private sales, or pump/fun mechanisms are involved. Selected off-chain signals (e.g., NFT trading volume) are integrated via admin-verified updates.

---

## 2. Vision & Objectives
- Build a **self-governed token ecosystem** through your own smart contract  
- Reward **real participation**, not capital dominance  
- Maintain **full on-chain transparency**  
- Use **phased unlocks** for controlled ecosystem growth  
- Separate **testing (Devnet)** from **value-carrying assets (Mainnet)**  

---

## 3. Ecosystem Architecture
- Single upgradeable Solana program (Anchor framework)  
- Manages PDAs, referral tracking, task verification, NFT mint eligibility, phase locks, token vault, airdrop distribution  
- Same logic on Devnet & Mainnet  

---

## 4. Phase-Based Lifecycle
- **Phase 1:** Points Farming & Referral  
- **Phase 2:** Devnet NFT Mint (Early Bird)  
- **Phase 3:** Mainnet NFT Mint  
- **Phase 4:** NFT Trading Enablement  
- **Phase 5:** Tokenomics & Documentation  
- **Phase 6:** Token Launch & Airdrop  

---

## 5. Referral & Badge System
- Unique referral ID per wallet  
- Direct referrals only  
- 500 points per successful referral  
- Badge levels stored on-chain & reflected in NFT metadata  

---

## 6. Task & Point System
| Action | Points |
|--------|--------|
| Initial wallet interaction | 1,000 |
| Social task completion | 100 per task |
| Referral | 500 per referral |

**Total base task points:** 1,400  
All completions stored on-chain in User PDA

---

## 7. NFT Framework
### Devnet NFT
- Purpose: testing & eligibility  
- No royalties  
- Fully visible metadata  
- Max supply: 500,000  

### Mainnet NFT
- Eligibility: Devnet NFT holders  
- One per wallet  
- Royalties: 7%  
- Metadata revealed after Phase 3 unlock  
- Max supply: 500,000  

Minted via **Metaplex Token Metadata** with verified collections

---

## 8. Tokenomics
**Token Symbol:** GMV  
**Total Supply:** 21,000,000

| Allocation | Percentage |
|------------|------------|
| Community Airdrop | 40% |
| Team (5-Year Vesting) | 40% |
| Maintenance | 10% |
| Marketing | 9% |
| Donation | 1% |

> All GMV tokens are minted **via the GrokMultiverse smart contract**; no third-party or speculative presale mechanisms are used.

---

## 9. Airdrop Distribution Model
**Eligibility Requirements**
- Hold a Mainnet NFT  
- Complete base tasks (≥ 1,400 points)  
- ≥ $100 verified NFT trading volume  
- Not claimed previously  
- Phase 6  

**Distribution Formula**
```text
UserPoints = TaskPoints + (ReferralCount × 500)
TotalSystemPoints = Sum of all eligible users’ points
UserAirdrop = (UserPoints × 8,400,000) / TotalSystemPoints

8,400,000 = 40% of total token supply


## 10. Post-Airdrop Utility

After the airdrop, **GrokMultiverse** continues engagement via:

- NFT utility & secondary market trading  
- Points & gamified engagement (leaderboards, badges)  
- Token utility: governance, staking, exclusive access  
- Dashboard metrics & interaction  
- Referral-driven community growth  

### Feature – Post-Airdrop Fuel

| Feature | Post-Airdrop Value |
|---------|------------------|
| NFT Mint | Trading & rarity-driven value |
| Points / Tasks | Leaderboards & badges |
| Token | Governance, staking, access |
| Dashboard | Continuous engagement |
| Referral | Community adoption |

---

## 11. Post-Airdrop Sustainability

- Seasonal competitions & leaderboard resets  
- Badge upgrades & achievements  
- NFT rarity events & collaborations  
- Token-governed ecosystem features  
- Community-driven development proposals  

> Sustainability relies on **long-term NFT & token utility, gamified engagement, and active community participation**

---

## 12. References & Links

- Dashboard: [https://grokmultiversedashboard.netlify.app](https://grokmultiversedashboard.netlify.app)  


© GrokMultiverse 2025 – All rights reserved
