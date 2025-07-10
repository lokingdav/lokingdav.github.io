---
title: "How to Recover a Cryptographic Secret From the Cloud"
collection: publications
category: conferences
permalink: /publication/2023-10-16-secret-recovery
excerpt: 'This paper presents a secure cloud-based secret-recovery mechanism that allows users to store cryptographic secrets and recover them independently, even after losing their credentials, while ensuring confidentiality against malicious clouds.'
date: 2025-07-02
venue: 'ACM Computer and Communications Security (CCS)'

---

**Extended Paper**: [Cryptology ePrint Archive](https://eprint.iacr.org/2023/1308) 

**Artifact**: [GitHub - Secret Recovery](https://github.com/wspr-ncsu/Secret-Recovery)


**Abstract**: Clouds have replaced most local backup systems, as they offer strong availability and reliability guarantees. Clouds, however, are not, and should not be, used as backup for cryptographic secrets. Cryptographic secrets might control financial assets (e.g., crypto wallets), hence, storing such secrets on the cloud corresponds to sharing ownership of the financial assets with the cloud, and makes the cloud a more attractive target for attacks.

Can we have the best of the two worlds, where a user, Alice, can conveniently store a copy of her cryptographic secrets on the cloud and she is the only one who can recover them? Can she do so even when she loses her devices and forgets all credentials, while at the same time retaining full ownership of her secrets?

In this paper, we provide a cloud-based secret-recovery mechanism where confidentiality is always guaranteed when Alice has not lost her credentials, even in the presence of a malicious cloud. If Alice loses all devices and credentials, she can still recover her secrets (in most circumstances). This is in contrast with all previous work that relies on the assumption that Alice remembers some authentication secret. We prove our system secure in the Universally Composable framework and we implement our protocols to demonstrate their efficiency.


#### BibTex

```Bibtex
@misc{verber2025recover,
      author = {Tanner Verber and David Adei and Alessandra Scafuro and Chris Orsini},
      title = {How to Recover a Cryptographic Secret From the Cloud},
      year = {2025},
      journal = {Proceedings of the ACM SIGSAC Conference on Computer and Communications Security (ACM CCS)},
}
```