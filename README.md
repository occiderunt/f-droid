# F-Droid repository

An F-Droid repository for my apps.

Add it in F-Droid under **Settings -> Repositories**:

    https://occiderunt.github.io/f-droid/repo

Fingerprint (SHA-256) of the repo signing key:

    64:36:80:73:B6:2C:6B:30:86:D3:0B:92:96:1C:D3:93:AA:2B:96:0E:1E:68:2C:D7:F3:BE:CA:CB:9D:7D:99:56

## Rebuilding

The static index in `repo/` is generated with fdroidserver:

    fdroid update -c

from the working repository (kept outside this checkout, with the signing
keystore), then copied here.
