# Record Resolution

> Provides the value of a specific domain record docket.

---

<!-- tabs:start -->

#### **Code Example**

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function resolverExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const resolvedRecord = await rns.resolveRecord({
      domain: 'radixnameservice.xrd',
      context: 'navigation',
      directive: 'website',
      proven: false
   });

   console.log(resolvedRecord); // will return { value: "https://rns.foundation" }

}

statusExample();

```

#### **Expected Outputs**

```js

// returns an object OR null

{
   value: "<string>",
   nonFungibleDataList?: StateNonFungibleDetailsResponseItem
}

```

<!-- tabs:end -->

[StateNonFungibleDetailsResponseItem](https://github.com/radixdlt/babylon-gateway/blob/main/sdk/typescript/lib/generated/models/StateNonFungibleDetailsResponseItem.ts#L28) refers to the tree of the RadixDLT SDK native nonFungibleDataList type interface.

To see the full list of proposed docket standards / structures, please view the [Docket Standards Section](wiki/resolution/standards.md).