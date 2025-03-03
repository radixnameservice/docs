# Domain Details

> Provides the specific details, subdomains and metadata for a specific domain name.

---

<!-- tabs:start -->

#### **Code Example**

```js
import RnsSDK from '@radixnameservice/rns-sdk';

async function detailsExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const result = await rns.getDomainDetails({domain: 'radixnameservice.xrd'});

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns an Object ⇾ Reference Type: DomainDetailsResponseT

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
         key_image_url: string,
      },
      {...etc},
      {...etc}
   ]
}

```

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->