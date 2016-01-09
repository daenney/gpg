# GPG

This repository contains my GPG public key, [0x18D40820FA0EE03C](https://raw.githubusercontent.com/daenney/gpg/gh-pages/daenney.asc).
It is also available on the GnuPG/sks-keyservers pool of keyservers to
ease fetching the key and verifying/encrypting against it. I'll keep syncing
signatures that get added back to the key in this repository and this
repository should be considered the authoritative source.

It has only one uid, *Daniele Sluijters* with no associated emails. This key
is supposed to be used to verify that a message is from me, or encrypt content
for my eyes only. However, who am I is not defined by my email address. As
such there will not be multiple uid's with different addresses. A message
signed by this key can be authenticated as coming from me.

## Key creation

The master key was created directly on an encrypted USB drive which is stored
somewhere only I have access to. A number of copies of the revocation
certificate have been stored in the event of a key compromise or loss.

The three subkeys were created directly on a Yubikey and have never left
the device.

I deem this setup to be secure enough for daily use and be reasonably friendly
with regards to managing the full lifecycle of the associated keys.
