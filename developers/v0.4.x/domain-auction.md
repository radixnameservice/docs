# Domain Auction

> Provides the auction status of a particular domain.

---

<!-- tabs:start -->

#### **Code Example**

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function auctionExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const auction = await rns.getAuction('nft.xrd');
   console.log(auction); // will return an auction object

}

auctionExample();

```

#### **Expected Outputs**

```js

// returns object OR null

{
    "id": "[<resource-id>]",
    "ends": <number: utc-timestamp>,
    "bids": {
        "currentBid": {
            "usd": <number>,
            "xrd": <number>
        },
        "initialBid": {
            "usd": <number>,
            "xrd": <number>
        },
        "leaderBadgeId": <string>,
        "originatorBadgeId": <string>
    }
}

```

<!-- tabs:end -->