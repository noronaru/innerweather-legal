---
title: InnerWeather — Privacy Policy
permalink: /privacy-policy
---

<!--
  DRAFT — have a lawyer review this before publishing, especially the KVKK (Turkish Personal
  Data Protection Law) sections on health-related data and transfers abroad.
  Replace before publishing: [SUPPORT_EMAIL], [EFFECTIVE_DATE].
  Keep this document in sync with TERMS_VERSION in src/js/store.js — bump the version when
  a change here requires people to accept again.
-->

# Privacy Policy

**Effective date:** 2026-09-13

InnerWeather ("the app") is provided by **Noronaru** ("we", "us"). Noronaru is the data controller for the personal data described in this policy. You can reach us at **noronaru@proton.me**.

## In short

- Your journal — mood scores, weather, notes, and voice notes — is stored **on your device**. We do not upload it.
- AI insights are **optional**. When you request one, your mood scores, dates, and weather for that period are sent to OpenAI to generate it. Your **notes are included only if you turn that on**. We do not store what is sent or the insight on our servers.
- The app shows ads through Google AdMob, which collects device identifiers to deliver and measure ads.
- InnerWeather is **not a medical service** and is not meant for emergencies.

## 1. Information that stays on your device

The following is stored only in the app's storage on your device:

- Daily entries: date, mood score, weather, and notes you write
- Voice notes you record
- Reminder times and app preferences (such as theme and whether notes are included in AI insights)
- AI insights you have received

We have no access to this information. If you export a backup, the file is saved to your device and stays under your control. Uninstalling the app or clearing its data deletes this information from your device.

## 2. AI insights (optional)

AI insights are available after you watch a rewarded ad, and only when you choose to request one.

**What is sent.** For a weekly or monthly insight, the mood scores, dates, and weather you logged in that period. Your notes are sent **only if you turn on "Include notes in AI insights"**, which is off by default and can be changed at any time in Settings. Voice notes are never sent.

**How it is processed.** The data travels over an encrypted connection to our server, which runs on Google Cloud in the United States, and is forwarded to **OpenAI** in the United States to generate the insight. We do not store the data you send or the resulting insight on our servers; the insight is saved on your device. According to OpenAI's published API data usage policies at the time of writing, data sent through its API is not used to train its models by default and may be retained for a limited period for abuse monitoring.

**Safety screening.** If your notes are included, they — and every generated insight — are checked by OpenAI's moderation service for signs of self-harm. If such signs are found, the app shows support resources instead of an insight. The result of this check is not stored.

**Your choice.** You can use InnerWeather without AI insights. You can stop sharing notes at any time in Settings.

<!-- Lawyer review: confirm that the in-app AI consent dialog satisfies KVKK explicit consent
     requirements for health-related data and for transferring it abroad. -->

## 3. App security and abuse prevention

- **Firebase Anonymous Authentication (Google).** When you use AI features, the app creates a random identifier. It does not include your name, email address, or phone number.
- **Firebase App Check and Google Play Integrity (Google).** These verify that requests to our server come from the genuine app on a genuine device.
- **Usage limits.** To prevent abuse, our database (Google Cloud Firestore, United States) stores your anonymous identifier with the current date and the number of AI insight requests and reports made that day. This record contains no journal content.

## 4. Reporting an AI insight

If you report an insight as harmful or inappropriate, we store the insight's text, whether it was weekly or monthly, your anonymous identifier, and the time of the report. We use this only to review the report and improve safety. Reports are **deleted automatically after 90 days**.

## 5. Advertising

The app shows rewarded ads through **Google AdMob**. AdMob may collect your device's advertising ID, IP address, and information about ad interactions to deliver ads, measure their performance, and — depending on your device settings — show personalized ads. You can reset your advertising ID or opt out of personalized ads in your Android settings. Learn more in [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites) and the [Google Privacy Policy](https://policies.google.com/privacy).

## 6. Reminders

Daily reminders are scheduled on your device. We do not operate a notification server.

## 7. Children

InnerWeather is not directed at children under 13, and we do not knowingly collect personal data from them. If you are under 18, please use the app only with permission from a parent or guardian. If you believe a child under 13 has used AI features, contact us and we will help remove any related server records.

## 8. Transfers outside your country

Our server provider (Google) and AI provider (OpenAI) process data in the **United States**. If you live in Türkiye, the European Union, or another country, this means your data is transferred abroad when you use AI insights, report an insight, or see ads.

## 9. Your rights

Depending on where you live — including under the Turkish Personal Data Protection Law (KVKK) and the EU General Data Protection Regulation (GDPR) — you may have the right to access, correct, or delete your personal data, to object to or restrict its processing, and to withdraw consent.

Because your journal stays on your device, you control it directly: you can edit or delete entries in the app, or delete everything by uninstalling the app. Server records contain only an anonymous identifier, dates, counts, and reported insight text; uninstalling the app removes that identifier from your device. For any request or question, contact **noronaru@proton.me**.

## 10. Security

Data sent to our server is encrypted in transit (HTTPS). Access to our server and database is restricted.

## 11. Not a medical service

InnerWeather does not provide medical, psychological, or crisis advice and is not a substitute for professional care. If you are in crisis, please contact emergency services or someone you trust, or find a helpline in your country at [findahelpline.com](https://findahelpline.com).

## 12. Changes to this policy

When we update this policy, we change the effective date above. If a change affects how your data is used, the app will ask you to review and accept it again.

## 13. Contact

Noronaru — **noronaru@proton.me**
