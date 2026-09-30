# Circumvention & Anonymity

Tools for reaching blocked content, hiding your identity online, or getting around network-level monitoring.

---

### Tor Browser
[torproject.org](https://www.torproject.org)

| | |
|---|---|
| Encryption | Multi-layer (onion) routing; not full end-to-end on the open web past the exit node |
| Open source | Yes |
| Audited | Yes, ongoing public audits |
| Logging | None (no account) |
| Jurisdiction | US nonprofit, decentralized network |
| Cost | Free |
| Self-host | N/A — joins existing network |
| Account needed | None |
| Platforms | Windows, Mac, Linux, Android |

**Best for:** Reaching blocked sites and hiding your identity from the sites you visit — the strongest anonymity in this list.
**Avoid if:** You need speed for calls/streaming, or Tor itself is blocked with no bridges available.

---

### Orbot
[orbot.app](https://orbot.app)

| | |
|---|---|
| Encryption | Routes chosen apps through Tor |
| Open source | Yes |
| Audited | Shares Tor Project audits |
| Logging | None |
| Jurisdiction | Guardian Project (US) |
| Cost | Free |
| Self-host | N/A |
| Account needed | None |
| Platforms | Android, iOS |

**Best for:** Routing other apps — not just a browser — through Tor on a phone.
**Avoid if:** You need full anonymous browsing — pair it with Tor Browser, don't use it alone.

---

### Psiphon
[psiphon3.com](https://psiphon3.com)

| | |
|---|---|
| Encryption | Obfuscated VPN/proxy tunnel |
| Open source | Yes |
| Audited | No independent public audit found |
| Logging | Aggregate/session metadata per policy |
| Jurisdiction | Canada |
| Cost | Free (ad-supported) / paid |
| Self-host | No |
| Account needed | None |
| Platforms | Windows, Mac, Android, iOS |

**Best for:** Quickly unblocking sites when Tor is too slow or also blocked.
**Avoid if:** You need strong anonymity — this is built for access, not for hiding who you are.

---

### Outline VPN
[getoutline.org](https://getoutline.org)

| | |
|---|---|
| Encryption | Shadowsocks-based VPN tunnel |
| Open source | Yes |
| Audited | Client + server open, community reviewed |
| Logging | Depends who runs your server |
| Jurisdiction | Depends on server operator |
| Cost | Free self-hosted, or paid via a provider |
| Self-host | Yes |
| Account needed | None |
| Platforms | Windows, Mac, Linux, Android, iOS |

**Best for:** A newsroom or org self-hosting its own VPN server for a trusted group.
**Avoid if:** You have no one to run a server — there's no public Outline network to join.

---

### Mullvad VPN
[mullvad.net](https://mullvad.net)

| | |
|---|---|
| Encryption | WireGuard / OpenVPN tunnel |
| Open source | Yes (apps) |
| Audited | Yes, regular independent audits |
| Logging | No-logs, audited |
| Jurisdiction | Sweden |
| Cost | Paid, flat fee |
| Self-host | No |
| Account needed | Anonymous account number, no email |
| Platforms | Windows, Mac, Linux, Android, iOS |

**Best for:** Everyday privacy from your ISP and hiding your IP — the most transparent commercial VPN.
**Avoid if:** You're in a country that actively blocks known VPN IPs, or need Tor-level anonymity.
