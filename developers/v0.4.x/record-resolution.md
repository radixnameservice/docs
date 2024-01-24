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
      directive: 'website'
   });

   console.log(resolvedRecord); // will return "https://rns.foundation"

}

statusExample();

```

#### **Expected Outputs**

```js

// returns string of objects OR null

<string>

```

<!-- tabs:end -->