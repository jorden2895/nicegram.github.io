---
description: Add, switch, back up, and hide Telegram accounts in Nicegram.
---

# How do accounts work in Nicegram?

Nicegram signs in to Telegram accounts and lets you keep more of them in one client
than a standard Telegram setup typically exposes. The account switcher keeps each
account’s chats and settings separate.

## Add an account

1. Open **Settings**.
2. Open the account switcher or choose **Add Account**.
3. Enter the phone number attached to the Telegram account.
4. Complete Telegram’s login-code and two-step-verification flow, if enabled.

The exact account ceiling is platform-specific and can also be constrained by
memory, storage, notification load, or Telegram. Nicegram’s public source currently
contains a much higher iOS ceiling and Android options for 10 or 100 accounts, so
“unlimited” should be understood as expanded multi-account use rather than a
guarantee that every device can run an arbitrary number.

## Switch accounts

Open the account switcher and select an account. Before sending a message, confirm
the active avatar and identity — especially if you manage client or channel accounts.

## Back up, import, or export accounts

Supported mobile builds expose Nicegram account-transfer tools. These tools move
account session access; they do not create a Telegram backup of all cloud chats.

- Protect exported account material as you would an active login session.
- Do not upload it to a public drive or send it through an untrusted chat.
- Availability and compatibility can differ between iOS and Android builds.

To keep an account out of the normal app surface, use
[Double Bottom or hidden chats](../features/privacy.md) instead of sharing an
exported session with another device.

**Sources:** [Nicegram features](https://nicegram.me/features) ·
[iOS source](https://github.com/nicegram/Nicegram-iOS) ·
[Android source](https://github.com/nicegram/Nicegram-Android)
