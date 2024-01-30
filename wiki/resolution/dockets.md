

# Dockets

---

As one would probably assume, Radix Name Service domains enable a variety of use cases within dApps and web3 related tools via records. Records are composed of record "dockets".<br />

#### Anatomy of a Docket

A docket is essentially a compact object of metadata that allows any dApps / integrations to query domain records within the most applicable scope and context.
<br />

<div style="max-width:1024px">

| Docket Field | Purpose | Example |
| :-----------: | :-----------: | :----------- |
| <strong>context</strong> | The wider context of the record. | Browser usage would command a 'navigation' context and a wallet would command a 'receiver' context. Two different contexts for two completely separate use cases. |
| <strong>directive</strong> | Narrows down the context to a more granular level. | Staking usage within a wallet would request a 'delegation' context (as per above), however, many different staking mechanisms many exist for different tokens. For Radix, an 'xrd' directive can be set and requested for an XRD specific validator delegation. |
| <strong>value</strong> | The record value. | This is value of the corresponding context / directive pair as set by the domain controller. |
| <strong>platform_identifier</strong> | An optional field for custom platform specific data. | Allows pure dApp based platform providers to attach custom platform specific data, but also retain standard usage for a particular context. XRD Domains, for example, leverages this field to allow users to add "XRD Domains widgets" to their domains and also utilise widget specific 'navigation' contexts. |

</div>
<br />

##### Docket Usage Example

<strong>Goal</strong>
<summary>Controller of <u>rnsfoundation.xrd</u> has set records which allows IPFS content when users navigate to <u>rnsfoundation.xrd</u> through a web3 specific browser (via an RNS compatible web extension), however, also allows a fallback and redirect to "https://rns.foundation" (standard web2 website) if the browser in question is not IPFS compatible.</summary>
<br />

<strong>Under The Hood (the outcome)</strong>
<summary>As <u>rnsfoundation.xrd</u> is being called within a web navigation environment, the RNS integrated extension would call the <strong>navigation</strong> context. Now, many actions can be taken within a navigation context. If the browser is IPFS compatible, the extension would then try to narrow down this navigation context to find an intended action by selecting the <strong>ipfs</strong> directive. If the browser is not IPFS compatible, the extension would then select the next natural progression of a navigation context to see if a <strong>website</strong> directive exists. In this case it does not, therefore, the extension moves to select a <strong>website:redirect</strong> directive. As this is set, it qualifies as a fallback and the user is redirected to "https://rns.foundation".</summary>


