

# Domain Discovery

> Provides a list of domain names associated with a particular account address.

---

### Code Example

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function discoveryExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const associatedDomains = await rns.getAccountDomains('account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7');
   console.log(records); // will return array of domain names

}

discoveryExample();

```