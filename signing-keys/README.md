# Signing keys
## SSH
I almost always Git through SSH as it's more verifiable and secure. The key uses `ed25519-sk`, which uses a hardware security key in addition to a passphrase. This is set as my authentication key on my main systems (meaning commits are not signed with it).

The public keys are stored in `ssh/github-<system>_ed25519_sk.pub`.

## GnuPG
My commits are signed with GnuPG. This is set as my signing key on my main systems.

The public keys are stored in `gpg/github-<system>.pub.asc`.

## Systems
Legend:
* 🔴 Keys no longer used for Git permanently, GnuPG keys revoked
* 🟡 System inactive temporarily, keys active
* 🟢 System active

| 🚥 | Abbreviation | System |
| --- | --- | --- |
| 🟢 | mbp-17 | MacBook Pro |

## Vigilant mode
This account has [vigilant mode](https://docs.github.com/en/authentication/managing-commit-signature-verification/displaying-verification-statuses-for-all-of-your-commits) enabled, meaning that if a commit is not signed, it will have a yellow `(Unverified)` badge. Don't trust unverified commits and assume it's not me unless I say otherwise in a signed message.
