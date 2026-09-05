# Coinistry Privacy Policy

**Effective date:** 26 August 2026  
**Last updated:** 26 August 2026

This Privacy Policy describes how **Coinistry** (“the app,” “we”) handles information when you use the Coinistry iOS application. Coinistry is a personal finance tracker designed to keep your ledger on your device. We do not operate a Coinistry cloud account or a Coinistry server that stores your transactions.

If you have questions, contact us at **[coinistry@outlook.com](mailto:coinistry@outlook.com)**.

---

## 1. What data your app collects

Coinistry does **not** require you to create an account, and we do **not** collect your financial ledger on our own servers.

### 1.1 Information stored only on your device

The following stays on your iPhone (or on a backup file you export yourself). We cannot see it unless you choose to send it to us (for example in an email you write):

| Category | Examples |
|----------|----------|
| **Financial records** | Transactions (amounts, merchants, dates, categories, accounts, payment methods, notes, hashtags), budgets, Settlement Tracker entries |
| **SMS text you import** | Bank or payment SMS that you paste, share into Coinistry, or send via the Shortcuts **Save SMS** action. Parsing runs on the device. The app cannot read your Messages inbox on its own. |
| **Files you import or attach locally** | CSV/PDF you import, encrypted `.evault` backups you create, and any transaction attachment paths stored by the app |
| **Preferences** | Display currency, appearance, start tab, analytics chart choices, App Lock on/off, reminder times, Free/Prime feature flags |
| **App Lock** | Whether lock is enabled. Unlock uses Face ID, Touch ID, Optic ID, or your device passcode through Apple’s system. Biometric templates are handled by iOS, not by Coinistry. |
| **Local notifications** | Daily expense reminders and (on Prime) budget alerts are scheduled on the device. There is no Coinistry push-notification server. |
| **Diagnostics you may send** | If you use **Settings → Send feedback**, Mail opens with a draft that includes **app version, bundle ID, device model, iOS version, screen size, locale, time zone, and similar technical fields**. It does **not** include your transactions. You can edit or delete that text before sending. |

Uninstalling the app, using **Factory reset**, or deleting individual records removes on-device data according to those actions. Encrypted backups and files you already shared (AirDrop, Files, Mail, iCloud Drive, and so on) remain wherever you put them.

### 1.2 Information we receive if you contact us

If you email **coinistry@outlook.com**, we receive whatever you include (your email address, message, and any attachments). We use that only to respond to support, feedback, or legal requests.

### 1.3 Information we do not collect as Coinistry

We do not run our own analytics, crash-reporting, or marketing SDKs. We do not sell your ledger. We do not use your transactions to train models or to profile you for advertising.

---

## 2. Third-party services used

Coinistry may use the following third parties. Each has its own privacy policy. We do not control how those parties process data once it reaches them.

| Service | Role | Privacy information |
|---------|------|---------------------|
| **Apple** | iOS, App Store, optional in-app purchase (when StoreKit is enabled), Mail when you send feedback, system share sheet, iCloud if *you* save files there, Face ID / Touch ID | [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| **Google AdMob** (Google Mobile Ads SDK, including related Google advertising and messaging components bundled with the SDK) | Ads on the **Free** tier | [Google Privacy Policy](https://policies.google.com/privacy) · [How Google uses information from apps](https://policies.google.com/technologies/partner-sites) · [AdMob](https://support.google.com/admob) |
| **Email provider (Outlook)** | Receives mail you send to coinistry@outlook.com | Microsoft’s privacy terms for Outlook / Microsoft 365 |

**Share extension and Shortcuts:** Text you share into Coinistry is stored in an on-device App Group so the main app can import it. That queue is not sent to a Coinistry server.

**Encrypted backup:** Export uses AES-256-GCM with a key stored in the device Keychain. The file leaves the device only when you share or copy it.

When you complete an App Store purchase (once offered), Apple processes payment. Coinistry does not receive your full card number.

---

## 3. Google AdMob / advertising

On the **Free** tier, Coinistry shows Google AdMob ads, including:

- Adaptive **banner** ads on main tabs (Dashboard, Transactions, Analytics, Budget)
- **Medium rectangle** placements where used in the UI
- **Interstitial** (full-screen) ads after certain actions (for example after several saved transactions, or when opening some Prime-gated screens)

Ads are **not shown** when Prime is active. Settings does not show the tab banner.

The Google Mobile Ads SDK is started when the app launches so ads can load for Free users. Google may receive technical data needed to serve or measure ads (see Google’s policies). **Your transaction list, SMS bodies, budgets, and backup files are not sent to AdMob by Coinistry.**

To remove ads in the app, unlock **Prime**.

---

## 4. Advertising identifiers and ad personalization

Coinistry does not implement its own advertising identifier collection or cross-app tracking.

Google’s advertising SDK **may**:

- Use the device **advertising identifier** (IDFA) **if** Apple’s App Tracking Transparency permission is granted
- Use other signals allowed by Apple and Google (for example SKAdNetwork conversion data, IP address, device type, approximate location derived from IP, and ad interaction events) to serve, personalize, or measure ads
- Serve **non-personalized** ads when tracking is denied, limited, or otherwise unavailable

**Your choices**

- iOS **Settings → Privacy & Security → Tracking** (and any Coinistry tracking prompt, if shown)
- iOS **Settings → Privacy & Security → Apple Advertising** (Personalized Ads)
- [Google Ads Settings](https://adssettings.google.com/)
- Reset the advertising identifier in iOS Settings

SKAdNetwork identifiers in the app help Apple and ad networks attribute installs in a privacy-preserving way. Coinistry does not use that data to identify you as a person.

Personalized advertising, if it occurs, is performed by **Google and its partners**, not by building a Coinistry advertising profile from your spending data.

---

## 5. Contact information

| | |
|--|--|
| **Support and privacy requests** | [coinistry@outlook.com](mailto:coinistry@outlook.com) |
| **In the app** | **Settings → Send feedback** (opens Mail) · **Settings → Privacy policy** (this policy) |

We will use the contact details you provide only to handle your request. We may retain support email as needed to provide help, prevent abuse, or meet legal obligations.

---

## 6. How we use information

| Purpose | What we use |
|---------|-------------|
| Provide the app | On-device ledger and settings |
| Ads (Free) | Google AdMob, as described above |
| Support | Email you send us, including optional diagnostics in the feedback template |
| Security and integrity | App Lock on device; we do not operate a Coinistry login |

Legal bases (where GDPR or similar laws apply) include: providing the service you request, our legitimate interest in showing ads on the Free tier and answering support mail, and consent where required (for example tracking permission or marketing cookies on third-party sites you visit).

---

## 7. Sharing

We do not sell your personal information. We share information only:

- **With you**, when you export or share files
- **With Apple and Google**, as needed for the OS, App Store, and ads
- **With our email provider**, when you write to us
- **If required by law**, or to protect rights, safety, and the app

---

## 8. Children

Coinistry is not directed at children under 13 (or the equivalent age in your country). We do not knowingly collect personal information from children. If you believe a child has sent us personal information by email, contact **coinistry@outlook.com** and we will delete it from our mailbox where reasonably possible.

---

## 9. Data retention and deletion

- **On device:** You control deletion (edit/delete transactions, Factory reset, uninstall).
- **Backups you created:** You control those files.
- **Email:** Kept as long as needed for support and legal reasons, then deleted or archived according to ordinary mailbox practice.
- **Ad data:** Retained by Google according to Google’s policies.

---

## 10. International processing

Your ledger is processed on your device. Support email and advertising may be processed in other countries (including the United States) by Apple, Google, or Microsoft. Those transfers follow those companies’ terms.

---

## 11. Changes

We may update this policy when the app or the law changes. The **Last updated** date at the top will change. Continued use after an update means you accept the revised policy. Material changes may also be noted in the App Store “What’s New” text when practical.

---

## 12. Your rights

Depending on where you live, you may have rights to access, correct, delete, or restrict processing of personal information we hold (typically support email). For on-device data, use the app’s delete and reset features. For AdMob data, use Google’s tools and Apple’s tracking settings.

To exercise rights regarding information we hold by email, write to **coinistry@outlook.com**.

---

This policy applies to the Coinistry iOS app. It does not cover websites or services you open from ads or from files you share with other apps.
