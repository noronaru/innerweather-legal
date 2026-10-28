---
title: InnerWeather — Privacy Policy
permalink: /privacy-policy
---

<!--
  Approved by the owners for publishing on 2026-10-27, and updated on 2026-10-28 for Plus on
  sale (no Plus day, no ad before a report), with TERMS_VERSION 2026-10-28 in src/js/store.js:
  people accept this policy in the terms gate, whose points must say the same.
  A lawyer's review is still to come, especially: mood entries and notes as health-related data
  and the explicit consents for them (KVKK art. 6, GDPR art. 9), transfers abroad (KVKK art. 9
  as amended in 2024, GDPR chapter V), the legal bases in section 13, and ad consent for users
  under the age of digital consent. The "Lawyer review" notes below are its checklist.
-->

# Privacy Policy

**Effective date:** 2026-10-28

InnerWeather ("the app") is provided by **Noronaru** ("we", "us"). Noronaru is the data controller for the personal data described in this policy. You can reach us at **noronaru@proton.me**.

## In short

- Your journal — mood scores, weather, notes, and voice notes — is stored **on your phone**. It leaves your phone only for features you turn on: cloud backup, sharing your mood with your other apps (Hydrorep and Dozelight), and AI insights.
- **Cloud backup is optional.** If you sign in with Google and turn it on, your entries (without voice notes) are stored in your account on Google Cloud in the **European Union**.
- **AI insights are optional.** When you request one, the mood scores, dates, and weather of that period — and your notes, your training from Hydrorep or your sleep from Dozelight only if you turned that on — are sent to **Anthropic**, the maker of Claude, in the United States (to **OpenAI** in the United States from app versions released before this policy). We do not keep them.
- When you first open the app, it gets a **random identifier** from Google Firebase, so our server can recognize genuine requests and count AI insights. It is not linked to your name or email address unless you sign in with Google.
- The app shows **rewarded ads** from Google AdMob, only when you choose to watch one: before a free AI insight. With Plus there are none. In the European Economic Area, the UK, and Switzerland, Google's consent form asks how ads may use your data, and you can change your choice in Settings.
- InnerWeather is **not a medical service** and is not meant for emergencies.

## 1. Your journal on your phone

The app stores the following in its private storage on your phone:

- Daily entries: date, mood score, weather, and notes you write
- Voice notes you record
- Your settings and choices, such as theme, language, reminder time, and what you agreed to share
- AI insights and reports you have received
- Small records the app needs, such as an AI insight you watched an ad for that has not reached you yet

We have no access to this information unless you turn on one of the features below that sends it. If you export a backup, the file is saved to your phone and stays under your control.

**Android's own backup.** Android's backup to your Google account does not include your journal, your voice notes, or your sign-in. On Android 12 and later, a phone-to-phone transfer that you start yourself (by cable or wirelessly) moves them straight to your new phone. To keep your journal when you lose, replace, or reset your phone, use cloud backup (section 3) or **Export backup** in Settings.

**Your other apps.** To show our other apps in its app bar, InnerWeather asks Android whether Hydrorep and Dozelight are installed on your phone. The answer stays on your phone.

Uninstalling the app or clearing its storage deletes all of this from your phone.

## 2. Your account

**Anonymous account.** When you open the app for the first time — and again after you sign out or delete your account — it signs in to **Firebase Authentication (Google)** with a random identifier. The identifier contains no name, email address, or phone number. Our server uses it to recognize requests from the app (section 5) and to count AI requests (section 6). Google processes it in the United States.

**Signing in with Google (optional).** In Settings → Account you can sign in with your Google account. Firebase Authentication then links your Google account's email address, name, profile picture link, and account ID to your identifier, which stays the same. Signing in is needed for cloud backup, for connecting InnerWeather with Hydrorep and Dozelight, and for Plus. If you also use Hydrorep, our workout tracker, or Dozelight, our sleep app, the same Google account signs you in to them: one account for all three.

**Signing out** (Settings → Account) turns off cloud backup and mood sharing — the mood scores you shared are deleted — and the choices to include your training and your sleep in AI insights, and the app continues with a new anonymous identifier. Your journal stays on your phone, and your backup stays in your account.

**Deleting your account** (Settings → Account → Delete account) deletes, for InnerWeather, Hydrorep and Dozelight alike: your Google sign-in, your cloud backup, the mood scores you shared, Hydrorep's cloud backup, the training and water summaries Hydrorep shared and the nights Dozelight shared. It then deletes the records our server keeps on your identifier (sections 6 and 7) and your subscription record at RevenueCat (section 9). It does not cancel a subscription in Google Play. Your journal on your phone stays.

## 3. Cloud backup (optional)

Cloud backup works only if you are signed in with Google and agree to it in the app. Your entries — date, mood score, weather, note, and when each was written and last changed — are stored in your account in **Google Cloud Firestore (Firebase) in the European Union** and kept in step across the phones where you use the same account. Voice notes are never backed up. The app also keeps an offline copy of the synced entries on your phone.

Turning backup off stops syncing; it does not delete the copy in your account. To delete that copy, delete your account, or write to us and we will delete only the backup.

## 4. Hydrorep and Dozelight (optional)

Hydrorep is our workout tracker app and Dozelight our sleep app, each with its own privacy policy ([Hydrorep](https://noronaru.github.io/hydrorep-legal/privacy-policy), [Dozelight](https://noronaru.github.io/dozelight-legal/privacy-policy)). They sign in with the same Google account as InnerWeather.

- **Sharing your mood with your other apps.** If you turn on **Share with my other apps** in Settings → Account and agree, the app stores each logged day's mood score in your account (Google Cloud Firestore, European Union) — the number only, never your notes, weather, or voice notes. It shares the last 90 days when you turn it on, and then every change. Hydrorep reads the scores to show your mood next to your workouts and, with Plus, to take it into account, and Dozelight to show it beside your nights. Hydrorep's AI coach can include them only if you agree to that in Hydrorep, as its privacy policy describes. Turning sharing off, signing out, or deleting your account deletes the shared scores. When what sharing covers changes, it pauses until you agree to the new terms.
- **Your training from Hydrorep.** If you allowed Hydrorep to share your training, InnerWeather reads Hydrorep's daily summary — number of workouts, time, volume, calories, average difficulty, and when the last workout finished — and, if Hydrorep shares it too, each day's water total and goal. It shows them in the day view and in Training & mood.
- **Your nights from Dozelight.** If you allowed Dozelight to share your nights, InnerWeather reads them — how long and how well you slept, when you went to bed and woke up, and the night's tags — to show the night before a day in the day view, in Sleep & mood, and in the Your apps sheet.

InnerWeather reads your training and nights from your account when needed and does not store them, apart from the offline copy the app keeps on your phone. They are sent for AI insights only as described in section 6.

## 5. App security

- **Firebase App Check and Google Play Integrity (Google)** check that requests to our server come from the genuine app on a genuine device.
- Requests to our server are encrypted in transit (HTTPS) and carry your account's identifier.

## 6. AI insights and reports (optional)

AI insights are available after you watch a rewarded ad (Plus members skip the ad), and only when you choose to request one. The monthly **Training & mood report** and a **season's report** come with Plus.

**What is sent.** For a weekly or monthly insight: the mood scores, dates, and weather you logged in that period. Your **notes** are sent only if you turn on **Include notes in AI insights**. Your **training** — number of workouts, time, and difficulty per day, never volume or calories — is sent only if you are signed in with Google and turn on **Hydrorep training in AI insights**. Your **sleep** — for each day, the night before it: how long and how well you slept, bed and wake times, and the night's tags — is sent only if you are signed in with Google, Dozelight shares your nights, and you turn on **Dozelight sleep in AI insights**. All three are off by default and can be changed at any time in Settings, and our server discards them unless they are on. Voice notes are never sent.

For the monthly **Training & mood report**: the mood scores, dates, and weather of the month's logged days, each with that day's training. Never notes or sleep. For a **season's report**: what an insight would send for each logged day of the season — notes, training, and sleep only as you chose for AI insights, a long note shortened.

**How it is processed.** The data travels encrypted to our server, which runs on Google Cloud in the United States, and is forwarded to **Anthropic** in the United States, whose Claude models write the insight (app versions released before this policy use **OpenAI** in the United States instead). We do not store the data you send or the resulting insight on our servers; the insight is saved on your phone. According to the published commercial terms of Anthropic (and of OpenAI) at the time of writing, data sent through their APIs is not used to train their models by default and may be retained for a limited period, among other things for abuse monitoring.

**Safety screening.** If your notes are included, they — and every generated insight — are checked for signs of self-harm by an Anthropic Claude model (by OpenAI's moderation service, from app versions released before this policy). If such signs are found, the app shows support resources instead of an insight. The result of this check is not stored.

**Usage limits.** To prevent abuse and keep costs in check, our database (Google Cloud Firestore, United States) stores your identifier with the date of your last AI request, or report of an insight, how many you made that day, and a random identifier for each AI insight request, so one asked again after its answer was lost is not counted twice — deleted after 2 days — and how many reports you asked for each month or season, deleted after 60 days. These records contain no journal content.

**Your choice.** You can use InnerWeather without AI insights.

<!-- Lawyer review: confirm that the in-app AI consent dialog satisfies KVKK and GDPR explicit
     consent for health-related data (including the training and sleep it may add) and for
     transferring it to the United States. -->

## 7. Reporting an AI insight

If you report an insight as harmful or inappropriate, we store the insight's text, which kind it was (weekly, monthly, training, or season), your identifier, and the time of the report. We use this only to review the report and improve safety. Reports are **deleted automatically after 90 days**.

## 8. Advertising

The app shows **rewarded ads** through **Google AdMob**, only when you choose to watch one: before a free AI insight. There are no banners and no ads between screens. AdMob may collect your device's advertising ID and app set ID, your IP address, information about your device and the app, and your interactions with ads, to show ads, measure them, prevent fraud, and — where allowed — personalize them. Ads are limited to content rated for teens.

**Your choice.** In the European Economic Area, the UK, and Switzerland, Google's consent form asks how ads may use your data when you open the app, and no ads are loaded until it has your answer. You can change your choice at any time in **Settings → Help & legal → Ad privacy choices**. Your choice is stored on your phone. In any country, you can opt out of personalized ads or delete your advertising ID in your phone's settings.

Learn more in [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites) and the [Google Privacy Policy](https://policies.google.com/privacy).

## 9. Plus

Plus is one subscription for InnerWeather, Hydrorep and Dozelight, sold through **Google Play**, which handles payment; we never see your payment details. To check and restore Plus in all three apps, the apps and our server use **RevenueCat** (United States). RevenueCat receives your account's identifier when you are signed in with Google (otherwise a random identifier it creates), your purchases and subscription status from Google Play (such as product, price, and dates), and basic information about your device and the app, such as the Android version, app version, country, and IP address. Learn more in [RevenueCat's privacy policy](https://www.revenuecat.com/privacy).

## 10. Reminders

Daily reminders are scheduled on your phone. We do not operate a notification server.

## 11. Children

InnerWeather is not directed at children under 13, and we do not knowingly collect personal data from them. If you are under 18, please use the app only with permission from a parent or guardian. If you believe a child under 13 has used the app, contact us and we will help remove any related records.

<!-- Lawyer review: decided on 15 October 2026 that users from 13 may use the app, with a
     parent's or guardian's permission under 18 (the terms gate's age checkbox says so). Ads are
     not tagged for users under the age of digital consent, since the app doesn't ask anyone's
     age. Confirm this is enough in the EEA (consent ages 13 to 16) and in Türkiye. -->

## 12. Where your data is processed

- **European Union:** cloud backup, the mood scores you share, and what you read from Hydrorep and Dozelight (Google Cloud Firestore).
- **United States:** your identifier and Google sign-in (Firebase Authentication), our server and its usage records (Google Cloud), AI insights and reports (Anthropic; OpenAI for app versions released before this policy), purchases (RevenueCat), and ads (Google AdMob, which may also process data in other countries).

If you live in Türkiye, the European Union, or another country, this means some of your data is transferred abroad. We rely on the safeguards the law requires for these transfers.

<!-- Lawyer review: name the transfer mechanism for each provider — KVKK art. 9 as amended in
     2024 (standard contracts notified to the Authority, or occasional transfers with explicit
     consent) and GDPR chapter V (standard contractual clauses or the EU-US Data Privacy
     Framework) — and whether the EU backup still needs one, given Firebase is a US company. -->

## 13. Legal bases

<!-- Lawyer review: confirm each basis under both KVKK (arts. 5 and 6) and GDPR (arts. 6 and 9). -->

- **Your explicit consent** for AI insights and reports (and for including your notes, training, or sleep in them), cloud backup, and sharing your mood with Hydrorep and Dozelight. Mood entries and notes can reveal information about your health, so they are only used for these after you agree in the app. You can withdraw your consent at any time by turning the feature off.
- **Your consent** for personalized ads where the law requires it (the consent form in section 8).
- **Providing the service you ask for** (our contract with you) for your Google sign-in and Plus.
- **Our legitimate interests** in keeping the service secure and preventing abuse: the anonymous identifier, App Check, usage limits, and reviewing reports.

## 14. How long we keep data

- **On your phone:** until you delete it, by clearing the app's storage or uninstalling the app.
- **Cloud backup and shared mood scores:** until you delete them as described in sections 3 and 4, or delete your account.
- **Your Google account:** until you delete your account.
- **Anonymous identifiers:** deleted automatically 30 days after they were created; the app then gets a new one. An anonymous identifier is no longer linked to your phone once you uninstall the app or clear its storage.
- **Daily usage counts:** 2 days. **Monthly and season counts:** 60 days. **Reports:** 90 days.

<!-- Lawyer review: the 30 days rely on Firebase's automatic clean-up of anonymous accounts
     (Identity Platform) being turned on, and the 2 days on Firestore TTL policies on expire_at
     for rate_limits, report_limits and coach_daily_limits - both before this text is published. -->

## 15. Your rights

Depending on where you live — including under the Turkish Personal Data Protection Law (KVKK) and the EU General Data Protection Regulation (GDPR) — you may have the right to access, correct, or delete your personal data, to receive a copy in a portable format, to object to or restrict its processing, and to withdraw consent at any time.

- **Your journal:** you can edit or delete any entry in the app (deleting an entry also deletes its cloud copy and shared mood score; your backup keeps only its date and when it was deleted, so your other phones delete it too), save a copy with **Export backup**, and delete everything from your phone by clearing the app's storage or uninstalling the app.
- **Your cloud data:** delete your account in Settings → Account, or ask us to delete only your cloud backup. Step-by-step instructions, with or without the app: [Delete your account](./delete-account).
- **Anything else**, including records tied to an anonymous identifier: write to **noronaru@proton.me**. We will answer within 30 days.

You also have the right to lodge a complaint with a data protection authority — in Türkiye, the Personal Data Protection Authority (KVKK); in the EU, the authority where you live or work.

## 16. Security

Data sent to our server and to Firebase is encrypted in transit (HTTPS). Access to our server and databases is restricted.

## 17. Not a medical service

InnerWeather does not provide medical, psychological, or crisis advice and is not a substitute for professional care. If you are in crisis, please contact emergency services or someone you trust, or find a helpline in your country at [findahelpline.com](https://findahelpline.com).

## 18. Changes to this policy

When we update this policy, we change the effective date above. If a change affects how your data is used, the app will ask you to review and accept it again.

## 19. Contact

Noronaru — **noronaru@proton.me**
