# Data & File Management

Tools for encrypting, backing up, sharing, and cleaning files.

---

### VeraCrypt
[veracrypt.fr](https://veracrypt.fr)

| | |
|---|---|
| Encryption | AES, full-disk or container, at rest |
| Open source | Yes |
| Audited | Yes |
| Jurisdiction | N/A — local software |
| Cost | Free |
| Platforms | Windows, Mac, Linux |

**Best for:** Hiding files on a laptop/USB drive that could be seized or lost.
**Avoid if:** You need seamless cloud sync — encrypted volumes don't sync well.

---

### Cryptomator
[cryptomator.org](https://cryptomator.org)

| | |
|---|---|
| Encryption | AES, per-file, at rest |
| Open source | Yes |
| Audited | Yes |
| Cost | Free (freemium mobile) |
| Platforms | Windows, Mac, Linux, Android, iOS |

**Best for:** Encrypting files before they hit Dropbox/Drive/etc, including on mobile.
**Avoid if:** You need whole-disk encryption, not per-file.

---

### OnionShare
[onionshare.org](https://onionshare.org)

| | |
|---|---|
| Encryption | Tor-routed transfer |
| Open source | Yes |
| Logging | None |
| Cost | Free |
| Platforms | Windows, Mac, Linux |

**Best for:** Sending a file or hosting a page to one person, with no third-party server involved.
**Avoid if:** The recipient won't install Tor Browser to receive it.

---

### restic
[restic.net](https://restic.net)

| | |
|---|---|
| Encryption | AES, client-side, at rest & in transit |
| Open source | Yes |
| Self-host | Yes |
| Cost | Free |
| Platforms | Windows, Mac, Linux |

**Best for:** Automated encrypted backups you fully control.
**Avoid if:** You want a point-and-click GUI — this is command-line only. *(A simpler GUI backup option is a current gap in this directory.)*
