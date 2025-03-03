# Record Resolution

> Provides the value of a specific domain record docket.

---

<!-- tabs:start -->

#### **Code Example**

```js
import RnsSDK from '@radixnameservice/rns-sdk';

async function resolverExample() {

   const rns = new RnsSDK({
      network: 'stokenet' // or mainnet
   });

   const result = await rns.resolveRecord('radixnameservice.xrd', {
      context: 'navigation',
      directive: 'website'
   });

   // handle result...

}
```

#### **Expected Outputs**

##### ✔️ Success (Example)

```js

// Returns an Object ⇾ Reference Type: ResolvedRecordResponseI

{
   value: string,
   nonFungibleDataList?: StateNonFungibleDetailsResponseItem[]
}

```

[StateNonFungibleDetailsResponseItem](https://github.com/radixdlt/babylon-gateway/blob/main/sdk/typescript/lib/generated/models/StateNonFungibleDetailsResponseItem.ts#L28) refers to the tree of the RadixDLT SDK native nonFungibleDataList type interface.

---

##### ✔️ Empty (Example)

```js

// Returns null

null

```

---

[filename](./common/errors/error-stack.md ':include')

<!-- tabs:end -->

To see the full list of proposed docket standards / structures, please view the [Docket Standards Section](wiki/resolution/standards.md).