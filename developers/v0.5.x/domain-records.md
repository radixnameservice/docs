# Domain Records

> Provides a list of record dockets of a corresponding domain name.

---

<!-- tabs:start -->

#### **Code Example**

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

#### **Expected Outputs**

```js

// returns array of objects OR null

[
    {
      record_id: "[<resource-id>]",
      id_additions: [],
      domain_id: "[<resource-id>]",
      context: <string>,
      directive: <string> | <null>,
      platform_identifier: <string> | <null>,
      value: <string>
   },
]

```

<!-- tabs:end -->