# Privacy Policy
Effective Date: [31-08-2025]

At XSpeed, your privacy is important to us. This Privacy Policy explains how we handle your information when you use our mobile application (“App”).

## 1. Information We Collect
 - XSpeed is a simple internet speed test app.
 - We do not collect, store, or share any personal information such as your name, email, phone number, or location.
 - The app only measures network performance (download speed, upload speed, and ping latency) directly from your device during the test.
No data is linked to your identity.

## 2. How We Use Information
 - The results of the speed test (download, upload, ping) are displayed only on your device.
 - We do not use this data for tracking, analytics, or advertising purposes.

## 3. Permissions
Our app requires no sensitive permissions (such as location, contacts, or microphone).
 - Network access permission is only used to perform the speed test.

## 4. Third-Party Services
XSpeed does not integrate with third-party SDKs or analytics tools that collect personal data.
If we ever use third-party services in the future, we will update this Privacy Policy accordingly.

## 5. Data Security
Since we do not collect or transmit personal data, no personal information is stored on our servers.

## 6. Children’s Privacy
Our app is safe for all users. We do not knowingly collect data from children under 13 (or under the age required by local law).

## 7. Changes to This Policy
We may update this Privacy Policy from time to time. Any updates will be posted within the app and/or on this page with a new “Last Updated” date.

8. Contact Us
If you have any questions about this Privacy Policy, please contact us at:
  - Email: atifbosan63@gmail.com


  # Privacy Policy

**Effective Date:** 2025-08-31  
**Last Updated:** 2026-04-16

At **XSpeed – Internet Speed Test**, your privacy is important to us. This Privacy Policy explains how we handle information when you use our mobile application ("App") on iOS and Android.

---

## 1. Information We Collect

XSpeed is a network diagnostic tool. We are committed to collecting the minimum information necessary to provide our features.

### 1.1 Data Stored Locally on Your Device
The following data is stored **only on your device** and is never transmitted to our servers:
- Speed test results (download speed, upload speed, ping, jitter, packet loss)
- Test history and timestamps
- Scheduled test preferences and alert thresholds
- App settings and preferences

You can clear this data at any time by clearing the app's data or uninstalling the App.

### 1.2 Data We Do NOT Collect
- We do **not** collect your name, email address, phone number, or any account information.
- We do **not** collect precise GPS location.
- We do **not** use advertising SDKs or analytics SDKs in the current version.
- No data from your device is transmitted to or stored on our servers.

---

## 2. How the App Works

To measure your internet performance, the App sends and receives network packets to/from publicly available third-party speed-test servers. This is the same technique used by all speed-test apps. These servers receive only standard network traffic — no personal information is sent.

Features that make external connections:
- **Speed Test** – connects to speed-test servers to measure download/upload speed, ping, jitter, and packet loss
- **Game Ping Test** – sends small ping packets to popular game server regions to measure latency
- **Stability Monitor** – periodically pings external servers to measure network consistency
- **VPN Speed Test** – compares speed with and without an active VPN by running the standard speed test twice

---

## 3. Permissions

The App requests only the permissions required for its features:

| Permission | Purpose |
|---|---|
| **Network / Internet Access** | Required to perform speed tests and ping measurements |
| **Notifications** *(optional)* | Used to deliver speed-drop alerts from scheduled auto-tests. You can deny or revoke this at any time in your device settings. |
| **Background App Refresh** *(optional)* | Used only if you enable Auto-Test scheduling. Allows the App to run a speed test at your chosen interval while in the background. |

No other permissions (camera, microphone, contacts, precise location, etc.) are requested or used.

---

## 4. Third-Party Services

The App uses the following third-party libraries. None of them collect personal data in the current version of XSpeed:

| Library | Purpose | Data Collected |
|---|---|---|
| Speed-test servers (via `flutter_speed_test_plus`) | Measure download/upload speed | Network packets only — no personal data |
| `dart_ping` / `dio` | Measure latency and run HTTP-based tests | Network packets only — no personal data |
| `flutter_local_notifications` | Deliver local speed-alert notifications | Stays on device — not transmitted |
| `workmanager` | Schedule background speed tests | Stays on device — not transmitted |
| `connectivity_plus` | Detect network type (Wi-Fi / cellular) | Stays on device — not transmitted |
| `in_app_review` | Prompt you to rate the App | Handled entirely by Apple App Store / Google Play |
| `share_plus` | Share speed results via the system share sheet | Handled entirely by your device's OS |

> **Advertising:** The current version of XSpeed contains **no ads and no ad SDKs**. If advertising is introduced in a future version, this policy will be updated before release and you will be notified via an updated "Last Updated" date.

---

## 5. Local Data Storage & Retention

All test history and preferences are stored locally on your device using standard platform storage (iOS: NSUserDefaults / Android: SharedPreferences). This data:
- Never leaves your device
- Can be deleted by clearing the App's data or uninstalling the App
- Is not backed up to our servers (it may be included in your device's own iCloud/Google backup if you have that enabled)

---

## 6. Children's Privacy

XSpeed does not target children. The App does not knowingly collect any personal information from anyone, including children under 13 (or under the age required by applicable local law). Since no personal data is collected, there is no risk of inadvertent collection from minors.

---

## 7. Data Security

Because XSpeed does not transmit or store personal data on any server, there is no server-side data at risk. All locally stored data (test history, preferences) is protected by your device's built-in security (PIN, Face ID, etc.).

---

## 8. Your Rights

Since we do not collect or hold any personal data, there is nothing for us to access, correct, or delete on our end. To remove all locally stored data, simply clear the App's storage in your device settings or uninstall the App.

If you are a resident of the EEA, UK, California (CCPA), or another region with data privacy laws, you are welcome to contact us and we will respond within the legally required timeframe.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the **"Last Updated"** date at the top of this page. We encourage you to review this page periodically. Continued use of the App after changes constitutes your acceptance of the updated policy.

---

## 10. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

- **Email:** atifbosan63@gmail.com
- **App Store:** [XSpeed on the App Store](https://apps.apple.com/us/app/xspeed-internet-speed-test/id6762279106)
- **Play Store:** [XSpeed on Google Play](https://play.google.com/store/apps/details?id=com.terabittech.xspeed)

