# Structure: Voting Mechanisms

This section lists the mechanisms and fixed sub-types of various proposal classifications and voting models that apply to the DAO. Each classification has a collection of functions, expected overall effect a respective proposal will have on the overall DAO, threshold required to approve various proposal types and voting models that apply to each. These mechanisms are introduced or enacted at certain points of adoption called "Eras".

---

<div style="overflow: auto;">
<table style="min-width:1280px;">

  <tr>
    <th>Classification</th>
    <th>Purpose</th>
    <th>Functions</th>
    <th>Footprint</th>
  </tr>

  <tr>
    <td>GOP</td>
    <td><strong>Core Governance Operations Proposal:</strong> These proposals affect the fundamental functionality of the core governance of the DAO.</td>
    <td>
      <ul>
        <li><em><strong>Constitutional Amendment:</strong></em> Proposition and implementation of amendments to the core constitution and voting mechanisms.</li>
        <li><em><strong>Facilitator / Oversight Resolution:</strong></em> Proposition, disputes and resolution relating to Facilitator or Oversight Committee Team structure and corresponding vesting mechanisms.</li>
        <li><em><strong>Fee Structure Change:</strong></em> Modifying the fee structure / mechanism of the service.</li>
      </ul>
    </td>
    <td>High</td>
  </tr>

  <tr>
    <td>SOP</td>
    <td><strong>Core Service Operations Proposal:</strong> These proposals affect the fundamental functionality of the protocol.</td>
    <td>
      <ul>
        <li><em><strong>Protocol Upgrade:</strong></em> Implementing a major upgrade to the protocol's core functionalities.</li>
        <li><em><strong>Protocol Amendment:</strong></em> Modifying existing core functionalities.</li>
        <li><em><strong>Hard Fork:</strong></em> Introducing a significant change that creates an backward-incompatible version of the protocol.</li>
      </ul>
    </td>
    <td>High</td>
  </tr>

  <tr>
    <td>PIP</td>
    <td><strong>Protocol Improvement Proposal:</strong> These proposals affect the DAO's operations but don't directly change the core protocol and provides funding for 3rd party initiatives with the view that such proposals will benefit the DAO and protocol as a whole.</td>
    <td>
      <ul>
        <li><em><strong>Treasury Grant Funding:</strong></em> DAO treasury funding for a specific project or initiative.</li>
        <li><em><strong>Partner Integration:</strong></em> Applications for outbound integration with another protocol or service.</li>
        <li><em><strong>Outreach & Marketing:</strong></em> Marketing and Biz Dev proposals / facilitation.</li>
      </ul>
    </td>
    <td>Moderate</td>
  </tr>

  <tr>
    <td>R&D</td>
    <td><strong>R&D Proposal:</strong> These proposals are primarily reponsible for insights and market reseach. These are non-binding proposals that act as reference points to pave the way for data-driven improvement proposals. R&D carried out under ICP's is for the ultimate benefit of the DAO, service and participants.</td>
    <td>
      <ul>
        <li><em><strong>[Example 1] Competitor Analysis:</strong></em> Evidence backed opportunities through research of other services in the Web3 space that may convert to a fully-fledged improvement proposal.</li>
        <li><em><strong>[Example 2] Strategic Direction Survey:</strong></em> Understanding member preferences for the DAO's long-term goals.</li>
        <li><em><strong>[Example 3] Community Sentiment Poll:</strong></em> Gathering member opinions on a potential future protocol upgrade.</li>
      </ul>
    </td>
    <td>Low</td>
  </tr>

  <tr>
    <td>MMP</td>
    <td><strong>Member Mediation Proposal:</strong> These proposals serve as a formal mechanism to initiate a mediated resolution process, ensuring that all parties involved have an opportunity to be heard and that a neutral facilitator can guide the process toward a mutually acceptable outcome.</td>
    <td>
      <ul>
        <li><em><strong>[Example 1] Integral Disagreements:</strong></em> Disagreements within The Radix Name Service community, particularly those related to governance, contributors, or any other operational conflicts that could arise between key DAO members.</li>
      </ul>
    </td>
    <td>Moderate</td>
  </tr>

  <tr>
    <td>PlatApp</td>
    <td><strong>Platform Provider Application:</strong> These applications allow 3rd parties to register as a commissioned platform provider.</td>
    <td>
      <ul>
        <li><em><strong>Platform Provider Badge Request:</strong></em> Issue Provider Badges to enable sales tracking (for eligible $RNS rewards) and DAO proposal / vote participation.</li>
        <li><em><strong>Platform Provider Resignation:</strong></em> Allows Platform Providers to resign as a Commissioned Platform Provider and subsequently burn Provider Badges.</li>
      </ul>
    </td>
    <td>Moderate</td>
  </tr>

  <tr>
    <td>RegApp</td>
    <td><strong>Genus Registry Application:</strong> These proposals allow Apex Handle holders to apply as genus registries.</td>
    <td>
      <ul>
        <li><em><strong>Genus Registry Request:</strong></em> Initiate new registry and sub-dao request, upon 7 day settlement will allow the applicant to issue / sell genus domains and run a corresponding sub-DAO.</li>
        <li><em><strong>Genus Registry Resignation:</strong></em> Allows Genus Registries to resign and subsequently cease all sales / issuance of genus domains and freeze the corresponding sub-DAO.</li>
      </ul>
    </td>
    <td>Low</td>
  </tr>

  <tr>
    <td>POP</td>
    <td><strong>Perpetual Operations Proposal:</strong> These proposals faciliate routine administrative tasks that allow the DAO Foundation to operate.</td>
    <td>
      <ul>
        <li><em><strong>Reimbursement Request / DAO Wrapper Renewal:</strong></em> Approving a request for reimbursement of pre-agreed operational expenses.</li>
      </ul>
    </td>
    <td>Low</td>
  </tr>

  <tr>
    <td>Bounty</td>
    <td><strong>Funded Bounties:</strong> Bounties enable the managed core build out of the DAO and RNS between Era 25k and Era 125k.</td>
    <td>
      <ul>
          <li><em><strong>Bounty Creation / Distribution:</strong></em> Creating Bounties and distributing subsquent bounty / task completion rewards.</li>
      </ul>
    </td>
    <td>High</td>
  </tr>

  <tr>
    <td>CGP</td>
    <td><strong>Community Genesis Proposal:</strong> This proposal provides the founding team with a community mandate to execute the “two year bootstrapping plan”, coordinate the development of the initial DAO structure and approves the proposed initial DAO constitution, tokenomics and the team oversight and incentive mechanism.</td>
    <td>
      <ul>
        <li><em><strong>DAO Structure:</strong></em> Approving the plans to allow the team to coordinate the initial DAO functionality and build out.</li>
        <li><em><strong>Governance Constitution:</strong></em> Approving the initial items contained within the DAO constitution and mechainsms that surround potential constitutional amendments.</li>
        <li><em><strong>Tokenomics:</strong></em> Approving the tokenomics, founding team vesting schedules and terms, and build out of the planned DAO / service based economy relating to the $RNS token and corresponding utility.</li>
        <li><em><strong>Oversight:</strong></em> Providing a firm mandate and instruction regarding the operation of an oversight committee and its role to both oversee and manage facilitator obligations, challenge any breach of obligation via given dispute routes, ensure that the DAO constitution and devolution is observed, assist with concise communication and cohesion between the founding team and community, and participate in the DAO as a whole.</li>
      </ul>
    </td>
    <td>High</td>
  </tr>

</table>

<br />
<br />

## Adoption Eras

Governance is to be progressively transferred and guard rails tapered down as protocol adoption increases. This is faciliated via devolution at certain stages of adoption called "Eras".

---

### What are Eras?

An Era within RNS governance is in place to allow DAO participants and onlookers a straightforward roadmap of entities that can exercise governance mechanisms once thresholds of adoption / maturety are met and target date for which certain protocol features go live. The threshold of adoption is directly linked to the number of  Handles currently in circulation; e.g. 25k Era = 25,000 registered Apex Handles in circulation, 50k Era = 50,000 registered Apex Handles in circulation (and so forth).

Respective Era upgrades are enacted, as pre-planned, once each corresponding threshold is met (based on the total root aliases in circulation). This managed form of devoution ensures both stability for the community and DAO participants and acts as a coeffcient during which governance mechanisms devolve. By attaching devolution events to adoption thresholds, we can help protect the DAO from the many potential threats that hostile parties pose within early stage DAO's and provides a high degree of predictability and clarity around upcoming functionalities.
<br /><br />

### What is Governance Devolution?

Devolution is a process by which the governance of the DAO becomes increasingly more 'fluid' and autonomous. At first, the DAO features various guard rails in the form of 'Facilitators'. The treasury is initially gated via a 'bounty' funding model rather than the fully comprehensive proposal funding method. These mechanisms are in place to ensure a stable bootstrapping period that protects what currently is a small DAO from exploitation and is further decentralized through a community mandate via the Genesis Vote.

Note, the Apex Protocol is still highly decentralized from genesis as clear dispute and routes of representation are available for Genus Registries and the Platform Consortium, thus, Facilitators are always held to account to honour the community mandated remit. These governance guard rails are removed in stages and entirely programmatically - this is baked into the protocol as each Adoption Era is reached.

---

Governance mechanisms devolve and respective voting criteria becomes active within the following Eras:

✅ = Permitted to raise (e.g. propose or apply).

<!-- tabs:start -->

#### **10k Era**

<div style="overflow: auto;">
<table style="min-width:1280px;">

  <tr>
    <th>Function</th>
    <th>Facilitators</th>
    <th>Platform Consortium</th>
    <th>Genus Registries</th>
    <th>Apex Handle Holders</th>
    <th>gRNS Holders</th>
    <th>Voting Model</th>
    <th>Mandate Threshold</th>
  </tr>

  <tr>
    <td>GOP's</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model -->n/a</td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>SOP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model --><strong>1 Vote Per Facilitator</strong></td>
    <td><!-- Mandate Threshold -->100% Approval (100% participation)</td>
  </tr>

  <tr>
    <td>PIP's</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model -->n/a</td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>MMP's</td>
    <td><!-- Facilitators -->n/a</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model -->n/a</td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>R&D</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model -->n/a</td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>PlatApp's</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model -->n/a</td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>RegApp's</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model -->n/a</td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>POP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model --><strong>1 Vote Per Facilitator</strong></td>
    <td><!-- Mandate Threshold -->100% Approval (100% participation)</td>
  </tr>

  <tr>
    <td>Bounties</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model --><strong>1 Vote Per Facilitator</strong></td>
    <td><!-- Mandate Threshold -->100% Approval (100% participation)</td>
  </tr>

  <tr>
    <td>CGP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->n/a</td>
    <td><!-- Voting Model --><strong>1 alias = 1 vote.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (33% Participation)</td>
  </tr>

</table>
</div>

#### **25k Era**

<div style="overflow: auto;">
<table style="min-width:1280px;">

  <tr>
    <th>Function</th>
    <th>Facilitators</th>
    <th>Platform Consortium</th>
    <th>Genus Registries</th>
    <th>Apex Handle Holders</th>
    <th>gRNS Holders</th>
    <th>Voting Model</th>
    <th>Mandate Threshold</th>
  </tr>

  <tr>
    <td>GOP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->80% Approval (33% Participation)</td>
  </tr>

  <tr>
    <td>SOP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (20% Participation)</td>
  </tr>

  <tr>
    <td>PIP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>Collateralized Endorsement.</strong></td>
    <td><!-- Mandate Threshold -->25% Collateralization Threshold</td>
  </tr>

  <tr>
    <td>MMP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (15% Participation)</td>
  </tr>

  <tr>
    <td>R&D</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (10% Participation)</td>
  </tr>

  <tr>
    <td>PlatApp's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (10% Participation)</td>
  </tr>

  <tr>
    <td>RegApp's</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>2 Week Settlement / Dispute Route.</strong></td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>POP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (5% Participation)</td>
  </tr>

  <tr>
    <td>Bounties</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (5% Participation)</td>
  </tr>

  <tr style="opacity: 0.4;">
    <td>CGP's</td>
    <td><!-- Facilitators -->-</td>
    <td><!-- Platform Consortium -->-</td>
    <td><!-- Genus Registries -->-</td>
    <td><!-- Apex Handle Holders -->-</td>
    <td><!-- gRNS Holders -->-</td>
    <td><!-- Voting Model -->-</td>
    <td><!-- Mandate Threshold -->-</td>
  </tr>

</table>
</div>

*Dropped Classifications:
- CGP's.

#### **125k Era**

<div style="overflow: auto;">
<table style="min-width:1280px;">

  <tr>
    <th>Function</th>
    <th>Facilitators</th>
    <th>Platform Consortium</th>
    <th>Genus Registries</th>
    <th>Apex Handle Holders</th>
    <th>gRNS Holders</th>
    <th>Voting Model</th>
    <th>Mandate Threshold</th>
  </tr>

  <tr>
    <td>GOP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->80% Approval (33% Participation)</td>
  </tr>

  <tr>
    <td>SOP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (20% Participation)</td>
  </tr>

  <tr>
    <td>PIP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>Collateralized Endorsement.</strong></td>
    <td><!-- Mandate Threshold -->25% Collateralization Threshold</td>
  </tr>

  <tr>
    <td>MMP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (15% Participation)</td>
  </tr>

  <tr>
    <td>R&D</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (10% Participation)</td>
  </tr>

  <tr>
    <td>PlatApp's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
     <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (10% Participation)</td>
  </tr>

  <tr>
    <td>RegApp's</td>
    <td><!-- Facilitators -->✖️</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>2 Week Settlement / Dispute Route.</strong></td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>POP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✖️</td>
    <td><!-- gRNS Holders -->✖️</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (5% Participation)</td>
  </tr>

  <tr style="opacity: 0.4;">
    <td>Bounties</td>
    <td><!-- Facilitators -->-</td>
    <td><!-- Platform Consortium -->-</td>
    <td><!-- Genus Registries -->-</td>
    <td><!-- Apex Handle Holders -->-</td>
    <td><!-- gRNS Holders -->-</td>
    <td><!-- Voting Model -->-</td>
    <td><!-- Mandate Threshold -->-</td>
  </tr>

  <tr style="opacity: 0.4;">
    <td>CGP's</td>
    <td><!-- Facilitators -->-</td>
    <td><!-- Platform Consortium -->-</td>
    <td><!-- Genus Registries -->-</td>
    <td><!-- Apex Handle Holders -->-</td>
    <td><!-- gRNS Holders -->-</td>
    <td><!-- Voting Model -->-</td>
    <td><!-- Mandate Threshold -->-</td>
  </tr>

</table>
</div>

*Dropped Classifications:
- CGP's.
- Bounties.

#### **250k Era**

<div style="overflow: auto;">
<table style="min-width:1280px;">

  <tr>
    <th>Function</th>
    <th>Facilitators</th>
    <th>Platform Consortium</th>
    <th>Genus Registries</th>
    <th>Apex Handle Holders</th>
    <th>gRNS Holders</th>
    <th>Voting Model</th>
    <th>Mandate Threshold</th>
  </tr>

 <tr>
    <td>GOP's</td>
    <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->80% Approval (33% Participation)</td>
  </tr>

  <tr>
   <td>SOP's</td>
   <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (20% Participation)</td>
  </tr>

  <tr>
    <td>PIP's</td>
    <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
   <td><!-- Voting Model --><strong>Collateralized Endorsement.</strong></td>
    <td><!-- Mandate Threshold -->25% Collateralization Threshold</td>
  </tr>

  <tr>
    <td>MMP's</td>
    <td><!-- Facilitators -->✅</td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (15% Participation)</td>
  </tr>

  <tr>
    <td>R&D</td>
    <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (10% Participation)</td>
  </tr>

  <tr>
    <td>PlatApp's</td>
    <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->n/a</td>
    <td><!-- Genus Registries -->✖️</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (10% Participation)</td>
  </tr>

  <tr>
    <td>RegApp's</td>
    <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->✖️</td>
    <td><!-- Genus Registries -->n/a</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>2 Week Settlement / Dispute Route.</strong></td>
    <td><!-- Mandate Threshold -->n/a</td>
  </tr>

  <tr>
    <td>POP's</td>
    <td><!-- Facilitators --><em>Deprecated</em></td>
    <td><!-- Platform Consortium -->✅</td>
    <td><!-- Genus Registries -->✅</td>
    <td><!-- Apex Handle Holders -->✅</td>
    <td><!-- gRNS Holders -->✅</td>
    <td><!-- Voting Model --><strong>gRNS (square rooted) + alias multiplier.</strong></td>
    <td><!-- Mandate Threshold -->51% Approval (5% Participation)</td>
  </tr>

  <tr style="opacity: 0.4;">
    <td>Bounties</td>
    <td><!-- Facilitators -->-</td>
    <td><!-- Platform Consortium -->-</td>
    <td><!-- Genus Registries -->-</td>
    <td><!-- Apex Handle Holders -->-</td>
    <td><!-- gRNS Holders -->-</td>
    <td><!-- Voting Model -->-</td>
    <td><!-- Mandate Threshold -->-</td>
  </tr>

  <tr style="opacity: 0.4;">
    <td>CGP's</td>
    <td><!-- Facilitators -->-</td>
    <td><!-- Platform Consortium -->-</td>
    <td><!-- Genus Registries -->-</td>
    <td><!-- Apex Handle Holders -->-</td>
    <td><!-- gRNS Holders -->-</td>
    <td><!-- Voting Model -->-</td>
    <td><!-- Mandate Threshold -->-</td>
  </tr>

</table>
</div>

*Dropped Classifications:
- CGP's.
- Bounties.

<!-- tabs:end -->

</div>

<!-- changelog:start -->

This is the contribution that serves to keep track of ideation sources, authorship and documentation modifications within the DAO. If you have created or contributed to an idea, or optimized the content of this page, please fill out the form to allow others to see under which context the submission occurred.

| Name  | Date            | Notes |
| :-----: | :---------------: | :---------------------------: |
| James Wylie (Wylie.xrd) | 6th Oct 2024 | Concept Ideation / Authorship |
| Ibrahim Mahmood (Beem.xrd) | 6th Oct 2024 | Suggestions - Merge voting mechanisms and eras for definition (improve clarity) |
| Faraz (Faraz.xrd) | 6th Oct 2024 | Suggestions - Grammatical Corrections |

<!-- changelog:end -->