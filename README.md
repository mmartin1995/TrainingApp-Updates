# TrainingApp public updates

This repository contains only public release metadata and distributable Android APK files for the Edzésnapló app.

The application source code remains in the private `mmartin1995/TrainingApp` repository.

## Update metadata

The Android app reads:

`https://raw.githubusercontent.com/mmartin1995/TrainingApp-Updates/main/latest.json`

The metadata is published only after a signed APK has been built and verified. Do not commit signing keys, passwords, tokens, personal data, or workout data here.

## Release process

A workflow in the private source repository will publish the signed APK and update `latest.json` here after the required signing and compatibility checks pass.
