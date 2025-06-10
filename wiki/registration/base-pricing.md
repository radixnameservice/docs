# Base Pricing

---

> **🎉 V2 APPROVED:** The RNS community has voted to approve the V2 upgrade! While domains are already forever assets with no expiry in the current system, V2 will introduce a "bonding" system where you can retrieve your funds. Current domain holders will need to migrate to V2 bonding once it launches. See the [RNS V2 Bonding System](wiki/registration/v2-bonding-system.md) for full details.

> **⚠️ MIGRATION COST WARNING:** Purchasing domains now (V1) means you'll need to pay **additional funds** to migrate to V2. Your V1 purchase costs are **NOT recoverable** - V2 migration requires new bond amounts. Consider this financial commitment before purchasing.

## Historical Context: Community-Driven Evolution

RNS pricing has evolved through community governance:

1. **Original System:** Domains had annual renewal fees and could expire
2. **Community Vote:** RNS community voted to eliminate renewals and make domains forever assets
3. **Current Result:** One-time purchase model with permanent ownership
4. **Recent V2 Vote:** Community approved bonding system for fund retrievability

This transition reflects the community's preference for permanent ownership over recurring fees.

## Current System

Domains are forever assets with a one-time purchase price, denominated in $ and payable in the XRD equivalent at the point of purchase. **There are no renewals or expiration dates** - this was a deliberate community decision.

**⚠️ Important:** These V1 purchase costs cannot be recovered during V2 migration.

The current pricing schedule is as follows:
<br /><br />

| Domain Length | Purchase Price <small>($ equivalent in XRD)</small> | V2 Migration Cost | Total Commitment |
| :-----------: | :-----------: | :-----------: | :-----------: |
| 2 characters | $240 (one-time, non-recoverable) | + $240 bond | = $480 total |
| 3 characters | $120 (one-time, non-recoverable) | + $120 bond | = $240 total |
| 4 characters | $40 (one-time, non-recoverable) | + $40 bond | = $80 total |
| 5+ characters | $4 (one-time, non-recoverable) | + $4 bond | = $8 total |

<br />

## Approved V2 Bonding System

Under the approved V2 system, the same pricing structure will apply but as retrievable bonds instead of one-time purchases:

| Domain Length | Bond Amount <small>($ equivalent in xUSDC/sUSD)</small> | Example |
| :-----------: | :-----------: | :-----------: |
| 2 characters | $240 (retrievable by burning domain) | hi.xrd |
| 3 characters | $120 (retrievable by burning domain) | hey.xrd |
| 4 characters | $40 (retrievable by burning domain) | hola.xrd |
| 5+ characters | $4 (retrievable by burning domain) | hello.xrd |

**Key differences in V2:**
- Bonds are paid in xUSDC or sUSD instead of XRD
- Bonds can be fully retrieved by "unbonding" **which burns the domain**
- Domains remain forever assets (no change from current system)
- Registrars can add optional "registrar fees" on top of bonds
- **Current domain holders will need to migrate with NEW funds** (V1 costs not recoverable)

**⚠️ Important Bond Retrieval:** You cannot have both the domain AND get your bond money back. Unbonding burns the domain to return the funds. For monetization while preserving the domain, trading on marketplaces is available.

## FAQ

---

> #### Should I buy domains now or wait for V2?

**There are different considerations for each approach:**
- **Buy now:** Secures the domain name immediately, but requires V1 cost + V2 migration cost
- **Wait for V2:** Only requires bond amount once but risks someone else claiming the domain
- **V1 costs are sunk costs** - they cannot be applied toward V2 bonds

Each user should evaluate their own priorities, risk tolerance, and financial circumstances.

> #### Are domains really forever now?

Yes! The RNS community voted to make domains forever assets with no expiration dates. This was a conscious decision to move away from the traditional renewal model used by other name services.

> #### What happened to renewals?

The community voted to eliminate renewals entirely. Once you purchase a domain in the current system, it's yours forever with no additional payments required. This was done to improve user experience and eliminate the fear of losing domains.

> #### Why did the community choose forever assets over renewals?

The community recognized that renewal systems create barriers to adoption, user anxiety about losing domains, and unnecessary complexity. Forever assets provide better user experience and true digital ownership.

> #### Why migrate to V2 if domains are already forever?

V2 bonding allows you to retrieve your funds **by burning the domain** if you no longer want it, whereas current purchases are permanent spends. V2 also transitions to a more stable currency (xUSDC/sUSD) and supports the move to a fully open-source project. **However, migration requires additional financial commitment.**

> #### Can I get my money back in V2?

Yes, but **only by burning the domain** through unbonding. You cannot keep the domain and get the bond back - it's one or the other. For monetizing domains while preserving them, marketplace trading is available.

> #### What's the difference between trading and unbonding?

**Trading:** Sell domain on marketplace → Get money (potentially more than bond) + buyer gets domain
**Unbonding:** Burn domain → Get exact bond amount back + domain is destroyed forever

These are two different methods with different outcomes and implications.

> #### From where is the pricing derived?

Due to the lack of battle-tested Oracles on Radix, an RNS Foundation governed sub-DAO has been set up to ensure that base pricing and corresponding pricing mechanisms are kept reasonably in line with the XRD/USD market price. Every 30 days, pricing is reviewed by the Founding team to re-calibrate pricing to the XRD/USD 30 day moving average via an internal resoultion.

> #### Why isn't the RNS based on single purchase (lifetime) domains?

It is now! The current system already provides lifetime domains with single purchases. V2 will add flexibility to this by making the bond amount retrievable while maintaining the forever asset nature of domains for as long as the user retains their bond.