# Privacy Policy

**App:** Reclaim — Pomodoro Focus Timer  
**Last updated:** May 6, 2026

Reclaim is developed and operated by **Tuyen Tran** ("I", "we", "our"). This policy explains what information is collected when you use Reclaim and how it is handled.

---

## Summary

- All your tasks and session data stay **on your device only**
- We use **Firebase Remote Config** for app configuration (no personal data)
- We use **TelemetryDeck** for anonymous, privacy-preserving usage analytics
- We do **not** collect your name, email, location, or any personal information
- We do **not** sell or share your data with third parties
- No account or sign-in is required

---

## 1. Data Stored on Your Device

The following data is stored locally on your iPhone using CoreData and UserDefaults. It **never leaves your device** and is never transmitted to any server.

| Data | Purpose |
|------|---------|
| Task titles, estimated time, durations | Core app functionality |
| Session history (focus/break records, timestamps, elapsed time) | Timer accuracy, completion stats, Daily Summary |
| App settings (dark mode, default durations) | Persisting your preferences |
| Onboarding completion state | Showing the tutorial only on first launch |
| Widget data | Displaying your active task on the Home Screen widget |

---

## 2. Firebase Remote Config

Reclaim uses **Firebase Remote Config** (provided by Google) solely to deliver app configuration — specifically the minimum supported app version. This allows us to notify users when an update is required.

Firebase Remote Config may collect:

- A **Firebase Installation ID** — a randomly generated, anonymous device identifier (not linked to you personally)
- Basic **device information** — device model, OS version, app version

Firebase Remote Config does **not** collect your name, email address, location, usage patterns, or any personally identifiable information.

For full details on how Google handles this data, see [Google's Privacy Policy](https://policies.google.com/privacy).

---

## 3. TelemetryDeck Analytics

Reclaim uses **TelemetryDeck** (provided by TelemetryDeck GmbH, Germany) to understand how features are used so we can improve the app. TelemetryDeck is designed from the ground up to be privacy-preserving — it cannot identify you as an individual.

**What TelemetryDeck collects:**

| Data | Purpose |
|------|---------|
| A **one-way hashed** device/user identifier | Counting unique users without identifying them — the hash cannot be reversed |
| App version, iOS version, device type | Understanding which environments to support |
| Locale | Prioritising language improvements |
| In-app events (e.g. task created, session started, streak reached) | Understanding which features are used and where users drop off |

**What TelemetryDeck does NOT collect:**

- Your name, email address, or any contact information
- Task titles or any content you enter
- Your location
- Advertising identifiers (IDFA)
- Any data that can be linked back to you personally

TelemetryDeck processes data on servers located in the **European Union** and operates under GDPR. For full details, see [TelemetryDeck's Privacy Policy](https://telemetrydeck.com/privacy/).

---

## 4. Local Notifications

Reclaim schedules three types of local notifications on your device:

- **8 AM** — daily task reminder
- **7 PM** — end-of-day summary prompt
- **Last 10 seconds of a session** — countdown alert (only when app is minimised)

All notifications are generated and processed entirely on your device. No notification content is sent to or stored on any server.

---

## 5. What We Do Not Collect

- No names, email addresses, or contact information
- No location data (GPS or IP-based)
- No advertising identifiers (IDFA / GAID)
- No task titles or any content you type into the app
- No crash reports (beyond what Firebase Remote Config may log at SDK level)
- No biometric data
- No payment information

---

## 6. Data Sharing

We do **not** sell, rent, or share your personal data with any third party, advertiser, or data broker.

External services used:

| Service | Provider | Data shared |
|---------|----------|-------------|
| Firebase Remote Config | Google | Anonymous device identifier, device model, OS version, app version |
| TelemetryDeck | TelemetryDeck GmbH | One-way hashed identifier, device type, OS version, app version, locale, in-app events |

No task titles, session content, or personally identifiable information is shared with either service.

---

## 7. Data Retention and Deletion

All task and session data lives exclusively on your device. You can permanently delete all app data at any time by uninstalling Reclaim. We have no access to your data and cannot recover it once deleted.

---

## 8. Children's Privacy

Reclaim does not knowingly collect data from children under 13. The app requires no account and collects no personal information beyond what is described above.

---

## 9. Future Features

We plan to add **optional iCloud sync** in a future release. If introduced:

- Sync will be **opt-in**, not automatic
- This privacy policy will be updated before the feature ships
- You will be informed via an app update release note

---

## 10. Your Rights

Regardless of where you live, you have the right to:

- Know what data is held about you (in this case: only what is on your own device)
- Delete your data (by uninstalling the app)
- Contact us with any privacy question or concern

**GDPR (EU users):** Firebase Remote Config processes anonymised device identifiers under Google's own legal basis. TelemetryDeck GmbH is based in Germany, processes data under GDPR, and applies one-way hashing so no personal data leaves your device in identifiable form.

---

## 11. Changes to This Policy

We may update this policy as the app evolves. The "Last updated" date at the top of this page reflects the current version. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 12. Contact

If you have any questions about this privacy policy or how your data is handled:

**Email:** reclaim.feedback@gmail.com

We will respond within 5 business days.
