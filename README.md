# broccoytdlp

Search YouTube and save videos as MP4 or audio as MP3, using
[yt-dlp](https://github.com/yt-dlp/yt-dlp) and ffmpeg.

This repository only hosts releases.

## Download

- [Windows 10 or 11 (64-bit)](https://github.com/michael-aguilar/broccoytdlp/releases/latest/download/broccoytdlp-setup.exe)
- [macOS](https://github.com/michael-aguilar/broccoytdlp/releases/latest/download/broccoytdlp.dmg)

Older versions are on the [releases page](https://github.com/michael-aguilar/broccoytdlp/releases).

## Installing

The app isn't code-signed, so the system warns before the first launch.

- **Windows:** if "Windows protected your PC" appears, select **More info**,
  then **Run anyway**. The app installs for your account only; uninstall it
  from **Settings → Apps**.
- **macOS:** open the disk image and drag the app to Applications. If macOS
  blocks it, open **System Settings → Privacy & Security** and select
  **Open Anyway**.

On first launch the app downloads yt-dlp and, on Windows, ffmpeg, so it needs
an internet connection. On macOS, install ffmpeg first with
`brew install ffmpeg`.

To update, install the newer version over the old one.
