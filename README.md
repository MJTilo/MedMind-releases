# MedMind for Android

[Download the latest APK](https://github.com/MJTilo/MedMind-releases/releases/latest)

Open the APK on Android and follow the installation prompt. Future updates are available in **Settings → App updates**.

## Current release: v1.0.46

[Download MedMind v1.0.46](https://github.com/MJTilo/MedMind-releases/releases/download/v1.0.46/MedMind-v1.0.46.apk)

- Email verification for patient and caregiver signup, with a 60-second resend wait and a way back to edit the address.
- Forgot password on the mobile sign-in screen.
- Recover the same archived profile with the existing password, or reset the password first.
- Includes earlier fixes through v1.0.45.

457 automated tests passed with one intentional skip. Live email and account tests passed.

## Dose confirmations

The dose confirmation button turns gray and becomes disabled 61 minutes after the scheduled time. The dose remains marked as missed in the caregiver adherence summary unless a taken confirmation was recorded within the allowed window.
