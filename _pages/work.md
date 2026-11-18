---
title: Work
---

## Digital identity

Tooling for EU age verification, built on the [Longfellow zero-knowledge proof system](https://eprint.iacr.org/2024/2010). The repositories are at [github.com/pipe23-org](https://github.com/pipe23-org).

- [longfellow-vectors](https://github.com/pipe23-org/longfellow-vectors). Collection of test vectors for Longfellow zero-knowledge proof implementations (draft-google-cfrg-libzk). Unstable.
- [pylongfellow](https://github.com/pipe23-org/pylongfellow). Python interface to implementations of Longfellow zero-knowledge proofs over ISO 18013-5 mdoc credentials. Unstable.
- [zk-age-verifier](https://github.com/pipe23-org/zk-age-verifier). Verifier service for EU age-verification proofs (Longfellow ZK over mdoc, W3C Digital Credentials API). Unstable.
- [predicate-circuit](https://github.com/pipe23-org/predicate-circuit). Provisional design for a Longfellow circuit that encodes a number of predicates. Unstable.
- [EUDI-Matrix-PoC](https://github.com/pipe23-org/EUDI-Matrix-PoC). EUDI Wallet to Matrix account provisioning proof of concept.

Issues raised upstream:

- [longfellow-zk/longfellow-zk#226](https://github.com/longfellow-zk/longfellow-zk/issues/226). mdoc::v1 prover ignores the requested namespace.
- [longfellow-zk/longfellow-zk#227](https://github.com/longfellow-zk/longfellow-zk/issues/227). mdoc::v1 fixes DeviceNameSpacesBytes to the empty map.
