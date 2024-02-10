# Example of how to use GnuPG with Python
## Install gpg
`brew install gnupg`

## Install gnupg
1. `pip install python-gnupg` please follow the link for more details https://gnupg.readthedocs.io/en/latest/
## Create public and private keys
1. `gpg --gen-key` Please follow the below link for more details on how to create private and public keys https://www.gnupg.org/gph/en/manual/c14.html
```
Example:

sangopakkundu@Sangopaks-MBP pgp-python % gpg --gen-key
gpg (GnuPG) 2.4.4; Copyright (C) 2024 g10 Code GmbH
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Note: Use "gpg --full-generate-key" for a full featured key generation dialog.

GnuPG needs to construct a user ID to identify your key.

Real name: SangopakKundu
Email address: sangojumech07@gmail.com
You selected this USER-ID:
    "SangopakKundu <sangojumech07@gmail.com>"

Change (N)ame, (E)mail, or (O)kay/(Q)uit? o
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
gpg: /Users/sangopakkundu/.gnupg/trustdb.gpg: trustdb created
gpg: directory '/Users/sangopakkundu/.gnupg/openpgp-revocs.d' created
gpg: revocation certificate stored as '/Users/sangopakkundu/.gnupg/openpgp-revocs.d/EF9FE9CB7AB010D82545DF84FFA1632B32468B73.rev'
public and secret key created and signed.

pub   ed25519 2024-02-10 [SC] [expires: 2027-02-09]
      EF9FE9CB7AB010D82545DF84FFA1632B32468B73
uid                      SangopakKundu <sangojumech07@gmail.com>
sub   cv25519 2024-02-10 [E] [expires: 2027-02-09]
```