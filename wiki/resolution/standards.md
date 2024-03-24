

# Record Usage / Standards

---

The Radix Name Service is still in its infancy, so docket and record standards are still being formed among users. The foundation proposes the following guide as a primer.<br />

#### Navigation Context

For use within web browsers or user facing content delivery.

<br />
<div style="max-width:1024px">

| Selector | Directives | Example Use Case |
| :-----------: | :-----------: | :----------- |
| navigation | website | Web2 website navigation. |
| navigation | website:redirect | Explicit Web2 redirect action. |
| navigation | ipfs | IPFS content hash consumption within a browser. |

</div>
<br />

#### Receiver Context

For use within wallets (receiving tokens).

<br />
<div style="max-width:1024px">

| Selector | Directives | Example Use Case |
| :-----------: | :-----------: | :----------- |
| receivers | * | Radix native catch-all account address. |
| receivers | <em>hypothetical: gumball</em> | Account that will exclusively receive gumball tokens. |

</div>
<br />

#### Delegation Context

For use within wallets / staking dashboards (delegation management).

<br />
<div style="max-width:1024px">

| Selector | Directives | Example Use Case |
| :-----------: | :-----------: | :----------- |
| delegation | xrd | Radix validator address (stake / unstake target). |
| delegation | <em>hypothetical: gumball</em> | Component that stakes gumballs in return for gumball yield. |

</div>
<br />

