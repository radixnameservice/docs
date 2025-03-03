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

   const result = await rns.getAccountDomains({accountAddress: 'account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7'});

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns an Array of Objects ⇾ Reference Type: DomainListResponseT

[
    {
        id: string,
        name: string,
        address: string,
        created_timestamp: number,
        key_image_url: string,
        subdomains: [
            {
                id: string,
                name: string,
                created_timestamp: number,
                key_image_url: string
            },
            {...etc},
            {...etc}
        ]
    },
    {...etc},
    {...etc}
]

```

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->