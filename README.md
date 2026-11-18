# DriverAccounts Android Project — Version 8.9

Fresh Android Studio project with the approved dark navy / blue / green visual direction.

Requirements: Android Studio, JDK 17, Android SDK 35, Gradle 8.9.

## Build APK
1. Extract the ZIP.
2. Open the `DriverAccounts` folder in Android Studio and allow Gradle sync.
3. Select **Build > Build APK(s)**.
4. APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## GitHub Actions
Push this project to GitHub. `.github/workflows/android.yml` builds a debug APK and uploads it as a workflow artifact.

## Data
Records are stored on-device in SharedPreferences. This project does not cloud-sync. Back up records before uninstalling or clearing app data.

## Fields
Uber/Yango/Bolt Credit, Cash and For Us; OWN Trip; Card Collection; Company Trips; EV Charging; Car Expenses; Salik Toll; Uzair Collected.
Daily Earnings = Uber Credit + Yango Credit + Bolt Credit + Uber For Us + Yango For Us + Bolt For Us + OWN Trip. Other amounts remain separate.
