# If You Don't Feel Safe

This page is organized by **symptom**, not by tool — start with what's actually happening. For the interactive, step-by-step version, use the [Guided Tool Finder](tools-finder.md).

## "I'm getting login alerts, password resets, or 2FA codes I didn't request"

This is usually an account takeover, not a device problem.

1. Change the password now, from a device you trust — not the one you suspect is compromised.
2. Check the account's "active sessions" list and sign out anything unfamiliar.
3. Turn on 2FA if it wasn't already (Aegis Authenticator, for Android).
4. Check recovery email/phone and mail-forwarding rules for silent persistence.
5. Repeat for any account this one can reset (usually your email).

→ [Security in a Box: recovering from account compromise](https://securityinabox.org/en/communication/account-compromise)

## "Someone close to me always seems to know my location or activity"

Possible device monitoring by someone with access to you.

!!! warning
    Checking for or removing spyware can alert whoever is monitoring you and escalate risk before you're safe. If there's any chance of physical danger, contact a domestic violence hotline or stalkerware-specialist service before acting alone — see [Coalition Against Stalkerware](https://stopstalkerware.org).

- If it's safe to check: look at installed apps, device admin permissions, and accessibility permissions for anything unfamiliar.
- Longer-term, a fresh device and accounts your monitor has never had access to is safer than trying to "clean" one they've already compromised (GrapheneOS, for a hardened replacement Android).

→ [Security in a Box: protect against physical threats](https://securityinabox.org/en/assess-plan/physical-security)

## "My device is acting strange — battery drain, heat, unknown apps, random restarts"

Possibly malware. **This directory doesn't yet have a vetted FOSS anti-malware pick — that's a real gap**, not an oversight.

1. Review installed apps for anything unfamiliar, and check admin/accessibility permissions.
2. Update the OS and all apps.
3. Uninstall anything suspicious rather than investigating it.
4. If symptoms continue, back up what matters (Cryptomator/restic) and factory reset.

→ [Security in a Box: protect against malware](https://securityinabox.org/en/phones-and-computers/malware)

## "I was recently stopped, detained, or had a device searched"

Treat the device as compromised from the moment it was taken.

1. Remote-lock or remote-wipe it now if you still can: [findmydevice.google.com](https://findmydevice.google.com) (Android) or [icloud.com/find](https://icloud.com/find) (iPhone) from another device. *(Not open-source, but the fastest real option in the moment.)* If the drive wasn't encrypted, assume its contents are already exposed.
2. Change passwords for anything accessible from that device, from a different trusted device.
3. Log out other sessions on major accounts.
4. Assume contacts and message history were seen — consider a heads-up to anyone whose safety could be affected.
5. For next time: Tails OS (amnesiac, boots from USB) or GrapheneOS (hardened daily-driver Android) limit what a future search can expose.

→ [Security in a Box: what to do when you risk being arrested](https://securityinabox.org/en/blog/2025-09-detentions)

## "I'm getting threats or messages with private details about me"

Mostly a process problem, not a tools problem.

1. Document everything first — screenshots with timestamps and URLs visible, before reporting or blocking (reporting often removes the evidence).
2. Lock down account privacy settings.
3. Report and block through the platform's harassment-specific flow.
4. Tighten account security as a precaution (Bitwarden/KeePassXC + Aegis) — doxxing often follows, or precedes, account compromise.

→ [Security in a Box: protect yourself on social media](https://securityinabox.org/en/communication/social-media)

## No specific incident — general check-up

1. Unique passwords everywhere (KeePassXC or Bitwarden).
2. 2FA on your important accounts, starting with email (Aegis Authenticator).
3. Review connected apps and active sessions on your main accounts.
4. Keep devices updated — most real-world compromises exploit already-patched holes.

→ Or walk the full [Security in a Box](https://securityinabox.org/en) check-up.
