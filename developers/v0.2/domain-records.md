# Domain Records

> Provides a list of record dockets of a corresponding domain name.

---

### Code Example

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function recordsExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const records = await rns.getRecords('radixnameservice.xrd');
   console.log(records); // will return array of record dockets

}

recordsExample();

```