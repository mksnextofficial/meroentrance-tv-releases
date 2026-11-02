# MeroEntrance official app downloads

[Choose your app and see setup instructions](https://meroentrance.com/apps/)

- [Android TV and Fire TV — latest signed APK](https://github.com/mksnextofficial/meroentrance-tv-releases/releases/latest/download/MeroEntrance-TV.apk)
- [Android phone and tablet — 1.0.18 (64)](https://github.com/mksnextofficial/meroentrance-tv-releases/releases/download/android-v1.0.18-64/MeroEntrance-Android.apk)
- [iPhone and iPad — App Store](https://apps.apple.com/np/app/meroentrance-learn-practice/id6822372282)

## TV updates

The GitHub TV build supports compatible Android TV and Android-based Fire OS devices on Android 8.0 or newer. It does not support Samsung Tizen, LG webOS or Vega OS.

Install once and sign in. While open on Home, the app checks for new releases (at most once every six hours) and downloads a newer APK. It verifies the package, version, SHA-256 checksum and signing identity before offering installation. Choose **Install update**, allow **MeroEntrance TV** under **Install unknown apps** when requested, then confirm the system installation. If asked which app should open the APK, choose **Package installer**. Login and app data stay in place; do not uninstall first.

Future approved, signed TV releases are published here with an increasing version code and `update.json`. The TV release remains GitHub's **Latest** release; phone releases are published with `--latest=false`. The phone APK is not part of the TV update channel. Google Play installations should continue using Google Play because store signing can differ.

This repository distributes signed APKs and release metadata only. Source code and signing keys are not included. Downloading the app does not grant paid course access; access follows your account or school plan.
