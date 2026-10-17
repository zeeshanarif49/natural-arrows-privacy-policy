# FireFly Remote — Privacy Policy

**Effective date:** 17 October 2026
**Application:** FireFly Remote – Remote for Fire TV & Firestick (`com.fireflyapps.firetvremote`)

This policy explains what information the FireFly Remote Android app ("the app", "we") handles, and why.
The app lets you control a Fire TV device on your local Wi-Fi network from your phone.

**In short:** the app has no ads, no analytics and no tracking. The only thing that leaves your phone is an
anonymous, one-way hashed device identifier, used to run the 3-day free trial.

---

## 1. Information that stays on your device

To connect to your TV, the app stores the following **only on your phone**. It is never sent to us or to any third party:

- The name and local IP address of Fire TV devices you add or that are discovered on your Wi-Fi network.
- The pairing token issued by your Fire TV after you enter the on-screen PIN, and the TV's certificate fingerprint.
- If you choose ADB mode, a locally generated key used to authenticate with your TV.
- Text you type with the keyboard feature, and the list of apps on your TV. These are exchanged directly with your TV
  on your local network and are not stored or transmitted anywhere else.

We do not require an account, and we do not collect your name, email, contacts, photos, location or advertising ID.

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

## 4. Network permissions

The app uses Wi-Fi and local network access to find and communicate with Fire TV devices on your home network
(mDNS discovery and direct connections to your TV), and internet access to load app icons shown by your TV,
to check your free trial, and to talk to Google Play for purchases.

## 5. Children

The app is not directed at children under 13, and we do not knowingly collect personal information from children.

## 6. Data retention and deletion

All data stored on your phone is deleted when you remove a TV in the app, clear the app's data, or uninstall the app.
The trial record (hashed device identifier and start time) is kept so the free trial can't be restarted.
You can ask us to delete it by emailing us (see Contact); deleting it does not grant a new trial.

## 7. Security

Communication with your TV uses HTTPS on your local network, and the TV's certificate is pinned after pairing.
The trial check uses HTTPS.

## 8. Changes

We may update this policy from time to time. Changes will be posted on this page with a new effective date.

## 9. Contact

Questions about this policy or deletion requests: **contact@farelyt.com**

---

FireFly Remote is an independent app and is not affiliated with Amazon.com, Inc.
Fire TV is a trademark of Amazon.com, Inc. or its affiliates.
