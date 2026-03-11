# Privacy Policy (Planova)

**Effective date:** 2026-03-10

Planova (the “App”) is a personal finance, habits, and planning application that can work offline and can optionally sync your data to the cloud using Google Firebase.

This Privacy Policy explains what information is processed, why, and what choices you have.

> **Important:** This document is a template filled for the current Planova architecture (Flutter + Drift + Firebase + AI). Before publishing, you must replace the placeholders in the **“Contact”** section with your real legal name/company and support email.

## 1) Who we are

**Controller / Developer:** Mykyta Zhorov

**Contact email:** nikita98zh@gmail.com

**Country/Region:** Germany

## 2) Summary

The App may process:

- **Account information** (for sign-in), such as email and a user identifier.
- **User content** you enter, such as transactions, accounts, categories, debts, recurring payments, habits, and tasks.
- **Device/technical data** required to provide cloud sync, push notifications, and app stability.

The App:

- Stores your data **locally** on your device (offline-first).
- Can sync data to **Firebase Firestore** under your account if you sign in.
- May send limited data to server-side services (Firebase Cloud Functions) to enable features (sync, notifications, AI).

## 3) Data we process

### 3.1 Account and identity data

If you sign in:

- **Email address** (if you use email/password sign-in).
- **Firebase user ID** (a unique identifier assigned by Firebase Auth).
- Optional profile fields you choose to set (e.g., display name, avatar).

### 3.2 Financial and productivity content

The App may store and sync the content you create, including:

- Financial accounts, balances, currencies.
- Transactions (income/expense/transfers), categories, notes.
- Debts, repayments.
- Recurring payments/subscriptions you track.
- Habits and completions.
- Planner tasks and completions.

When you sign in and use cloud sync, the App may sync some or all of this content to your private cloud storage (Firebase Firestore) under your user account so it can be restored on another device.

### 3.3 Notifications data

If you enable notifications, the App may process:

- **Notification preferences** (what reminders you enabled).
- **Push token** (Firebase Cloud Messaging token), used to deliver push notifications.
- **Language and timezone metadata** (for example, app language code and your timezone when needed) to schedule and localize certain notifications.

The App only stores a push token for server-side notifications after you enable at least one server-side notification type in the App.

### 3.4 Calendar data (optional)

If you enable calendar integration and grant permission:

- The App may connect to your Google Account using Google Sign-In and access Google Calendar via Google Calendar APIs.
- The App may create or use a dedicated calendar named “Planova” and read/write events in that calendar to synchronize your planner tasks.

### 3.5 AI features (optional)

If you enable AI features (for example, AI-generated briefings/insights):

- The App may send **selected data** (such as summaries of your transactions and habits) to server-side AI processing.
- AI outputs are generated automatically and may be inaccurate; you should not treat them as financial advice.

The App may use Google Cloud services for AI processing (for example, Gemini/Vertex AI) via server-side components. AI features are optional and depend on your settings.

### 3.6 Profile photo (optional)

If you upload a profile photo (avatar):

- The App may access images on your device (for example, from gallery or camera, depending on what you choose).
- The photo may be uploaded to Firebase Storage under a private path linked to your user ID.

### 3.7 App lock / device authentication (optional)

If you enable App Lock (Face ID / fingerprint / device PIN):

- The App uses the operating system’s authentication mechanisms.
- The App does not collect or store your biometric data. Biometric data is processed by your device/OS.

## 4) How we use your data (purposes)

We process data to:

- Provide core offline functionality (local storage, analytics, history).
- Provide cloud features (sign-in, sync/backup/restore across devices).
- Deliver reminders and notifications you enabled.
- Provide AI insights if you explicitly enable them.
- Maintain security, prevent abuse, and debug crashes/performance issues.

## 5) Where data is stored

### 5.1 On-device storage

The App stores most data locally in an on-device database.

### 5.2 Cloud storage (Firebase)

If you sign in and enable cloud features, data may be stored in:

- **Firebase Authentication** (account identity).
- **Firebase Firestore** (synced app data).
- **Firebase Storage** (for example, profile images), if used.

If you connect Google Calendar, calendar data is processed via Google Calendar APIs.

## 6) Sharing and third parties

The App uses the following service providers:

- **Google Firebase** (Auth, Firestore, Cloud Functions, Cloud Storage, Messaging, Remote Config).

Depending on your configuration, the App may also use:

- **Google APIs** (e.g., Google Calendar).

We do not sell your personal data.

## 6.1 International data transfers

We use Google infrastructure (Firebase / Google Cloud). Depending on your location and the configuration of Google services, your data may be processed on servers located in other countries.

## 7) Legal bases (EEA/UK)

If you are in the EEA/UK, we process your data under one or more of these legal bases:

- **Contract**: to provide the App features you request (account, sync).
- **Legitimate interests**: to maintain security and improve the App.
- **Consent**: for optional features such as push notifications and AI features (where applicable).

## 8) Data retention

- Local data remains on your device until you delete it in the App or uninstall.
- Cloud data remains associated with your account until you delete it using the in-app deletion feature (if available) or request deletion via the contact email.

## 9) Security

We use reasonable technical measures to protect data, including:

- Transport security (HTTPS/TLS) for network communication.
- Firebase security rules and authentication for cloud data access.

No method of storage or transmission is 100% secure.

## 10) Your choices and rights

You can:

- Use the App offline without signing in (limited cloud features).
- Enable/disable notifications in the App settings and system settings.
- Enable/disable AI features (if available).
- Request access, correction, or deletion of your account data by contacting us.

## 11) Account and data deletion

If the App provides an in-app account deletion feature:

- You can request deletion of your account and associated cloud data from within the App.

In Planova, you can start account deletion from:

- Open the App
- Go to **Profile**
- Select **Delete account** and confirm

When you delete your account, the App is designed to remove:

- Your cloud data stored under your account in Firebase services (for example, Firestore documents and uploaded avatar, if any)
- Your authentication account (Firebase Authentication)
- Local app data on the device (as part of the deletion flow)

Otherwise, you can request deletion by contacting us at the email in the **Contact** section.

## 12) Children

The App is not intended for children. Do not use the App if you are under the age required by your jurisdiction.

## 13) Changes to this policy

We may update this policy from time to time. We will update the “Effective date” at the top.

## 14) Contact

**Developer / Controller:** Mykyta Zhorov

**Support email:** nikita98zh@gmail.com

**Country/Region:** Germany
