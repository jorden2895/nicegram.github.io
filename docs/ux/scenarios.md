# Nicegram public-help scenarios

These scenarios define the behavior the public Wiki must explain. IDs are stable
and should be referenced when a feature page changes.

## SCR-001 — Install Nicegram

**Given** a user chooses a supported platform, **when** they follow the official
download route, **then** they reach the current App Store, Google Play, Android APK,
or macOS package without passing through an obsolete domain.

## SCR-002 — Add and switch accounts

**Given** a signed-in user, **when** they add another Telegram account, **then** the
account appears in the account switcher until a platform or device limit is reached.

## SCR-003 — Hide and reveal a private surface

**Given** Double Bottom or hidden chats are enabled, **when** the user enters the
configured alternate access action, **then** only the intended hidden surface is
revealed. The page must also explain recovery limits.

## SCR-004 — Reuse a reply

**Given** a saved quick reply, **when** the user invokes it in a chat, **then** the
stored text is inserted or sent according to the current platform flow.

## SCR-005 — Translate or transcribe content

**Given** a supported message or voice note, **when** translation or transcription
is requested, **then** a result is shown or an actionable availability/error state
is explained.

## SCR-006 — Send existing video as a video message

**Given** a compatible local video, **when** the user chooses video-message
conversion, **then** Nicegram prepares it as a round video subject to media limits.

## SCR-007 — Record a call responsibly

**Given** call recording is available on the device, **when** the user starts or
enables recording, **then** the recording is saved through the documented flow and
the user is reminded to obtain legally required consent.

## SCR-008 — Use an AI feature

**Given** AI is available for the account and plan, **when** the user submits a
prompt or chat context, **then** the app returns a result or explains the limit and
the page makes third-party processing discoverable before use.

## SCR-009 — Use wallet or Web3 tools

**Given** the wallet surface is available, **when** the user creates or connects a
wallet, **then** the app explains the confirmation and recovery model before the
user moves assets or connects a dApp.

## SCR-010 — Resolve a missing feature

**Given** a feature is documented but not visible, **when** the user checks the
availability guide, **then** they can distinguish platform, version, plan, region,
rollout, and account-state causes and know where to ask for help.
