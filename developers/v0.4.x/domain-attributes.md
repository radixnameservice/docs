# Domain Status

> Provides the registration status of a domain name.

---

### Code Example

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function statusExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const attributes = await rns.getDomainAttributes('radixnameservice.xrd');
   console.log(attributes); // will return a list the status of the domain along with a verbose status explanation.

}

statusExample();

```