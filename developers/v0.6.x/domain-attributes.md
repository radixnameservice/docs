# Domain Status

> Provides the registration status of a domain name.

---

<!-- tabs:start -->

#### **Code Example**

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

#### **Expected Outputs**

```js

// returns an object OR null

{
   status: "registered",
   verbose: "radixnameservice.xrd is registered."
}

```

#### Response Variants:

<details>
<summary>object ⇾ status</summary>

Registry status of a particular domain name:

| Value | Type |
| ----------- | ----------- |
| available | String |
| registered | String |
| settlement | String |
| auction | String |
| sunrise | String |
| tld | String |
| genus-substrate | String |

</details>

<!-- tabs:end -->