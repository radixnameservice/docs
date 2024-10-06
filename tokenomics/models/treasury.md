# Models: Treasury

**The official treasury vault domain / address:**<br />
vault://treasury.rns
{{vault-address-here}}

**$XRD Reserves:** ~3,000,000 XRD<br />
**$RNS Reserves:** 0 RNS<br />
**LP Pools:** 0 RNS / 0 XRD

---

## Treasury Unlock Events

The Treasury Unlock Event is a structured funding mechanism designed to ensure Protocol Improvement Proposals (PIPs) and other DAO initiatives are financed with accountability and community participation. It operates through the issuance of Treasury Mandate Badges, which are granted to those that are provided a mandate to withdraw such funds via an official DAO proposal mechanism.


<!-- tabs:start -->

#### **PIP's**

The Treasury Unlock Event balances accountability, efficiency, and community involvement. The use of Stage Collateralization Levels ensures that projects with strong backing progress smoothly through automatic badge releases, while the involvement of Platform Providers guarantees that undercollateralized proposals are scrutinized and assessed at every phase. This dual mechanism ensures the careful and responsible use of treasury funds.

#### Overcollateralization Threshold

The Overcollateralization Threshold refers to the point at which a proposal has secured collateral exceeding the required percentage for a given stage of funding. If a proposal reaches or surpasses this threshold, it becomes eligible for automatic badge issuance at each subsequent stage based on predefined time intervals, bypassing the need for a governance vote.

#### Unlocking PIP Funds: The 5-Stage Process

For each proposal, funds are released in five phases, triggered by the issuance of Treasury Mandate Badges. These badges are granted based on progress, and the proposal's Stage Collateralization Level plays a critical role in determining whether badges are issued automatically or require community input.

##### Stage 1: Commencement Threshold

**Criteria:** The first badge is awarded once the proposal reaches its Commencement Threshold, which requires 25% of the total treasury ask to be backed by community collateralization. This phase initiates the project.<br />
**Badge Issuance:** A governance vote ensures that the project meets the commencement criteria, and the first Treasury Mandate Badge is issued.<br />
**Unlock:** The badge is burned in exchange for the release of the first tranche of funds (20% of the total ask).

##### Stage 2: Early Progress

**Criteria:** The second badge is either automatically issued if the proposal reaches the Overcollateralization Threshold, which allows for auto-release of badges at specific time intervals. If the proposal is not overcollateralized, the DAO's Platform Providers are called upon to vote on whether the badge should be issued based on progress.<br />
**Badge Issuance:** A vote by Platform Providers is triggered if the proposal does not meet the overcollateralization requirements. If the vote passes, the second badge is granted.<br />
**Unlock:** This badge unlocks the next portion of treasury funds, allowing the project to proceed.

##### Stage 3: Midpoint Milestone

**Criteria:** At the halfway point, the third badge is awarded if the proposal has hit its milestone. If overcollateralized, the Stage Collateralization Level ensures the badge is issued automatically once 3/5ths of the project timeline has passed. Otherwise, the Platform Providers will vote again.<br />
**Badge Issuance:** Either an automatic release (if overcollateralized) or a platform provider vote is required.<br />
**Unlock:** This triggers the release of the third tranche of funds.

##### Stage 4: Final Development Stage

**Criteria:** In the final phase of development, the fourth badge is issued based on progress. If the project remains undercollateralized, the Platform Providers will vote to approve or deny the badge, ensuring all criteria have been met before moving into final completion.<br />
**Badge Issuance:** If 4/5ths of the timeline has passed and the project remains overcollateralized, the badge is released automatically. Otherwise, the platform provider vote is needed.<br />
**Unlock:** The fourth tranche of funds is released, enabling the project to move toward completion.

##### Stage 5: Completion & Final Review

**Criteria:** The fifth and final badge is awarded upon successful completion of the project, and only after all milestones and objectives have been met.<br />
**Badge Issuance:** Whether or not overcollateralized, the final stage requires a formal vote by the DAO to confirm successful completion.<br />
**Unlock:** The final tranche of funds is released, marking the full completion of the treasury unlock process.

#### Stage Collateralization Levels & Auto-Release Mechanism

If a proposal reaches the Overcollateralization Threshold at any given stage, the corresponding Treasury Mandate Badge is released automatically once the project hits its timeline milestone (e.g., 2/5ths, 3/5ths, or 4/5ths of the total timeline). This auto-release mechanism ensures projects with substantial community backing continue seamlessly.

If the proposal is not overcollateralized, the DAO’s Platform Providers are called upon to vote on whether the project has met the criteria to receive the next badge. This added layer of governance provides an additional check and balances for proposals that require more scrutiny or have less community backing.

#### Specific Traits

- **Badge Expiry:** Each Treasury Mandate Badge is valid for 3 months after issuance. If not used, it expires, encouraging timely project execution.
- **Burning Mechanism:** Once a badge is used to unlock treasury funds, it is burned to maintain transparency and accountability.
- **Auto-Release for Overcollateralized Proposals:** Proposals that exceed the required collateral levels benefit from auto-release mechanisms at each stage, reducing the need for manual governance votes as long as time-based milestones are met.

#### Platform Providers' Role

When a project is undercollateralized, Platform Providers serve as the governance layer that determines whether badges are issued at each stage. They assess the progress of the proposal based on reports, milestones, and deliverables, voting to either release or withhold the badge.

Platform Providers are integral to maintaining project quality, particularly when overcollateralization is not achieved. Their votes ensure that proposals with less community backing are still thoroughly evaluated for merit and progress.

##### Proposal Lifecycle and Accountability

Throughout the proposal’s lifecycle:

- Progress Updates: Proposers are required to submit regular updates and review requests at each phase. This ensures transparency and continued engagement from both the community and Platform Providers.
- Community & Platform Scrutiny: Each stage requires either automatic approval (if overcollateralized) or active governance by Platform Providers to ensure the proposal stays on track.
- Engagement & Stream Rewards: $RNS holders who collateralize proposals receive Stream Rewards, incentivizing participation and trust in the process.

##### Completion and Treasury Management

Once the proposal is completed:
- Final Deliverables: The proposer presents a final report and strategy detailing the outcomes, which must be approved by the DAO.
- Unlock of Collateral: Upon completion, all collateral is released, and any accrued Stream Rewards become available for withdrawal.

If the proposal fails to meet its obligations:
- Desertion Clause: If the proposal is abandoned or significantly delayed (beyond a buffer period of 50% past the timeline), the locked collateral is forfeited to the DAO Treasury for future projects.

#### **POP's**

Perpetual Operations Proposals are essential for the ongoing administrative functions and routine tasks that allow the DAO Foundation to operate efficiently. These proposals typically cover areas such as reimbursement requests and operational expenses. While less complex than Protocol Improvement Proposals, Perpetual Operations Proposals still require a structured process to ensure transparency, accountability, and proper use of DAO treasury funds.

#### Treasury Badge Issuance

##### 1. Proposal Submission:

- The individual or entity submitting the proposal outlines the operational expense (e.g., reimbursement for an incurred expense, or renewal of services).
- The proposal must include supporting documents such as invoices, receipts, or pre-approved budgets for verification.

##### 2. Review and Voting:

- The community reviews the proposal through the governance portal. For routine expenses, the DAO may have pre-agreed parameters that streamline this process.
- Platform Providers and community members vote on whether the proposal meets the criteria for fund release. Given the nature of Perpetual Operations Proposals, these are often lower risk and more procedural in nature.

##### 3. Mandate Badge Issuance:

- Once approved, a Treasury Mandate Badge is issued, representing approval for the fund release. Since these requests typically address immediate needs, the badge is usually released in one stage, unlike Protocol Improvement Proposals, which require multiple phases.
- Overcollateralization Thresholds do not apply to Perpetual Operations Proposals because they deal with specific operational needs, rather than phased project funding.

##### 4. Badge Redemption and Expiry:

- Once the badge is issued, it can be redeemed in exchange for the corresponding treasury funds. Like other Treasury Mandate Badges, these are burned upon redemption.
- To ensure timely action, the badges expire within 3 months of issuance, creating urgency for requesters to follow through with their proposals.


#### **Bounties**

Bounties are created by Facilitators and typically derived from Community Governance Proposal (CGP) requirements. This ensures that the tasks align with the broader goals of the DAO and act as a precursor to more expansive Protocol Improvement Proposal (PIP)-derived Treasury Grants, providing structure and control in the DAO's formative stages. Flexibility is maintained, however, through the ability to create additional bounties based on community feedback and emerging needs or flashpoints.

#### Treasury Mandate Badge Issuance:

Like Protocol Improvement Proposals (PIPs), bounty fulfillment is tied to the issuance of Treasury Mandate Badges. These badges are a mechanism to release treasury funds at various stages of bounty fulfillment and ensure accountability.

**1. Stage-Based Completion:** As each stage of the bounty is completed, the winning tender can request a Treasury Mandate Badge to unlock funds for that phase.<br />
**2. Review and Approval:** Facilitators review the deliverables to ensure the stage is completed according to the agreed specifications. If satisfied, the badge is released.<br />
**3. Redemption:** The badge can be redeemed for treasury funds. Like other badges, they are burned upon redemption to avoid double-dipping or misuse.<br />
**4. Expiration:** Treasury Mandate Badges have an expiration period of 3 months from the date of issuance, ensuring that claimants act promptly.

<!-- tabs:end -->