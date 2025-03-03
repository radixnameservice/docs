# Record Amendment

>  Executes a record amendment transaction via RDT.

---

<!-- tabs:start -->

#### **Code Example**

```js
import RnsSDK from '@radixnameservice/rns-sdk';

async function recordAmendmentExample() {

   const rdt = RadixDappToolkit({
      networkId: RadixNetwork.Stokenet,
      applicationVersion: "1.0.0",
      applicationName: "RNS Examples",
      applicationDappDefinitionAddress: "account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7",
   });

   const rns = new RnsSDK({
      network: 'stokenet', // or mainnet
      rdt // RDT is a required dependency
   });

   const result = await rns.amendRecord({
      subdomain: "target-domain.xrd",
      accountAddress: "account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7",
      docket: {
         context: 'navigation',
         directive: 'website',
         value: 'https://radixnameservice.com'
      }
   });

   // handle result...

}
```

#### **Expected Outputs**

[filename](./common/errors/commitment-stack.md ':include')

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->

To see the full list of proposed docket standards / structures, please view the [Docket Standards Section](wiki/resolution/standards.md).