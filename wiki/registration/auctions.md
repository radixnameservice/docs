

# Advantage Auctions

---

If other parties are interested in a domain and the domain is within a [settlement period](wiki/registration/settlement.md), they will have the opportunity to participate in an auction. Many other name services utilise blind bidding to facilitate domain acquisition, however, this method may be frustrating to users, especially those attempting to secure a straightforward, generic domain. The RNS is presented with the following questions:

- How can one provide everybody a fair chance to purchase what are perceived to be valuable domain names without compromising great user experience (such as facilitation via blind auctions that last days)?
- How can a name service create a more user friendly purchase process other than using blind auctions for those wanting to purchase generic domains and also protecting them from interception and flippers?
- How do domains achieve fair market value based on demand?

The RNS Foundation have worked hard to find a reasonable solution based on a number of trade-offs, market efficiency and psychology: The <strong>'Advantage Auction'</strong>. This type of auction:

- Enforces any parties other than the original applicant top submit a 20% overbid atop of the current price or bid amount. This is also subject to compounding.
- Provides the original applicant with an 'edge'. This is called an <strong>'originators edge'</strong>. This means the original applicant will only need to meet just over the current bid to overbid without being charged a premium.

When initiated, the total duration of an advantage auction is exactly 48 hours after the end of what's remaining of the settlement period of the domain in question. <small>(settlement period remaining + 48 hours)</small>

---

Please see the example flow of the advantage auction in the infographic (provided by XRD.domains) below:
<br /><br />

<object data="../../_assets/lifecycles/advantage-auction-example.pdf" type="application/pdf" width="100%" height="1040px">
    <embed src="../../_assets/lifecycles/advantage-auction-example.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="../../_assets/lifecycles/advantage-auction-example.pdf">Download PDF</a>.</p>
    </embed>
</object>
<br /><br />

Advantage auctions strike a balance between those bidding for perceived value, and those bidding purely for utility of the domain (such as a blog or new dApp). The core benefits are that:

- Generic domain applicants receive a degree of protection from flip attempts as bidding close to the minimum bid requirement will allow the original applicant to easily compete, and each consecutive bid eats into a potential flip margin. If the original applicant cannot use their 'originators edge' to keep pace with the highest bid, then they're unlikely going to pay the premium a domain flipper may demand at the end of the contest. Overbidding for a domain that may not be resalable adds a high amount of risk for a flipper, as there's no guarantee that they'll be able to resell the domain for a higher price than paid at auction.

- Enables a streamlined and intuitive user experience when acquiring Web3 domains. An auction process within which people know exactly where they and others stand is what many have come to expect as a result of Web2 auction processes. Advantage auctions effectively yield the best of both worlds.

- It provides a totally transparent auction process that ensures the Foundation receives a fair market price for domains that are perceived to be valuable. This amount of transparency allows other interested parties to be prompted to participate rather than stealth blind bids taking place in the background, either by bots or otherwise.


## FAQ

---

> #### The process above may seem quite complex for non-technical users; how do you expect these users to grasp these concepts in order to onboard themselves to the Radix Name Service?

Platform providers (platforms through which domains sales are facilitated) are responsible for abstracting any complexities to cater to non-technical users.
<br /><br />

> #### Doesn't this incentivise flippers to build bots and always be first to reserve a generic name?

Anybody can register as many domains as they wish, however, there's no way a domain flipper can front-run a generic domain name registration attempt before an interested party attempts to purchase the domain name in question. Knowledge of interest for a specific domain name will be required for flip attempts and the original applicant would hold an originators edge as soon as the domain interest is revealed.
<br /><br />

> #### What about a bot advantage for what are perceived to be valuable domain names?

Locking in funds for hundreds of domains would be incredibly expensive, however, not impossible. The advantage auction mechanism is primarily designed and UX optimised for generic purchases - theoretically speaking, for perceived premium domain edge cases, a certain party is going to pay up to a certain ceiling for a domain name or several domain names regardless of the auction mechanism and this represents fair market value. An advantage auction will provide 100% opportunity transparency for all users under these circumstances and provides the auction process with a fine balance between first come, first served and highest price offered.