---
wallet-cli: patch
---

Honor the requested wallet network during login, access-key refresh, and identity checks, including when the persisted wallet previously selected another chain. Allow login retries after failed authorization by reusing cached sessions only when a usable key exists for the requested account and network.
