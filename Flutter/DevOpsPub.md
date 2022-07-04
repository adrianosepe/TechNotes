## How to publish

### Generating Android APK splited by architecture processor

> lutter build apk --target-platform android-arm,android-arm64,android-x64 --split-per-abi

### Generating Android APK to share with stakeholders

> flutter build apk --release

### Generating Android Bundle to publish at Google Play

> flutter build appbundle --release

## Generating iOS Archive to publish at Apple Store

> flutter build ipa --release