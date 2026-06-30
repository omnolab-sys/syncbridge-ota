# SyncBridge OTA channel

The app checks `latest.json` at:
  https://raw.githubusercontent.com/omnolab-sys/syncbridge-ota/main/latest.json

To publish a new version (done by Claude on request):
1. Build the new APK (versionCode bumped), e.g. SyncBridge-1.4.apk
2. Copy it here and update latest.json (versionCode, versionName, apkUrl, notes)
3. git add/commit/push to the PUBLIC repo `omnolab-sys/syncbridge-ota` (main branch)
Phones pick it up on next launch (red dot) → Settings → Update.
