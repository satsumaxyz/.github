# Security policy

This policy covers every repository in the [satsumaxyz](https://github.com/satsumaxyz)
organisation, the Satsuma chain, and the products Satsuma deploys on it and on
tangerine, unless a repository has its own `SECURITY.md`.

## Reporting a vulnerability

Please **do not open a public issue** for a vulnerability, and never test an
exploit against live funds.

Report it privately through GitHub:
**[Report a vulnerability](https://github.com/satsumaxyz/.github/security/advisories/new)**.

Include what is affected (repository, contract address or URL), how to
reproduce it, and the impact you expect. You'll get an acknowledgement, and the
report stays private until a fix is deployed.

## Severity

Reports are triaged on [Immunefi's severity scale](https://immunefi.com/immunefi-vulnerability-severity-classification-system-v2-3/)
(Critical, High, Medium, Low). A breach of a product's declared invariants halts
that product on chain until it is fixed.

## Scope

- In scope: the chain runtime and node, Satsuma's governance and treasury
  contracts, products listed in Satsuma's on-chain registry, and the public
  sites under `satsuma.one`.
- Out of scope: denial of service by volume, social engineering, and findings
  that need a compromised key.
