# Neon Galaxy Projectivy Icon Pack — revised source build

This source project contains the Neon Galaxy Cosmic Glass artwork integrated into the Projectivy/Blueprint dashboard framework.

## Icon integration
- 35 approved master PNGs replace the previous artwork for their existing mapped apps.
- The BBC / YouView icon mapping is retained, because the supplied master artwork collection did not include a BBC icon.
- The Browser artwork is included as an additional selectable icon in the Projectivy picker; no automatic package mapping is assumed for it.
- `appfilter.xml` retains all 36 app mappings. `drawable.xml` contains 37 selectable icons.
- Theme metadata is labelled Neon Galaxy, version 1.1.0 (version code 2).

## Build
Run `./gradlew :app:assembleDebug` from the project root, or use the included GitHub Actions workflow. The debug APK is intended for personal installation.

## Notes
The dashboard framework is based on Blueprint. Retain the upstream licence and attribution when redistributing modified work.
