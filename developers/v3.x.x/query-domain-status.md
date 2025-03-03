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

   const result = await rns.getDomainStatus({domain: 'radixnameservice.xrd'});

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns an Object ⇾ Reference Type: DomainAttributesResponseT

{
   status: string, // possible fixed values ⇾ "registered" | "available" | "sunrise" | "tld" | "genus-substrate"
   verbose: string
   price: {
      xrd: string,
      usd: string
   }
}

```

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->