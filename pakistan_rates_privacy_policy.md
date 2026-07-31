# Pakistan Rates — Privacy Policy

**Effective date:** 31 July 2026
**Application:** Pakistan Rates (`pk.rates.app`)

Pakistan Rates displays daily petrol, diesel, gold and silver rates for Pakistan
and can send a notification when a rate changes. There is no account, no sign-in,
no advertising, and no sale of data.

---

## 1. Information we do not collect

The app does not ask for or collect your name, email address, phone number,
postal address, date of birth, precise or approximate location, contacts,
photos, files, microphone or camera data. There is no registration or login.

## 2. Information collected automatically

| What | Why | Service |
|---|---|---|
| **Messaging registration token** — an anonymous, app-specific device identifier | To deliver price alerts. The app subscribes to broadcast topics (fuel / metals, in English or Urdu). It is not linked to your identity, and we cannot use it to contact you individually. | Firebase Cloud Messaging |
| **Crash diagnostics** — stack trace, device model, OS version, app version, time of crash | Only sent if the app crashes, so faults can be fixed. Contains no personal information. | Firebase Crashlytics |
| **IP address and request time** | Recorded in ordinary server logs when the app fetches rates over HTTPS. Used solely to operate and secure the service; not used to profile you. | Supabase (rates database) |

## 3. Information stored only on your device

- The most recent rates, cached so the app works offline
- Your language preference (English or Urdu)
- Whether you have been asked for notification permission

This never leaves your device and is removed when you uninstall the app.

## 4. Permissions the app requests

- **Internet / network state** — required, to fetch rates.
- **Notifications** (`POST_NOTIFICATIONS`) — optional. Used only to alert you to a
  rate change. Declining it does not affect anything else; the app continues to
  work and you can enable or disable notifications at any time in Android
  Settings.

## 5. Third-party services

- **Google Firebase** (Cloud Messaging, Crashlytics) — https://firebase.google.com/support/privacy
- **Supabase** (rates database and API) — https://supabase.com/privacy

These providers process data on our behalf under their own privacy terms.

## 6. No advertising, no analytics, no data sale

The app contains no advertising SDKs and does not read the Android advertising
identifier. It performs no behavioural or marketing analytics. We do not sell,
rent or share personal data with third parties for advertising purposes.

## 7. Children

The app is not directed at children under 13 and we do not knowingly collect
information from them.

## 8. Data retention

The messaging token is retained while the app remains installed and is
invalidated on uninstall. Crash reports are retained according to Google's
Crashlytics retention schedule (approximately 90 days). Server request logs are
kept only briefly for operational and security purposes.

## 9. Your choices

- Turn notifications off at any time in Android Settings → Apps → Pakistan Rates
  → Notifications.
- Uninstalling the app deletes all locally stored data and ends messaging
  delivery.

## 10. Important — about the rates shown

**Rates in this app are indicative and are provided for general information
only.** They are gathered automatically from publicly available third-party
sources, including Pakistan State Oil, PakWheels, Pakistani news outlets and
bullion rate publishers. They are cross-checked between independent sources
before being displayed, but they are **not official notifications** and may be
delayed, incomplete or inaccurate.

Nothing in this app is financial, investment or trading advice. Always confirm
the current price with the fuel station, dealer or an official source before
making any transaction or financial decision. We accept no liability for any
loss arising from reliance on the information shown.

## 11. Security

All network communication uses HTTPS. The credential embedded in the app is
read-only and cannot modify any data.

## 12. Changes to this policy

Any changes will be posted on this page with an updated effective date.

## 13. Contact

Questions about this policy: **arifmoneeb02@gmail.com**
