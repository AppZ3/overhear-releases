# Overhear

Live English captions over anything your phone is playing, or anything it can hear.

**[Install on Android](https://appz3.github.io/overhear-releases/)**

Or download the APK directly from [the latest release](https://github.com/AppZ3/overhear-releases/releases/latest).

---

## What it does

- **This phone's audio** — captions whatever is playing. Works with Bluetooth headphones.
- **The room** — uses the microphone, for a TV or a cinema.

Captions float above other apps and taps pass straight through them. Size, width, colour, position
and timing are all adjustable.

Everything runs on the device. No audio leaves your phone, and there is no account.

## Installing

Android will warn you about installing an app from outside the Play Store. That is expected for a
sideloaded app. Allow it for your browser or file manager when prompted.

The speech model (about 42 MB) downloads the first time you press Start.

Requires Android 10 or newer. Most phones need the `arm64-v8a` build.

## Updates

The app checks this repository for updates in the background.

- **Settings and speech-model fixes apply on their own**, with nothing to confirm.
- **New versions download automatically**, and Android asks you to confirm before installing.
  It cannot install silently, and no app that is not part of the system can.

You can turn automatic downloads off in the app under Updates.

## Known limitations

- **Netflix, Disney+ and similar block audio capture.** Android gives apps no way around it. Use
  *The room* mode with the microphone instead.
- Captions appear about a second after someone speaks. Most of that is the speech model deciding
  what it heard, not the app.
- English only.

## Privacy

Audio is processed on the device and is never uploaded. The app contacts the network for exactly
two things: downloading the speech model on first run, and checking this repository for updates.
It sends no identifiers and collects no analytics.
