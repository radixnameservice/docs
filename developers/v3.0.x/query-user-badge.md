# User Badge

> Returns the RNS Badge ID for a particular account address.

---

<!-- tabs:start -->

#### **Code Example**

```js
import RnsSDK from '@radixnameservice/rns-sdk';

async function userBadgeExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const result = await rns.getUserBadge({accountAddress: "account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7"});

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns an Object ⇾ Reference Type: UserBadgeResponseT

{
   id: string | null
}

```

---

##### ✔️ Empty (Example)

```js

// Returns null

null

```

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->