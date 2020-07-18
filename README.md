# Rule 34 App - Android

This project generates an android APK using TWA thanks to [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap)

## Download

[Latest .APK](src/app-release-signed.apk)

## Development

- Install JDK8
- Install Android Studio CLI
- Install Bubblewrap CLI
- Paste the secret `android.keystore` to .src/

```sh
# Init
bubblewrap init --manifest https://r34.app/_nuxt/manifest.<UNKNOWN>.json

# Update
bubblewrap update

# Build
bubblewrap build --skipPwaValidation
```
