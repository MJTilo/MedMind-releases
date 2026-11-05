# MedMind for Android

[Download the latest APK](https://github.com/MJTilo/MedMind-releases/releases/latest)

Open the APK on Android and follow the installation prompt. Future updates are available in **Settings → App updates**.

## Current release: v1.0.44

[Download MedMind v1.0.44](https://github.com/MJTilo/MedMind-releases/releases/download/v1.0.44/MedMind-v1.0.44.apk)

- Improved Senior Citizen and PWD ID recognition for varied local-government layouts.
- Handles older laminated cards, attached portraits, handwritten numbers and labels below their values.
- Corrects false rejection of warnings that report no signs of tampering.
- Keeps matching-side, birthday and conflicting-identity safeguards.
- Includes the previously published fixes through v1.0.43.

440 automated tests passed with one intentional skip. Sixteen live photo scans passed, including six exact name-and-number checks. Both supplied fronts correctly requested the reverse for the missing birthday.

[Source and test report](https://github.com/Shonome/CapstoneMedmind/blob/main/docs/LOCAL_ID_RELIABILITY_20261105.md).

## Dose confirmations

The dose confirmation button turns gray and becomes disabled 61 minutes after the scheduled time. The dose remains marked as missed in the caregiver adherence summary unless a taken confirmation was recorded within the allowed window.
