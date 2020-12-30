# Rule 34 App — Android

This project generates an Android APK of the [Rule 34 App](https://redirect.r34.app/github) thanks to the TWA technology.

## Warning

This is just an alternative to the PWA and **should NOT be used**, as there is no way to auto update.

The recommended way to install the [Rule 34 App](https://redirect.r34.app/github) is as a PWA through your browser.

Learn more about [installing the Rule 34 App](https://www.notion.so/alejandroakbal/App-Installation-5b1be2062ffe48bda39ac1236421fc84).

## Download

Download the [latest .APK](src/app-release-signed.apk).

## Development

### Requirements

- JDK8
- Android Studio CLI
- Bubblewrap CLI

### Usage

First you will need to paste the secret `android.keystore` to the `src` directory.

```sh
cd src

# Install dependencies
npm install

# Init
bubblewrap init --manifest https://r34.app/_nuxt/manifest.<UNKNOWN>.json

# Update
bubblewrap update

# Build
bubblewrap build --skipPwaValidation
```
