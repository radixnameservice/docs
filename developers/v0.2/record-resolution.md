# Record Resolution

> Provides the value of a specific domain record docket.

---

### Code Example

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function resolverExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const resolvedRecord = await rns.resolveRecord({
      domain: 'radixnameservice.xrd',
      context: 'navigation',
      directive: 'web2'
   });

   console.log(resolvedRecord); // will return "rns.foundation"

}

statusExample();

```