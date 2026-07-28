# Privacy Policy

Last updated: 2026-07-28

This Privacy Policy describes how **RingForge** ("the App", "we", "us") handles information when you use the mobile application (package name: `com.pegasuslw.tonecraft`).

---

## 1. What the App Does

RingForge is a local ringtone maker. It allows you to:
- select audio/video files from your device,
- preview and trim audio,
- apply effects, fade, speed, and volume adjustments,
- save trimmed audio as ringtone files,
- manage favorites and optional scheduled ringtone rotation,
- set ringtone, notification, message, or alarm tones through Android system settings.

All core processing runs on your device. The App does not require an account.

---

## 2. Information We Process

To provide core features, the App may process the following data **on your device**:
- media file metadata (such as file name, duration, format, content URI, or file path shown in the system media library),
- media files you select for preview, trimming, saving, or deletion,
- information about ringtones you save with the App (such as display name, file location, and duration), stored in the App's private storage to support save and apply features,
- app preferences (such as theme, language, favorites, and rotation settings), stored locally on your device.

If you choose to send in-app feedback, the App transmits only what you submit: your message, optional image attachments, and basic app/device diagnostic details needed to investigate the report. Feedback is sent by email only when you tap Send.

We do not operate a backend that receives your media files or personal profile.

---

## 3. Permissions

The App may request these Android permissions:

- `READ_MEDIA_AUDIO` / `READ_MEDIA_VIDEO` (Android 13+), or `READ_EXTERNAL_STORAGE` (Android 12 and below):
  Used to list and access local audio/video files you choose.

- `WRITE_SETTINGS`:
  Used only when you choose to set a sound as the default system ringtone, notification, message, or alarm tone. You can deny this permission and still preview, trim, and save files; you may need to select the saved ringtone manually in system sound settings.

- `INTERNET`:
  Used only when you voluntarily submit in-app feedback by email.

- `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_MEDIA_PLAYBACK`:
  Used for audio preview playback while the App is active.

- `RECEIVE_BOOT_COMPLETED`:
  Used to reschedule optional ringtone rotation after your device restarts.

You can deny permissions, but some features may not work properly.

---

## 4. Data Sharing and Transmission

- The App does **not** sell your data.
- The App does **not** upload your selected media files to our servers.
- The App does **not** require account registration.
- The App does **not** intentionally collect personal identifiers (such as name, phone number, or email) for backend storage.

If you send feedback, the information you include is transmitted only to process your support request. We do not use feedback content for advertising.

Important: if your Android system or device vendor services back up app data, that behavior is controlled by your device/OS settings, not by our own remote server.

---

## 5. Data Retention and Deletion

- Trimmed ringtone files are saved on your device storage (for example, under ringtone-related folders in the media library, such as `Ringtones/RingForge`).
- Saved ringtone metadata and app preferences may be kept in the App's private storage on your device.
- You can delete created files from the App (where supported) or from your system file/media manager. Uninstalling the App removes its private app data.

---

## 6. Children's Privacy

The App is not directed to children under 13, and we do not knowingly collect personal information from children.

---

## 7. Third-Party Services

The App uses open-source audio processing libraries (including FFmpegKit and TAndroidLame) to process media **locally on your device**. These libraries do not receive your media files over the network during normal App use.

If future versions integrate third-party analytics, sign-in, or other online services, this policy will be updated accordingly.

---

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. The latest version will be published in the repository or on the app listing page.

---

## 9. Contact

If you have questions about this Privacy Policy, please contact:

- Policy document: https://github.com/pegasuslw/PrivacyPolicy/blob/main/ring/PRIVACY_POLICY.md
- GitHub Issues: https://github.com/pegasuslw/PrivacyPolicy/issues
- Email: pegasus.lw@gmail.com
