# MedMind for Android

[Download the latest APK](https://github.com/MJTilo/MedMind-releases/releases/latest)

Open the APK on Android and follow the installation prompt. Future updates are available in **Settings → App updates**.

## Current release: v1.0.43

[Download MedMind v1.0.43](https://github.com/MJTilo/MedMind-releases/releases/download/v1.0.43/MedMind-v1.0.43.apk)

- Provider-enforced password requirements with a matching five-item checklist in mobile signup and admin password changes.
- Spaces and Unicode letters no longer count as the required symbol.
- Server-side locking for concurrent admin password changes.
- Stricter ID-response validation and recovery from stalled notification requests.
- Includes earlier ID, language, schedule, validation and request-recovery fixes.

334 root tests and 104 backend tests passed; one root test was intentionally skipped. Eight mobile browser layouts passed.

The deployed provider has a Unicode minimum-length edge documented in the source password-policy report.

Built from [Shonome/CapstoneMedmind v1.0.43](https://github.com/Shonome/CapstoneMedmind/releases/tag/v1.0.43).

## Dose confirmations

The dose confirmation button turns gray and becomes disabled 61 minutes after the scheduled time. The dose remains marked as missed in the caregiver adherence summary unless a taken confirmation was recorded within the allowed window.
