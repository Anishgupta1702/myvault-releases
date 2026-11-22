# MyVault — releases

Download repository for **MyVault**, a personal vault for cards, documents,
passwords, vehicles, insurance and purchases, encrypted on the device.

This repository holds **release binaries only**. There is no source here.

## Install

Download the `.apk` from the [latest release](../../releases/latest) and open
it on the phone. Android will ask once for permission to install apps from
this source.

Already running MyVault? You do not need this page — the app checks here
itself and can download and install an update without leaving the app
(**Settings → Updates**).

## Why this repository is public

The app fetches its update feed with no credentials, and GitHub requires a
token to read release assets on a private repository. Nothing sensitive is
published here: the APK contains no vault data, and the vault's encryption key
never leaves the device it was created on.
