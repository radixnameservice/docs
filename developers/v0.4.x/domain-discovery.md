

# Domain Discovery

> Provides a list of domain names associated with a particular account address.

---

<!-- tabs:start -->

#### **Code Example**

```js

import RnsSDK from '@radixnameservice/rns-sdk';

async function discoveryExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const associatedDomains = await rns.getAccountDomains('account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7');
   console.log(associatedDomains); // will return array of domain names

}

discoveryExample();

```

#### **Expected Outputs**

```js

// returns array of objects OR null

[
    {
        id: "[<resource-id>]",
        name: "<domain-name>",
        subdomains: [],
        created_timestamp: <number: utc-timestamp>,
        last_valid_timestamp: <number: utc-timestamp>,
        key_image_url: "<qr-image-url>"
    },
]

```

<!-- tabs:end -->