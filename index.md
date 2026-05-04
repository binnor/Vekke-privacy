# Privacy Policy — Vekke

*Last updated: May 4, 2026*

## What Vekke does

Vekke is a messaging mode app. When a mode is active, Vekke intercepts incoming message notifications from apps you've selected (WhatsApp, Messenger, Instagram, SMS, Telegram, Signal, Viber, Discord, TikTok, Snapchat), sends automatic replies on your behalf where the receiving app supports it, and holds the messages so you can read them when you're back.

## What Vekke reads

Vekke reads notification previews — the same text that appears on your lock screen when a message arrives. This is the only data Vekke accesses from your messages.

Vekke does not read message history, contacts, photos, browsing data, location, or any other data on your device beyond what arrives in a notification preview while a mode is active.

## Where your data goes

Nowhere outside your phone. Vekke processes everything locally on the device. No message content, sender names, or notification previews are ever sent to any server, third party, or cloud service.

When you send an auto-reply, the text is delivered through your installed messaging app using its existing reply mechanism — the same path that runs when you reply manually. Vekke composes the reply text; the messaging app sends it. Vekke itself makes no outbound network connections.

## Where data is stored

- **Held messages** are kept in your phone's local app storage. They are removed from local storage when you release them, when you uninstall Vekke, or when you clear app data through Android Settings.
- **A small whitelist of senders who replied "disrupt"** is also stored locally so those senders can reach you for the rest of the active mode. The whitelist is cleared each time a mode ends.
- **Your settings** (active mode, name, language, dark-mode preference) are stored locally and never transmitted.

## Permissions Vekke uses

**Notification access** (`BIND_NOTIFICATION_LISTENER_SERVICE`)
Required to intercept incoming messages and send automatic replies via Direct Reply. Without this, Vekke cannot function.

**Do Not Disturb access** (`ACCESS_NOTIFICATION_POLICY`)
Used to silence incoming calls while a mode is active. Vekke saves your previous DND state and restores it exactly when the mode ends.

**Battery optimization exemption** (`REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`)
Prevents Android from putting Vekke to sleep in the background, which would stop auto-replies from working.

**Phone state** (`READ_PHONE_STATE`) — optional
Used only if you enable "Auto-SMS on silenced calls" on a mode. Vekke detects when a call goes unanswered. Requires your explicit opt-in per mode.

**Call log** (`READ_CALL_LOG`) — optional
Used only alongside the phone state permission above, to identify the caller's number after a silenced call. Not accessed at any other time.

**SMS** (`SEND_SMS`) — optional
Used only to send the auto-SMS reply described above. Vekke does not send SMS for any other purpose.

## What Vekke does not do

- Vekke has no user accounts. There is no sign-up, email, or password.
- Vekke uses no analytics SDK, no crash reporting service, no advertising network.
- Vekke does not collect anonymized, aggregated, or telemetry data of any kind.
- Vekke does not integrate with any third-party services or backend servers.
- Vekke does not show ads.

## Your rights

Because Vekke stores all data locally on your device, you control it directly:

- **To view your data**, open the app — held messages and settings are visible inside Vekke.
- **To delete your data**, release held messages, clear app data through Android Settings, or uninstall Vekke. All data is removed from the device immediately.
- **EU/UK/EEA users** retain rights under GDPR (access, erasure, restriction, portability, objection). Because no data leaves your device, these rights are exercised by you on your own phone. If you have questions, contact us.
- **California users** retain rights under the CCPA. Vekke does not "sell" personal information as defined by the CCPA.

## Children

Vekke is not directed at children under 13 and does not knowingly collect any data from anyone, regardless of age.

## Changes to this policy

If this policy changes materially, we'll update the "Last updated" date above and note the change in the app's release notes. Continued use of Vekke after a policy update means you accept the updated terms.

## Contact

Questions, deletion requests, or privacy concerns:

**binnor117@gmail.com**

We respond to privacy inquiries within 30 days.
