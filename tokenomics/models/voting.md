# Models: Voting

The Radix Name Service employs a locking mechanism for $RNS tokens to ensure Sybil protection while maintaining flexibility and enabling concurrent voting. This approach enhances the protocol’s governance by incentivizing participation and preventing abuse, without relying on manual snapshot processes. Here are the key components of the $RNS token locking mechanism.

---

## Locking Mechanism Overview

### Locking Periods

**LP Tokens:** Liquidity Provider (LP) tokens are locked for a period of 7 days.<br />
**Collateral:** Tokens used as collateral for proposals are locked until the proposal's completion or resignation.

In return for locking $RNS tokens, participants receive $gRNS tokens, which are soulbound governance tokens used to vote on DAO matters. This mechanism ensures that voting power is tied to active participation and commitment to the DAO.

### Technical Specifications

##### 1. Token Locking Details

**LP Tokens:** When liquidity providers deposit LP tokens into The Radix Name Service, these tokens are locked for 7 days. This lockup ensures stability and prevents rapid fluctuations in liquidity that could impact the protocol.<br />
**Collateral Locking:** Tokens committed as collateral for Protocol Improvement Proposals (PIPs) or other DAO-related activities are locked until the associated proposal is either completed or formally withdrawn. This lock-up period helps ensure that participants are committed to the outcomes of their proposals.

##### 2. $gRNS Token Issuance

**Issuance Mechanism:** Participants receive $gRNS tokens on a 1:1 basis relative to the amount of $RNS locked. For instance, if a participant locks 1,000 $RNS tokens, they receive 1,000 $gRNS tokens.<br />
**Soulbound Nature:** $gRNS tokens are soulbound to the address that locked the $RNS tokens. This means they cannot be transferred or sold, ensuring that voting power remains tied to the original participant's commitment.

##### 3. Sybil Protection and Voting Flexibility

**Sybil Protection:** The locking mechanism mitigates Sybil attacks by requiring participants to lock tokens to receive $gRNS tokens. This discourages the creation of multiple addresses to gain voting power without real commitment.<br />
**Concurrent Voting:** The $gRNS system allows for free and concurrent voting without the need for manual snapshots. Since $gRNS tokens are issued based on token locking actions, votes can be cast in real-time, enabling a highly scalable and responsive governance process.

##### 4. Voting Rights and Delegation

**Voting Rights:** $gRNS tokens grant voting rights within the DAO. Token holders can vote on proposals and governance issues, contributing to the decision-making process.<br />
**Delegation:** While $gRNS tokens are soulbound, participants can delegate their voting rights to trusted representatives. Delegation is managed through a delegation badge, which tracks the delegated voting power. This system ensures that even soulbound tokens can be effectively utilized for governance while maintaining Sybil protection.

##### 5. No Snapshot Requirements

**Automated Voting:** The locking mechanism and $gRNS issuance ensure that voting does not require manual snapshots. Voting power is automatically adjusted based on the amount of $RNS locked, enabling a seamless and decentralized voting process.

By implementing this token locking mechanism, The Radix Name Service effectively balances the need for sybil protection with the desire for an agile, real-time decentralized governance system with reduced administrative overhead.

<!-- changelog:start -->

This is the contribution that serves to keep track of ideation sources, authorship and documentation modifications within the DAO. If you have created or contributed to an idea, or optimized the content of this page, please fill out the form to allow others to see under which context the submission occurred.

| Name  | Date            | Notes |
| :-----: | :---------------: | :---------------------------: |
| James Wylie (Wylie.xrd) | 6th Oct 2024 | Concept Ideation / Authorship |

<!-- changelog:end -->