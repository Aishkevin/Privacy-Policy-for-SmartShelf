# Privacy Policy for Soul Shelf

**Effective Date:** October 28, 2026
**Last Updated:** October 28, 2026

Soul Shelf ("we", "our", "us") is a household inventory app that helps you track groceries, expiry dates, shopping lists and shared shelves with your family. This Privacy Policy explains what information the Soul Shelf mobile app (package name: `com.soulshelf.app`, the "App") collects, how it is used, and the choices you have.

By using the App, you agree to the practices described in this policy.

**Developer:** Aishwarya A
**Contact:** aishwaryasri234@gmail.com

---

## 1. Information We Collect

### A. Account information
- **Email address and password:** If you create an account, Firebase Authentication stores your email address and a securely hashed password so we can identify you and sync your data across devices and family members.
- **Anonymous ID:** The App may create an anonymous Firebase user ID so the App can work before you sign in.
- **Profile details:** Your display name, your role on a shelf (for example Owner or Member), and an optional avatar emoji, so shelf members can see who is who.

### B. Content you create
- Pantry items, quantities, units, categories, expiry dates, shopping lists, activity logs, and the shelf codes and join requests that connect family members to a shared shelf.

### C. Photos and camera
- **Receipt / bill scanning:** When you scan a grocery bill, the photo you take is sent to our secure Firebase Cloud Function, which sends it to Google's Gemini API to read the items. The photo is used only to extract the items. We may store the extracted item list (not a copy of your photo) so the same receipt does not need to be processed twice, and we keep a daily scan count per account to prevent abuse.
- **Barcode scanning:** The camera is used to read product barcodes so the App can look up and fill in item details.

### D. Voice input
- If you tap the microphone, the App uses your device's built-in Google speech recognition service to turn your speech (English or Tamil) into text. The App itself does not record or store your audio.

### E. AI assistant requests
- When you use the AI assistant, recipe suggestions or similar features, your question and relevant inventory details (such as item names and quantities) are sent to Google's Gemini API to generate a response. We do not send your email address or name to Gemini.

### F. Advertising and device information
- The App shows ads using Google AdMob. AdMob may collect your device's advertising ID, IP address, and similar device and usage information to show ads and measure their performance. You can reset your advertising ID or opt out of personalized ads in your Android settings (Settings > Google > Ads).

### G. Information we do not collect
- We do not collect your precise or approximate location.
- We do not collect your contacts, SMS messages or call history.

---

## 2. How We Use Your Information

- To provide the App and keep your pantry, shopping list and shared shelves synced in real time between members of the same shelf.
- To run AI features such as receipt scanning, barcode lookup, recipe suggestions and the assistant.
- To send local notifications about low stock and items nearing expiry.
- To secure accounts, prevent abuse and limit usage (for example, daily scan limits).
- To fix bugs and improve the App.
- To show ads through AdMob.

---

## 3. Third-Party Services

The App relies on these services, which process data under their own privacy policies:

- **Google Firebase** (Authentication, Cloud Firestore, Cloud Functions, Remote Config): account login, data storage and sync. https://policies.google.com/privacy
- **Google Gemini API:** reads receipts and generates AI responses. https://policies.google.com/privacy
- **Google speech recognition (on-device service):** voice input. https://policies.google.com/privacy
- **Google AdMob:** advertising. https://policies.google.com/technologies/ads

We do not sell your personal information. We do not share it with anyone else for their own marketing purposes.

---

## 4. Sharing Within Your Shelf

Shelves are collaborative. Anyone who joins your shelf can see the items, shopping list, activity log and the display names of members on that shelf. Joining a shelf requires the shelf code and approval from the shelf owner. Only share your shelf code with people you trust.

---

## 5. Device Permissions

- **Camera:** scan receipts and barcodes.
- **Notifications:** low-stock and expiry reminders.
- **Internet:** sync your data and use AI features.

You can change permissions at any time in your device settings. The App still works without the camera permission, but scanning will not be available.

---

## 6. Data Storage, Security and Retention

- Your data is stored in Google Firebase (Cloud Firestore), on Google Cloud infrastructure. Data may be processed on servers outside your country.
- Data is encrypted in transit using HTTPS.
- Access controls (Firestore security rules) are designed so that only members of a shelf can read or write that shelf's data.
- We keep your data for as long as your account is active. When you delete your account, your data is removed as described below.
- No method of transmission or storage is completely secure, so we cannot guarantee absolute security.

---

## 7. Account and Data Deletion

You can delete your account and data at any time.

**In the App:** open **Profile / Settings** and tap **Delete Account**.

**By email:** if you cannot access the App, email **aishwaryasri234@gmail.com** with the subject "Account Deletion Request" from the email address registered on your account. We will process the request within 30 days.

**What is deleted:**
- Your email address and Firebase authentication profile.
- Your user profile and your pending join requests.
- Shelves you own, including their items, shopping lists, activity logs and invite codes.

Information that is backed up or cached by our service providers may remain for a short period before it is permanently removed.

---

## 8. Your Rights

Depending on where you live, you may have the right to access, correct, export or delete your personal data, or to object to certain processing. To make a request, contact us at aishwaryasri234@gmail.com. You can also delete your data yourself using the steps in Section 7.

---

## 9. Children's Privacy

Soul Shelf is not directed at children under 13 (or the minimum age required in your country). We do not knowingly collect personal information from children. If you believe a child has given us personal information, contact us and we will delete it.

---

## 10. Changes to This Policy

We may update this policy from time to time. When we do, we will change the "Last Updated" date above. Continued use of the App after a change means you accept the updated policy.

---

## 11. Contact Us

**Developer:** Aishwarya A
**Email:** aishwaryasri234@gmail.com
