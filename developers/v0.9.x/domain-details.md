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

   const details = await rns.getDomainDetails('radixnameservice.xrd');
   console.log(details); // will return an object containing the domain details OR a failure object

}

statusExample();

```

#### **Expected Outputs**

##### ✔️ Success

```js

// returns an object OR Null

{
   id: "[<resource-id>]",
   name: <string>,
   address: <string>,
   created_timestamp: <number>,
   last_valid_timestamp: <number>,
   key_image_url: <string>
}

```

##### ❌ Failed (Domain Input Invalid)

```js

// returns an object OR Null

{
   id: "invalid", <string>
   verbose: <string>
}

```

##### ❌ Failed (Authenticity Failure)

```js

// returns an object

{
   status: "address-mismatch",
   verbose: <string>
}

```

##### ❌ Failed (No Domain Present)

```js
// returns Null

```

<!-- tabs:end -->