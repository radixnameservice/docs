# Domain Auctions

> Returns a list of all domain auctions.

---

<!-- tabs:start -->

#### **Code Example**

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function getAllAuctionsExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const auctions = await rns.getAllAuctions(<cursor: number (optional)>);
   console.log(auctions); // will return an array of auction objects, total count and pagination options

}

getAllAuctionsExample();

```

#### **Expected Outputs**

```js

// returns object OR null
{
    data: [
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
        },
        {...etc},
        {...etc},
        {...etc}
    ],
    next_cursor: <null> | <number>,
    total_count: <number>
}
```

<!-- tabs:end -->