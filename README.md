# OneFit: workout and nutrition tracker for Android and iPhone

**OneFit** is one app for training and eating well: log workouts set by set, follow routines and programs, track calories, protein, fat and carbs, scan barcodes, and let the AI coach build a plan around your goal.

This repository holds the **Android releases** of OneFit (signed APK files). The app's source code is not here.

- Website and downloads: **[onefit.world](https://onefit.world)**
- Latest Android build: **[Releases → Latest](https://github.com/FijshH/onefit-releases/releases/latest)**
- iPhone: through TestFlight, from the link on [onefit.world](https://onefit.world)
- Web app: [beta-app.onefit.world](https://beta-app.onefit.world)

## What OneFit does

- **Workout log**: exercises with sets, reps, weight and rest timer; history and personal records per exercise.
- **Routines and programs**: build your own or start from ready-made ones; an AI builder makes a routine from a short description.
- **Nutrition diary**: meals with calories and macros, a food database with barcode scanning, favourites, and AI analysis of a meal from text or a photo.
- **Goals and progress**: daily calorie and macro targets, water, body weight and measurements, weekly statistics.
- **Sign in** with Google, with Apple on iPhone, or with e-mail.
- English and Russian.

OneFit is in **beta**: things change quickly, payments run in test mode, and data on the beta may be reset.

## Install on Android

1. Open the [latest release](https://github.com/FijshH/onefit-releases/releases/latest) on your phone and download the `.apk` file.
2. Open the downloaded file. Android asks once to allow installing apps from your browser or file manager: allow it.
3. Tap **Install**. Updates install the same way, over the existing app, and keep your data.

Requires Android 10 or newer. The app tells you when a newer build is available and brings you back here to download it.

## Check that a download is genuine

Every release lists the SHA-256 of its APK. All builds are signed with the same key; the certificate's SHA-256 fingerprint is:

```
43:B4:02:BD:90:0B:B2:95:EB:A1:7A:FC:BF:80:9F:D3:E0:98:63:E1:3B:D6:12:AB:06:FE:88:18:7D:23:AD:4C
```

Verify with Android's build tools: `apksigner verify --print-certs onefit-<version>.apk`. Android itself refuses to install an update that is signed with a different key.

## Help and feedback

Write to **support@onefit.world**, or open an issue in this repository for problems with installing or updating the Android app.
