# FireFly Remote — Privacy Policy

**Effective date:** 30 October 2026 (updated: optional rewarded video ads)
**Application:** FireFly Remote – Remote for Fire TV & Firestick (`com.fireflyapps.firetvremote`)

This policy explains what information the FireFly Remote Android app ("the app", "we") handles, and why.
The app lets you control a Fire TV device on your local Wi-Fi network from your phone.

**In short:** no analytics, no banner or pop-up ads. During the 3-day free trial and for Premium users, the only thing
that leaves your phone is an anonymous, one-way hashed device identifier used to run the trial. After the trial, you can
choose to watch a rewarded video ad (Google AdMob) for 15 minutes of free use — see section 4.

---

## 1. Information that stays on your device

To connect to your TV, the app stores the following **only on your phone**. It is never sent to us or to any third party:

- The name and local IP address of Fire TV devices you add or that are discovered on your Wi-Fi network.
- The pairing token issued by your Fire TV after you enter the on-screen PIN, and the TV's certificate fingerprint.
- If you choose ADB mode, a locally generated key used to authenticate with your TV.
- Text you type with the keyboard feature, and the list of apps on your TV. These are exchanged directly with your TV
  on your local network and are not stored or transmitted anywhere else.

We do not require an account, and we do not collect your name, email, contacts or photos.

## 2. Free trial

To give each device one 3-day free trial, the app sends a one-way SHA-256 hash of your device's Android ID to our
backend, hosted by [Supabase](https://supabase.com/privacy). We store only that hash and the time your trial started.

- The hash cannot be turned back into your Android ID and is not linked to your name, email, Google account or any other information.
- It is used only to tell whether this device has already used its free trial, never for advertising or tracking.
- As with any internet request, Supabase may record your IP address and the request time in ordinary server logs, used only to operate and secure the service.

## 3. Purchases (Google Play Billing)

FireFly Premium (subscription or one-time purchase) is processed entirely by Google Play. We never receive your payment
card details. The app only receives confirmation from Google Play that your purchase is active, so it can unlock the app.
See the [Google Payments Privacy Notice](https://payments.google.com/payments/apis-secure/u/0/get_legal_document?ldo=0&ldt=privacynotice).
You can cancel a subscription at any time in Google Play → Payments & subscriptions → Subscriptions.

## 4. Rewarded video ads (Google AdMob)

After the free trial, the app offers an optional "watch a video" button that unlocks the app for 15 minutes.
The ads are provided by [Google AdMob](https://policies.google.com/technologies/ads). The ads SDK is only started
when you reach this screen after your trial; it is never loaded during the trial or for Premium users.

When ads are loaded, Google may collect and process your device's **advertising ID**, IP address (used to estimate
approximate location), device and app information, and ad interactions, to show and measure ads and prevent fraud.
See [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites).

- In the EEA, UK and Switzerland you are asked for consent first (Google's consent form), and you can change your
  choice anytime with **Ad choices** on the subscription screen.
- You can reset or delete your advertising ID in Android Settings → Privacy → Ads.
- Premium (subscription or lifetime) removes ads completely.

## 5. Network permissions

The app uses Wi-Fi and local network access to find and communicate with Fire TV devices on your home network
(mDNS discovery and direct connections to your TV), and internet access to load app icons shown by your TV,
to check your free trial, to talk to Google Play for purchases, and to load optional rewarded ads.

## 6. Children

The app is not directed at children under 13, and we do not knowingly collect personal information from children.

## 7. Data retention and deletion

All data stored on your phone is deleted when you remove a TV in the app, clear the app's data, or uninstall the app.
The trial record (hashed device identifier and start time) is kept so the free trial can't be restarted.
You can ask us to delete it by emailing us (see Contact); deleting it does not grant a new trial.

## 8. Security

Communication with your TV uses HTTPS on your local network, and the TV's certificate is pinned after pairing.
The trial check uses HTTPS.

## 9. Changes

We may update this policy from time to time. Changes will be posted on this page with a new effective date.

## 10. Contact

Questions about this policy or deletion requests: **contact@farelyt.com**

---

FireFly Remote is an independent app and is not affiliated with Amazon.com, Inc.
Fire TV is a trademark of Amazon.com, Inc. or its affiliates.
