---
notification: patch
notification-js: patch
---

Fixed Android notifications always getting an empty `InboxStyle`, which hid the body text on devices that show notifications expanded by default. `InboxStyle` is now only applied when there is at least one inbox line.
