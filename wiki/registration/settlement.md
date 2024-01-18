

# Settlement Periods

---

Once a user commits to a domain purchase, the domain is subject to a settlement period. The settlement period is a window of time within which a process of price and demand discovery can be determined - other parties may initiate an auction within this window if they happen to apply for the same domain. Settlement periods vary based on the character length of the corresponding domain:
<br /><br />

| Domain Length | Settlement Period |
| :-----------: | :-----------: |
| 2 characters | 96 hours |
| 3 characters | 72 hours |
| 4 characters | 64 hours |
| 5+ characters | 36 hours |
| 8+ characters | 24 hours |
| 12+ characters | 12 hours |
| 15+ characters | 4 hours |
| 18+ characters | Instant |

<br />

## FAQ

---

> #### Why not remove the settlement period altogether and just create an auction?

The main goal here is to create a user-friendly domain registration experience. Many other name services use a blind auction method, which in turn, keeps people in the dark for days as bids are submitted. The RNS Foundation expects most purchases to be generic in nature in the medium to long term (not perceived to be high-value or have any relation to rarity), so has decided to optimise the UX for such a scenario. Generic domain registration attempts would be hindered by a blind bidding process that is presented to users by many other name services, however, would greatly benefit with the settlement period mechanism, as anyone purchasing a generic domain comprised of a mediocre number of characters will likely be able to start using the domain within hours as opposed to days.

Transparency and fair value also need to be considered due to the smaller size of the network in which the Radix Name Service is launching. The settlement period strikes a fine balance between transparency, demand based fair value and usability.
<br /><br />

> #### What if domain touts or flippers attempt to intercept and resell domain to me?  

Those who originally attempt to register a domain will always receive an 'edge' in an auction if another party happens to attempt to purchase the same domain within its settlement period. The original applicant will always be compensated if they lose an auction. The 'advantage' auction process has been designed to ensure that intentions surrounding domain demand and contests are always for appropriate reasons. Tout or 'flip to originator' attempts under this mechanism will effectively be zero-sum if the original applicant cannot keep pace with the highest bid by taking advantage of their 'originators edge'. Please see more information on the [auctions](wiki/registration/auctions.md) page.