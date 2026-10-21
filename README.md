# Remedio Mail updates

This repository only serves the update feed for Remedio Mail, a native macOS mail client. The source code is private.

- `appcast.xml` is the [Sparkle](https://sparkle-project.org) feed that installed copies check once a day.
- Each release here holds one update archive (`RemedioMail-<version>.zip`), signed with the app's EdDSA key. The app installs only archives whose signature matches the public key built into it.

There's nothing to download by hand: Remedio Mail updates itself (Remedio Mail → Check for Updates…).
