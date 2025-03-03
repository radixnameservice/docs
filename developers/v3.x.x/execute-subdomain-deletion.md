# Subdomain Deletion

>  Executes a subdomain deletion transaction via RDT.

---

<!-- tabs:start -->

#### **Code Example**

```js
import RnsSDK from '@radixnameservice/rns-sdk';

async function subdomainDeletionExample() {

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

   const result = await rns.deleteSubdomain({
      subdomain: "target-subdomain.root-domain.xrd",
      accountAddress: "account_tdx_2_1298zn26mlsyc0gsx507cc83y7x8veyp90axzh6aefqhxxq9l7y03c7"
   });

   // handle result...

}
```

#### **Expected Outputs**

[filename](./common/errors/commitment-stack.md ':include')

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->