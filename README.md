# MedMind for Android

[Download the latest APK](https://github.com/MJTilo/MedMind-releases/releases/latest)

Open the APK on Android and follow the installation prompt. Future updates are available in **Settings → App updates**.

## Current release: v1.0.45

[Download MedMind v1.0.45](https://github.com/MJTilo/MedMind-releases/releases/download/v1.0.45/MedMind-v1.0.45.apk)

- Education links restricted to DOH, FDA Philippines, DOST-FNRI, PSMID and WHO domains.
- 51 supported articles published, with all 53 records preserved.
- Ambroxol and Carbocisteine retained as unpublished drafts pending working approved references.
- Matching source safeguards in the app, admin API and database.
- Includes earlier fixes through v1.0.44.

441 automated tests passed with one intentional skip. All 22 published reference destinations passed availability checks.

[Source correction and validation report](https://github.com/Shonome/CapstoneMedmind/blob/main/docs/EDUCATION_SOURCE_CORRECTION_20261105.md).

## Dose confirmations

The dose confirmation button turns gray and becomes disabled 61 minutes after the scheduled time. The dose remains marked as missed in the caregiver adherence summary unless a taken confirmation was recorded within the allowed window.
