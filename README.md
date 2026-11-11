# Christmas GSD Projectivy

Standalone Android Studio project for a Christmas-themed Projectivy Launcher icon pack for Sony BRAVIA / Android TV.

## Project contents
- Android Studio / Gradle source project.
- Original 50 Projectivy target-app mappings retained from the V8 source baseline in `app/src/main/assets/appfilter.xml`.
- Independent application ID: `uk.christmasgsd.projectivy`.
- GitHub Actions workflow to build a debug APK on pushes to `main` or manually.
- 4K UHD wallpaper in `wallpaper/`.

## Important artwork status
This is the clean, independent Android project scaffold and mapping baseline. The drawable resources currently inherited from the V8 source are **not yet the finished traditional Christmas icon artwork**. They are retained as temporary baseline assets so that the app structure and mappings are preserved while the 50 final Christmas designs are prepared and integrated. Do not treat this scaffold as the finished Christmas icon pack.

## Build
Open this folder in Android Studio, allow Gradle sync, then run `./gradlew :app:assembleDebug`. GitHub Actions performs the same debug build and publishes the APK as a workflow artifact.

## Compatibility notes
The target-app package/activity mappings in `app/src/main/assets/appfilter.xml` are carried over unchanged from the audited V8 baseline. The new icon-pack app itself has a separate application ID so it can coexist with the original project.
