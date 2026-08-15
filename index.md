# Privacy Policy for Tranza

**Effective Date:** August 15, 2026  
**Developer:** John Michael Gemino

---

## 1. Introduction

Welcome to **Tranza** ("we," "our," or "the App"). Tranza is a mobile application designed to help cash agents and store owners manage and track their cash-in, cash-out, and fund transfer transactions.

We are committed to protecting your privacy and being transparent about how we handle your data.

**Key Principle:** Tranza does not operate servers or cloud databases for storing your app data. Your transaction and app data is stored locally on your device. Certain features, such as Google Play Billing for in-app purchases, communicate with third-party services required to provide those features.

---

## 2. Information We Collect

### 2.1 Information You Provide

When you use Tranza, you may enter the following types of information, all of which is stored **on your device**:

- **Transaction Data:** Transaction type (cash-in, cash-out, fund transfer), reference numbers, base amounts, fee amounts, total collected, net release, customer names, and notes.
- **Wallet Information:** Wallet names, wallet types (e.g., GCash, Maya), current balances, custom colors, and custom logo images.
- **Fee Configuration:** Custom fee rules, fee settings, and increment configurations.
- **Receipt Images:** Photos of transaction receipts captured via your device's camera or selected from your photo gallery.
- **Custom Wallet Logos:** Images you upload as wallet logos from your photo gallery.

### 2.2 Information Collected Automatically

- **App Preferences:** Theme selection (light, dark, or system), OCR debug mode toggle, and receipt auto-delete settings. These are stored locally using standard Android preferences.
- **Premium License Data:** If you purchase Tranza Premium, your Google Play purchase token, product ID, purchase date, and verification timestamp are stored in encrypted local storage on your device. This information is used solely to verify your premium status.

### 2.3 Information We Do NOT Collect

- We do **not** collect your name, email address, phone number, or any other personal contact information through the App.
- We do **not** collect your location data.
- We do **not** collect device identifiers, advertising IDs, or analytics data.
- We do **not** use cookies, tracking pixels, or any form of online tracking.
- We do **not** collect or transmit usage statistics or crash reports.

---

## 3. How We Use Your Information

All data entered into Tranza is used **solely to provide the App's core functionality** on your device:

| Purpose | Data Used |
|---------|-----------|
| Record and display transactions | Transaction data, reference numbers, amounts |
| Track wallet balances | Wallet information and transaction records |
| Auto-fill transaction details via OCR | Receipt images (processed on-device) |
| Calculate transaction fees | Fee rules and settings |
| Export transaction records | Transaction data (exported to CSV by your action) |
| Backup and restore data | All app data (initiated by you) |
| Verify premium status | Google Play purchase token |
| Personalize appearance | Theme and display preferences |

**No data is used for advertising, marketing, profiling, or any purpose other than the direct functionality of the App.**

---

## 4. OCR (Optical Character Recognition) Processing

Tranza uses **Google ML Kit Text Recognition** to scan receipt images and automatically extract transaction details such as reference numbers, amounts, and wallet types.

Tranza uses the **bundled** (on-device) variant of Google ML Kit. The text recognition model is included within the App itself and runs locally on your device. Receipt images are **not uploaded** to any server or cloud service for OCR processing, and no internet connection is required for this feature to function.

---

## 5. Data Storage and Security

### 5.1 Local Storage

All app data is stored on your device using the following mechanisms:

- **SQLite Database (Drift):** Transaction records, wallet data, and fee configurations are stored in a local SQLite database within the app's private storage area.
- **Application Documents Directory:** Receipt images and custom wallet logos are saved as files in the app's private documents directory.
- **Encrypted Storage (FlutterSecureStorage):** Premium license information is stored using Android's Keystore-backed encryption.
- **SharedPreferences:** Non-sensitive settings such as theme preference and auto-delete configuration.

### 5.2 Security Measures

- Sensitive data (premium license) is encrypted using Android Keystore-backed encryption.
- App data is stored within Android's sandboxed application storage, which is not accessible to other apps under normal circumstances.
- Backup files are created only when you explicitly choose to back up your data and are saved to a location you control.

### 5.3 Your Responsibility

Since all data is stored locally on your device, the security of your data also depends on the security measures you have in place on your device (e.g., screen lock, device encryption). We recommend enabling device-level security features to protect your data.

---

## 6. Permissions and System Access

Tranza is designed to respect your privacy and minimizes access to your device's features:

| Feature / Permission | Mechanism & Purpose |
|----------------------|---------------------|
| **Camera** | Used with your explicit permission to capture receipt photos for on-device OCR scanning and transaction record-keeping. |
| **Photo & File Selection** | Uses the modern **Android Photo Picker** and **Storage Access Framework (SAF)**. When you choose a receipt photo, select a custom wallet logo, export CSV data, or save/restore backup files, you select specific files or folders directly through the Android system dialog. Tranza does **not** request or require broad access to your device's photo gallery or external storage. |

All access is initiated solely by your explicit actions (e.g., tapping to capture a receipt, picking an image from your gallery, choosing an export directory, or selecting a backup file). Camera permission can be granted or revoked at any time through your device's Settings.

---

## 7. Third-Party Services

Tranza uses the following third-party service:

### Google Play Billing

- **Purpose:** Processing one-time in-app purchases for Tranza Premium.
- **Data Shared:** Purchase transactions are handled entirely by Google Play. We receive a purchase verification token from Google Play to confirm your premium status. We do not have access to your payment information (credit card details, etc.).
- **Google's Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

**We do not use any other third-party services**, including but not limited to:
- No analytics services (e.g., Firebase Analytics, Google Analytics)
- No advertising networks or ad SDKs
- No crash reporting services (e.g., Crashlytics, Sentry)
- No social media integrations
- No cloud storage services

---

## 8. Data Sharing

**We do not share, sell, rent, or trade your data with any third parties.**

The only ways your data leaves the App are through actions **you explicitly initiate**:

- **CSV Export:** You can export your transaction records to a CSV file saved to a location you choose on your device.
- **Backup:** You can create a backup file (ZIP) containing your database, receipt images, and wallet logos, saved to your device.
- **Share:** You can share backup files or CSV exports using your device's share functionality (e.g., sending via email, messaging apps, or cloud storage). This is entirely under your control.

---

## 9. Data Retention and Deletion

### 9.1 Data Retention

Your data is retained on your device for as long as the App is installed and you choose to keep it. We do not have access to or copies of your data.

### 9.2 Deleting Your Data

You have full control over your data:

- **Delete individual transactions** from within the App.
- **Delete wallets** and their associated data.
- **Auto-delete old receipt images** using the configurable auto-delete feature (after 90, 120, 180, or 365 days).
- **Manually purge old receipts** from the Settings screen.
- **Uninstall the App** to remove the App's locally stored data from your device.

### 9.3 Backup and Residual Data

Backup files you create are saved to your device's storage (e.g., the Downloads folder). These files persist independently of the App and will remain even after uninstalling. You are responsible for managing or deleting these backup files.

Uninstalling Tranza removes the App's locally stored data from the device, subject to Android's backup and restore behavior. If you have enabled Android's automatic backup feature in your device settings, some app data may be backed up to your Google account as part of Android's standard system behavior.

---

## 10. Nature of the App

Tranza is a **transaction recording and tracking tool**. It is designed to help users log and manage their cash-in, cash-out, and fund transfer transactions.

Tranza does **not**:
- Move money between users or accounts
- Hold customer funds
- Operate as a digital wallet or payment service
- Directly execute payments through GCash, Maya, or any other financial platform
- Perform bank transfers or financial transactions

Recording a transaction in Tranza is a bookkeeping activity and does not constitute a financial transaction.

---

## 11. Children's Privacy

Tranza is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. The App is designed for use by cash agents, store owners, and individuals who manage cash-in and cash-out transactions.

If you are under the age of 13, please do not use this App.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in the App's features or applicable laws. When we make changes:

- The "Effective Date" at the top of this policy will be updated.
- Significant changes will be communicated through the App or the Google Play Store listing.

We encourage you to review this Privacy Policy periodically for any updates.

---

## 13. Your Rights

Since all data is stored locally on your device and we do not collect or have access to any of your data, you already have full control over your information. You can access, modify, export, and delete your data at any time through the App.

---

## 14. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or the App's data practices, please contact us:

- **Developer:** John Michael Gemino
- **Privacy Email:** johnmichaelgemino.dev@gmail.com
- **Support Email:** support.tranza@gmail.com

---

*This Privacy Policy was last updated on August 15, 2026.*
