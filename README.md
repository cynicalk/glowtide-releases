# Glowtide for Windows

A music companion for Windows: an album-coloured glow around the edge of your screen and
word-by-word lyrics over your desktop. It follows Spotify, YouTube Music or any app that shows
up in Windows' media controls.

This repository holds Glowtide's installers and release notes; installed copies check its
latest release for updates. The source code is at
[cynicalk/glowtide](https://github.com/cynicalk/glowtide) (MIT licence).

## Install

1. Open the [latest release](../../releases/latest) and download `Glowtide-<version>-setup.exe`.
2. Run it. It installs for your Windows account only, with no administrator prompt.
3. The installer isn't code-signed, so Windows SmartScreen may say "Windows protected your
   PC". Choose **More info → Run anyway**.

Glowtide lives in the tray, by the clock, and updates itself: when a new version has
downloaded, it shows **Restart to update**. Settings → App has the update and start-up
switches. Your settings are in `%APPDATA%\Glowtide`, and uninstalling is from Settings → Apps.

Releases before 1.0.11 keep their original installer file names.
