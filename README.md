# Biconomy x Arbitrum: PropAMM

Documentation for the propAMM settlement infrastructure Biconomy is bringing to Arbitrum: chain-agnostic EVM contracts, deployed and load-validated on another L2 today, designed to scale propAMM volumes on Arbitrum One.

## Contents

- [`docs/propamm-on-arbitrum.md`](docs/propamm-on-arbitrum.md): partnership context. The problem propAMMs hit on permissionless L2 deployments, what we built to close the dominant toxic-flow vector at the contract layer (ERC-8211 freshness predicates developed with the Ethereum Foundation), why Arbitrum is the right operational home (250ms blocks, private-mempool sequencing, an evolving ordering-policy surface), MM commitments, unit economics.
- [`docs/transaction-ordering.md`](docs/transaction-ordering.md): how PropAMM would use new transaction-ordering primitives on Arbitrum. A commit lane scoped to price commits, application-declared ordering as a standing rule, why ordering matters for Arbitrum, and open questions for the Arbitrum team.