# FireFly Remote — Privacy Policy

**Effective date:** 5 November 2026 (updated: the app is free with ads; free trial removed)
**Application:** FireFly Remote – Remote for Fire TV & Firestick (`com.fireflyapps.firetvremote`)

This policy explains what information the FireFly Remote Android app ("the app", "we") handles, and why.
The app lets you control a Fire TV device on your local Wi-Fi network from your phone.

**In short:** no analytics and no banner ads. The app is free and shows ads from Google AdMob: one ad when you open
the app (at most every few hours) and optional reward videos — see section 4. Buying "Remove ads" turns ads off. The app
also sends an anonymous, one-way hashed device identifier so we can count how many devices use the app — see section 2.

---

## 1. Information that stays on your device

To connect to your TV, the app stores the following **only on your phone**. It is never sent to us or to any third party:

- The name and local IP address of Fire TV devices you add or that are discovered on your Wi-Fi network.
- The pairing token issued by your Fire TV after you enter the on-screen PIN, and the TV's certificate fingerprint.
- If you choose ADB mode, a locally generated key used to authenticate with your TV.
- Text you type with the keyboard feature, and the list of apps on your TV. These are exchanged directly with your TV
  on your local network and are not stored or transmitted anywhere else.

We do not require an account, and we do not collect your name, email, contacts or photos.

## 2. Usage count (hashed device identifier)

When you open the app, it sends a one-way SHA-256 hash of your device's Android ID to our backend, hosted by
[Supabase](https://supabase.com/privacy). We store only that hash and the time it was first seen. (Until version 1.3.0
this ran a 3-day free trial; the app is now free and there is no trial.)

- The hash cannot be turned back into your Android ID and is not linked to your name, email, Google account or any other information.
- It is used only to count how many devices install and keep using the app, never for advertising or tracking.
- As with any internet request, Supabase may record your IP address and the request time in ordinary server logs, used only to operate and secure the service.

## 3. Purchases (Google Play Billing)

"Remove ads" (subscription or one-time purchase) is processed entirely by Google Play. We never receive your payment
card details. The app only receives confirmation from Google Play that your purchase is active, so it can turn ads off.
See the [Google Payments Privacy Notice](https://payments.google.com/payments/apis-secure/u/0/get_legal_document?ldo=0&ldt=privacynotice).
You can cancel a subscription at any time in Google Play → Payments & subscriptions → Subscriptions.

## 4. Ads (Google AdMob)

The app is free and supported by ads from [Google AdMob](https://policies.google.com/technologies/ads):

- an **app open ad**, shown when you open the app, at most once every few hours and never while you are using the remote;
- an optional **reward video** on the "Remove ads" screen that turns the app open ad off for 24 hours.

The ads SDK is never started for users who bought "Remove ads".

When ads are loaded, Google may collect and process your device's **advertising ID**, IP address (used to estimate
approximate location), device and app information, and ad interactions, to show and measure ads and prevent fraud.
See [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites).

- In the EEA, UK and Switzerland you are asked for consent first (Google's consent form), and you can change your
  choice anytime with **Ad choices** on the "Remove ads" screen.
- You can reset or delete your advertising ID in Android Settings → Privacy → Ads.
- "Remove ads" (subscription or lifetime) turns ads off completely.

## 5. Network permissions

The app uses Wi-Fi and local network access to find and communicate with Fire TV devices on your home network
(mDNS discovery and direct connections to your TV), and internet access to load app icons shown by your TV,
to send the usage count, to talk to Google Play for purchases, and to load ads.

## 6. Children

The app is not directed at children under 13, and we do not knowingly collect personal information from children.

## 7. Data retention and deletion

All data stored on your phone is deleted when you remove a TV in the app, clear the app's data, or uninstall the app.
The usage record (hashed device identifier and first-seen time) is kept to count devices. You can ask us to delete
it by emailing us (see Contact).

## 8. Security

Communication with your TV uses HTTPS on your local network, and the TV's certificate is pinned after pairing.
The usage count is sent over HTTPS.

## 9. Changes

We may update this policy from time to time. Changes will be posted on this page with a new effective date.

## 10. Contact

Questions about this policy or deletion requests: **contact@farelyt.com**

---

FireFly Remote is an independent app and is not affiliated with Amazon.com, Inc.
Fire TV is a trademark of Amazon.com, Inc. or its affiliates.
