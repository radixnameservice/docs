

# Registration Lifecycle

---

Acquiring a domain involves a process of searching for a domain and, if available, committing to its [base purchase price](wiki/registration/base-pricing.md). The domain then enters a [settlement period](wiki/registration/settlement.md), which is a period of time that's allowed to pass before a user can claim the domain. This provides a window of time within which a process of price and demand discovery can be determined - other parties may initiate an auction within this window if they happen to apply for the same domain.

- If other parties are interested in the domain and the domain is within a settlement period, they will have the opportunity to participate in an [auction](wiki/registration/auctions.md). Due to the nature of our auction process, the original applicant always receives an edge within this auction and is compensated if they do not win. Please see the [auctions](wiki/registration/auctions.md) section for more information.
- If no demand arises for the domain within the settlement period, it will settle and the user can claim the domain accordingly.


Both base pricing and settlement periods are determined by domain character length.
<br /><br />

## Process

---

The registration process is as follows (infographic provided by XRD.domains):
<br /><br />

<object data="../../_assets/lifecycles/registration-lifecycle.pdf" type="application/pdf" width="100%" height="1040px">
    <embed src="../../_assets/lifecycles/registration-lifecycle.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="../../_assets/lifecycles/registration-lifecycle.pdf">Download PDF</a>.</p>
    </embed>
</object>
<br /><br />

## FAQ

---

> #### The process above may seem quite complex for non-technical users; how do you expect these users to grasp these concepts in order to onboard themselves to the Radix Name Service?

Platform providers (platforms through which domains sales are facilitated) are responsible for abstracting any complexities to cater to non-technical users.
<br /><br />

> #### Why not remove the settlement period altogether and just create an auction?

The main goal here is to create a user-friendly domain registration experience. Many other name services use a blind auction method, which in turn, keeps people in the dark for days as bids are submitted. The RNS Foundation expects most purchases to be generic in nature in the medium to long term (not perceived to be high-value or have any relation to rarity), so has decided to optimise the UX for such a scenario. Generic domain registration attempts would be hindered by a blind bidding process that is presented to users by many other name services, however, would greatly benefit with the settlement period mechanism, as anyone purchasing a generic domain comprised of a mediocre number of characters will likely be able to start using the domain within hours opposed to days.

Transparency and fair value also need to be considered due to the smaller size of the network in which the Radix Name Service is launching. The settlement period strikes a fine balance between transparency, demand based fair value and usability.
<br /><br />

> #### If I win at auction, will the renewal costs always be in line with the amount I paid for the bid?

Short answer no. It will almost certainly be way cheaper, because domain renewals always follow the [base pricing schedule](wiki/registration/base-pricing.md).
<br /><br />

> #### Huh, compensation if I lose an auction? How?

Absolutely - those who originally attempt to register a domain will always get an 'edge' in an auction if another party happens to attempt to purchase the same domain within its settlement period. The original applicant will always be compensated if they lose at auction. Please see more information on the [auctions](wiki/registration/auctions.md) page.