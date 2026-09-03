---
description: Hide selected Nicegram accounts or chats and understand what these controls do not protect.
---

# How do Nicegram privacy controls work?

Nicegram adds controls that reduce what appears in the normal app interface. They
are useful when several people can see or temporarily handle your device, but they
do not replace device security or Telegram’s account protections.

## Double Bottom

Double Bottom creates an alternate hidden account surface. After setup, the normal
entry path shows your regular accounts; the configured alternate action or code
reveals the hidden set.

1. Open Nicegram settings and find **Double Bottom** or hidden-account settings.
2. Configure the alternate access method offered by your build.
3. Add only the intended accounts to the hidden surface.
4. Lock the app and test both the normal and alternate paths before relying on it.

If you forget the Double Bottom credential, recovery can be limited. Do not set it
until you know which recovery option the current screen provides.

## Hidden chats

Hidden chats remove selected conversations from the normal chat list and expose
them through Nicegram’s hidden-chat entry point. Hiding a chat does not delete it,
change Telegram retention, or make messages invisible on another signed-in device.

## Immediate auto-lock

Supported builds offer shorter auto-lock intervals than the normal client flow.
Use a device passcode and biometric lock as the first layer; use Nicegram’s lock as
an additional client layer.

## Phone-number controls

Some builds expose an extra phone-number visibility control or guidance. Telegram
still owns the account’s underlying privacy rules, so confirm the result under
**Settings → Privacy and Security → Phone Number**.

## Hidden chats are not Secret Chats

Hidden chats change the local Nicegram interface. Telegram Secret Chats are a
separate Telegram conversation type with their own encryption and device behavior.

**Availability:** iOS and Android; exact labels and recovery behavior vary.

**Sources:** [Official feature list](https://nicegram.me/features) ·
[Official status labels](https://nicegram.me/download) ·
[Telegram privacy FAQ](https://telegram.org/faq#privacy)
