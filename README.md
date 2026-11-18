# JokerForge releases

Public installers, release notes and video guides for JokerForge. This repository hosts downloads; application source development is maintained separately.

## Current tester releases

[macOS 0.19.0-beta.12](https://github.com/cristhiandcl/JokerForge-releases/releases/tag/v0.19.0-beta.12) fixes a Python cache/signature issue that could disable the updater. It retains existing harnesses, model connections, shared tools, crew recovery, reporting and Help, plus initial CLI discovery and host selection.

- [macOS Apple silicon installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.12/JokerForge-0.19.0-beta.12-arm64.dmg): macOS 26 or later; Developer ID signed, Apple notarized and stapled.
- [Windows x64 beta.10 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.10/JokerForge-0.19.0-beta.10-x64-Setup.exe).
- [Windows ARM64 beta.10 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.10/JokerForge-0.19.0-beta.10-arm64-Setup.exe).

Mac and public Windows downloads currently have different versions. Windows beta.12 remains private pending native checks. Windows downloads are unsigned manual prerelease testers; signing and automatic updates remain deferred. Retain your existing workspace when replacing the app. A native Linux desktop installer is not available yet.

If an installed Mac beta.10 already says updates are not configured, use the beta.12 DMG once: quit JokerForge and replace the app in Applications without deleting app data. An update feed cannot repair that already disabled updater. Working Mac updaters can install beta.12 normally from either update screen.

## Guides and demos

Open **Help → JokerForge Help** in the app for 26 bundled topics that work offline, including dedicated Claude Code, Codex and Antigravity guides. Choose a walkthrough inside Help and press Play to stream it. Movies require Internet and are not bundled in installers; downloads remain available.

- [Start on macOS](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.9/JokerForge-macOS-start.mp4).
- [Start on Windows](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.9/JokerForge-Windows-start.mp4).
- [Daily workflow](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.9/JokerForge-daily-workflow.mp4).
- [All 17 videos with English captions, transcripts and chapters](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.9/JokerForge-video-guides-beta.9.zip).

Fourteen focused clips cover sessions, regular projects, agent crews, harness settings, model connections and agents, shared MCPs, skills, plugins, browser previews, Git, usage/context, automation/Inbox, notifications and updates/diagnostics. Find each clip and its related reading guide in Help.

The videos demonstrate real controls and local tool operations with scripted model replies and controlled setup/update states. Windows setup footage is a renderer demonstration, not native Windows acceptance. Account sign-in and provider terms must be completed locally by each user.

## Updates and support

On the Mac, use **About → Check for updates** or **Settings → Desktop → Updates**, review what's new, download the update and choose **Restart now** or **Later**. Restart now restarts JokerForge, not the computer. Automatic update discovery also checks at app startup and periodically. Windows testers currently replace the app with the matching manual installer.

Select a real recent issue in About to preview its safe category and delivery state. Local history remains separate from the upload queue. Diagnostic exports can be reviewed and saved locally. Private coded error reporting is optional and starts disabled; it is separate from sharing a diagnostic export. Do not post credentials, private conversations or diagnostic bundles in this public repository.

JokerForge builds on Omnigent and other open-source components. Release packages include applicable notices and corresponding source materials. See each release's SHA256SUMS and manifest to identify its exact downloads.
