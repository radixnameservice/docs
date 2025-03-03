# Subdomain Validation

>  Validates a subdomain name.

---

<!-- tabs:start -->

#### **Code Example**

```js
import RnsSDK from '@radixnameservice/rns-sdk';

async function domainValidationExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const result = await rns.utils.validateSubdomain({
      domain: "subdomain.target-domain.xrd",
   });

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns true

true

```

---

##### ❌ Failed (Error Stack)

```js

// Returns an Object ⇾ Reference Type: ErrorI

{
   code: string,
   error: string,
   verbose: string
}

```

<!-- tabs:end -->