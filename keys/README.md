# Public keys
## GnuPG
My commits are signed with GnuPG. This is set as my _signing key_ on my main systems.

The public keys are stored in `gpg/github-<system>.pub.asc`.

## SSH
I almost always Git through SSH as it's more verifiable and secure. This is set as my _authentication key_ on my main systems.

The public keys are stored in `ssh/github-<system>_<type>.pub`.

## Systems
Legend:
* 🔴 Keys no longer used for Git permanently; key revoked
* 🟡 Keys no longer used for Git; key valid
* 🟢 Active

| Date       | GPG | SSH             | Abbreviation | System           | Notes                           |
|------------|-----|-----------------|--------------|------------------|---------------------------------|
|            | 🔴  | 🔴 ed25519_sk   | mbp-17       | 2017 MacBook Pro |                                 |
| 2024-06-19 | 🔴  | 🔴 ed25519_sk   | mbp-17-new   | 2017 MacBook Pro | GPG key on YubiKey              |
| 2024-09-08 | 🔴  | 🟢 ed25519      | mbp-17-3     | 2017 MacBook Pro |                                 |
| 2024-10-10 | 🟢  |                 | ed25519      | 2017 MacBook Pro | Generated after username change |
| 2024-10-12 | 🔴  | 🟢 ed25519      | mp-13        | 2013 Mac Pro     |                                 |

## Vigilant mode
This account has [vigilant mode](https://docs.github.com/en/authentication/managing-commit-signature-verification/displaying-verification-statuses-for-all-of-your-commits) enabled, meaning that if a commit is not signed, it will have a yellow `(Unverified)` badge.

* **Commits before 2024-10-09: 🟢 Trust** They have been unverified due to username change.
* **Other commits: 🔴 Don't trust**
