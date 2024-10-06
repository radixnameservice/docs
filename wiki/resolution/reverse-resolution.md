

# Reverse Resolution (Domain Discovery)

---

The Radix Name Service allows users to enable what's called "Domain Discovery Mode" for each of their controlled domains. This allows RNS integrations to resolve domain names from specific addresses within the integration itself in a safe and verified manner (e.g. can auto resolve a list of account addresses). This is much safer over utilizing a 'receiver' context record value as the domain to which the address resolves is an absolute binding, rather than an address that is manually set by the user (as a record), which could of course create opportunities for interception attempts.

<br />
We're still spec'ing this out 🤓
