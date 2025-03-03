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

   const result = await rns.getRecords({domain: 'radixnameservice.xrd'});

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns an Array of Objects ⇾ Reference Type: RecordListResponseT

[
   {
      record_id: string,
      platform_identifier: string,
      domain_id: string,
      context: string, // possible fixed values ⇾ "receivers" | "delegation" | "navigation" | "social" | "discovery" | "widgets"
      value: string | null,
      directive: string,
      id_additions: string[]
   },
   {...etc},
   {...etc}
]

```

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->

To see the full list of proposed docket standards / structures, please view the [Docket Standards Section](wiki/resolution/standards.md).