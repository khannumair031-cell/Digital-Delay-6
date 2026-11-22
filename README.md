# DD6-NUMAIR-2026

Test-ready Android Studio project for the DD-6 phone app.

## Current stage
This stage wraps the existing Web Audio prototype in a native Android WebView shell and adds:
- Welcome screen
- Four main controls: EVO LEVEL, FEED BACK, DELAY TIME, MODE
- Import audio
- Playback
- Recording
- Live microphone routing
- Tap tempo
- WAV export
- Footswitch bypass
- Dark metallic/carbon-fibre pedal styling
- GitHub Actions debug APK build

## Important test status
The project has been assembled as source code, but an Android emulator/device build was NOT executed in this ChatGPT environment. Therefore this package is explicitly **test-ready**, not claimed as device-tested.

## Presets
The exact three Naat Sharif preset values from the earlier brief were not present in the recovered project file. They are intentionally NOT invented here. Add the exact prior values before treating the preset feature as complete.

## Build
Push this folder to GitHub, open Actions, and run **Build DD-6 APK**. The generated debug APK is uploaded as an artifact.

Package: com.numair.digitaldelay
