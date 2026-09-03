# Nicegram public facts

These are the reusable claims approved for public documentation. “Source-visible”
means code exists; it does not mean the feature is in every released build.

| Fact | Status | Evidence |
|---|---|---|
| Nicegram is an independent client built with Telegram APIs | Current | [Official download FAQ](https://nicegram.me/download) |
| Official downloads are linked from `nicegram.me/download` | Current | [Download page](https://nicegram.me/download) |
| Multiple accounts, Double Bottom/hidden surfaces, translation, quick replies, call recording, and prerecorded video messages are listed as available | Current public claim | [Download page](https://nicegram.me/download) |
| AI Assistant and AI Agent Marketplace are labeled beta | Beta | [Download page](https://nicegram.me/download) |
| Escrow payments and HyperLancer are labeled beta | Beta | [Download page](https://nicegram.me/download) |
| iOS and Android clients are open-source forks with Nicegram additions | Current | [iOS](https://github.com/nicegram/Nicegram-iOS), [Android](https://github.com/nicegram/Nicegram-Android) |
| Nicegram iOS currently declares iOS 15 as its minimum | Source-visible | [`Telegram/BUILD:164`](https://github.com/nicegram/Nicegram-iOS/blob/47c59dac6fc6b93b741fbc197c1f79524bfbf65c/Telegram/BUILD#L164) |
| Nicegram Android currently declares Android 7.0/API 24 as its minimum | Source-visible | [`TMessagesProj/build.gradle:173`](https://github.com/nicegram/Nicegram-Android/blob/76f9b4022e2e3c0108d9722a63aef8f35974b556/TMessagesProj/build.gradle#L173) |
| Feature visibility can vary by platform, version, plan, region, rollout, and account state | Product behavior | Public store descriptions plus client configuration surfaces |
| Nicegram and its providers process some data needed for features and analytics | Current | [Privacy Policy](https://nicegram.me/privacy-policy), [App Store privacy details](https://apps.apple.com/app/id1608870673) |

## Claims not approved

- “Nicegram collects no personal data.”
- “Every feature is available on every platform.”
- “Unlimited accounts” without noting device and platform constraints.
- Any exact AI model name unless it is verified in the current product surface.
- Guaranteed wallet safety, recovery, returns, or protection from scams.
- Old Scroll-to-Earn or attention-point accrual as an active program.
