# Privacy Policy for SmartShelf

**Effective Date:** July 3, 2026

Welcome to **SmartShelf** ("we," "our," "us"). We are committed to protecting your privacy and ensuring you have a secure, collaborative, and intelligent experience when managing your household inventory.

This Privacy Policy describes how **SmartShelf** (package: `com.soulshelf.app`) collects, uses, stores, and protects your information when you use our mobile application (the "App").

Please read this Privacy Policy carefully. By downloading, installing, or using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

We only collect information that is strictly necessary to run, sync, and improve the features of SmartShelf.

### A. Personal Data
* **Email Address / Authentication Info:** When you register or log in via Firebase Authentication, we collect your email address. This is required to identify your account, secure your profile, and enable collaborative syncing of shelves across family members.
* **Family Member Profiles:** Name, role (e.g., Owner, Member), and optional avatar emojis are stored to represent collaborators on a shared shelf.

### B. Device, Camera, and Speech Data
* **Camera Access:** We request access to your device's camera. This permission is used exclusively for:
  * **Receipt / Bill Scanning:** Capturing pictures of grocery store bills to automatically parse and import pantry items using AI.
  * **Barcode Scanning:** Scanning product barcodes to identify, lookup, and prefill item details.
* **Voice and Speech Data:** When you tap the microphone button to speak to the AI Assistant, we utilize Google's Speech Recognizer. Voice audio is securely processed into text (in English or Tamil) via the standard Google Speech-to-Text intent overlay.
* **Pantry and Shopping Data:** We store and synchronize all inventory records including item names, stock quantities, units, categories, expiry dates, shopping lists, activity logs, and shared shelf associations.

---

## 2. How We Use Your Information

We use the collected information for the following operational purposes:
* **Real-Time Collaboration & Syncing:** To keep your pantry, shopping list, and family member details synced in real time between all users linked to your shared shelf via your 6-digit invite code.
* **AI Copilot Assistance:** To analyze your inventory and generate answers, summaries, or recipes in Tamil, English, or mixed Tanglish using Google's Gemini API.
* **Passcode Reset and Notifications:** To secure your account, handle password recovery, and send local low-stock or expiry notifications.
* **App Optimization:** To troubleshoot errors, fix performance issues, and enhance the overall experience.

---

## 3. Third-Party Services & APIs

To provide secure syncing, intelligent capabilities, and optimal performance, SmartShelf integrates with reputable third-party SDKs and service providers:

* **Google Firebase (Auth & Cloud Firestore):** Securely manages user authentication and maintains the synchronized database for pantry shelves, shopping lists, and activity logs. [Google Privacy Policy](https://policies.google.com/privacy)
* **Google Gemini AI API:** Translates user questions and processes images of receipts or barcode data to identify food products. No personal, identifying details are transmitted to the Gemini API.
* **Google Speech Recognition:** System-level Speech-to-Text used to recognize spoken English and Tamil commands.
* **Google AdMob:** Integrated to display non-intrusive advertisements in the App. AdMob may collect anonymous device identifiers to show relevant promotions.

We do **not** sell, rent, trade, or share your personal user data with any other external third parties for marketing or commercial purposes.

---

## 4. Device Permissions

To deliver specific features, SmartShelf requires your explicit consent to access certain hardware features. You can grant or revoke these permissions at any time via your device settings:

* **Camera Permission (`android.permission.CAMERA`):** Required for scanning barcodes and taking photos of grocery receipts to parse and sync stock lists.
* **Notification Permission:** Used to alert you about low stock thresholds or items nearing their expiration dates.

*Note on Location Permissions:* SmartShelf **does not** collect, request, or store your geographical location data.

---

## 5. Account Deletion and Data Erasure

We believe you should have complete control over your personal data. You can request to delete your account and erase all your associated records at any time:

### How to request deletion:
1. Navigate to the **Profile / Settings** screen inside the App and select **Delete Account**.
2. Alternatively, send an email request directly to the developer at **aishwaryasri234@gmail.com** with the subject line "Account Deletion Request."

### What gets deleted:
Upon account deletion, the following data is permanently and irreversibly erased from our servers:
* Your email address and authentication profile in Firebase Auth.
* All custom shelf configurations, pantry items, shopping lists, and activity logs created by your account.
* Your associated family member profile links.

---

## 6. Data Storage and Security

Your data is protected using standard, industry-recognized safety measures:
* All cloud-hosted information is stored securely in Firebase Firestore databases, backed by Google Cloud infrastructure.
* Security rules are implemented to ensure only authorized family members with access to your 6-digit shelf code can read or write shelf data.
* Temporary user preferences (like your theme settings or cache data) are kept locally on your physical device.

---

## 7. Children's Privacy

SmartShelf is designed for general family audiences. We do not knowingly collect personal information from children under the age of 13. If you are a parent or guardian and realize your child has provided us with an email address or other personal data without your consent, please contact us immediately, and we will take steps to remove that information from our systems.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to align with legal requirements or product improvements. Any updates will be reflected on this page with an updated effective date. We encourage you to review this policy periodically.

---

## 9. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact us:

* **Developer Name:** [Aishwarya Sri / Developer Name]
* **Contact Email:** aishwaryasri234@gmail.com
