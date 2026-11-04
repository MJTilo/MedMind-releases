# MedMind for Android

[Download the latest APK](https://github.com/MJTilo/MedMind-releases/releases/latest)

Open the APK on Android and follow the installation prompt. Future updates are available in **Settings → App updates**.

## Current release: v1.0.42

[Download MedMind v1.0.42](https://github.com/MJTilo/MedMind-releases/releases/download/v1.0.42/MedMind-v1.0.42.apk)

- Admin password requirements and background request alerts.
- Pag-IBIG, PhilHealth and SSS IDs, plus reverse-side camera/upload prompts when required details are missing.
- Scanned-name autofill, surname/given-name order matching and 09 phone-number validation.
- Vertical signup password requirements and valid date-range calendar limits.
- Additional guards for stale/duplicate ID scans, image size, admin password confirmation and blocked browser alerts.
- Includes the earlier PWD/Senior ID, Filipino UI, dose-recording, schedule, request-deadline and database-setup fixes already in main.

Affected areas passed targeted automated checks. A full-system regression run was not performed for this release.

Built from [Shonome/CapstoneMedmind v1.0.42](https://github.com/Shonome/CapstoneMedmind/releases/tag/v1.0.42).

## Dose confirmations

The dose confirmation button turns gray and becomes disabled 61 minutes after the scheduled time. The dose remains marked as missed in the caregiver adherence summary unless a taken confirmation was recorded within the allowed window.
