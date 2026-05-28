# Android / AGP 9 compatibility (Brewlab)

Changes in `android/build.gradle` for modern Flutter (AGP 9, compileSdk 36):

- Migrated from legacy `buildscript` + `apply plugin` to `plugins { }` block
- Added `namespace` (required for AGP 8+)
- `compileSdk` 36
- `minSdk` DSL

Upstream: https://github.com/Ayush783/readsms_plugin
