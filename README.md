# Auren

**Made to disappear.**

*A native Windows video player powered by libmpv.*

Auren is a lightweight, native video player for Windows built around a simple idea:
when you're watching a video, the player should get out of the way.

It bundles its own playback engine, requires no external codec packs, and focuses on
fast interaction, modern video playback, HDR, subtitles, and a minimal interface
designed around the video itself.

> **Auren is currently in alpha.**
> It is under active development and has not yet been broadly tested across different
> Windows systems and hardware.

## Downloads

The latest public builds of Auren are available from the **Releases** section of this repository.

Auren includes a built-in updater. Once installed, future releases can be detected
and installed directly from the application.

## What is this repository?

This is Auren's **public release feed**.

It contains only built distribution artifacts:

- Windows installers
- Velopack update packages
- release metadata required by Auren's built-in updater

The Auren application itself is developed in a separate source repository.

Keeping the release feed separate allows Auren's updater to access releases
anonymously while the source repository remains private during early development.

The source code is intended to become public as the project matures.

## About Auren

Auren uses **libmpv** as its playback engine, with FFmpeg providing broad media
format support underneath it.

libmpv is Auren's engine. **Auren is not a skin on top of mpv.**

The Windows application, interface, playback experience, settings, system integration,
and update behavior are built specifically for Auren.

---

**Made to disappear.**
