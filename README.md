# FileSteward AI releases

Signed Android APK downloads for FileSteward AI, an Android file manager with an AI organizer.

This repository is the public download origin for the FileSteward AI website. It contains:

- `manifest.json`: the current public release state that the website reads.
- GitHub Releases: each release carries one signed universal APK named `filesteward-ai-{version}-universal.apk` and its SHA-256 checksum.

The application source code is not published here.

## Verifying a download

Every release lists the SHA-256 of its APK. After downloading, compare it:

```
sha256sum filesteward-ai-<version>-universal.apk
```

All official APKs are signed with the same certificate. Its SHA-256 fingerprint is:

```
9C:75:DA:22:57:11:8E:DE:84:01:14:78:DC:76:41:C8:63:49:8B:89:89:E5:74:C4:17:A5:6D:A4:E7:B9:45:5F
```

## Requirements

Android 13 or newer. AI features use your own AI provider key.

## Support

Open an issue in this repository.
