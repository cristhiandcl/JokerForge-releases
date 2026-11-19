# JokerForge releases

Public installers, release notes and video guides for JokerForge. This repository hosts downloads; application source development is maintained separately.

## Current tester release

[JokerForge 0.19.0-beta.15 for macOS](https://github.com/cristhiandcl/JokerForge-releases/releases/tag/v0.19.0-beta.15) adds shared MCP/skill, connection/custom-agent, reviewed plugin and crew CLI management through the existing engine. Existing GUI sessions, projects, crews, reporting, Help and CLI session execution remain available.

- [macOS Apple silicon beta.15 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.15/JokerForge-0.19.0-beta.15-arm64.dmg): macOS 26 or later; Developer ID signed, Apple notarized and stapled. A working Mac updater can install beta.15 from About or Settings, Desktop, Updates.
- [Windows x64 beta.14 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.14/JokerForge-0.19.0-beta.14-x64-Setup.exe).
- [Windows ARM64 beta.14 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.14/JokerForge-0.19.0-beta.14-arm64-Setup.exe).

Windows beta.15 candidates are being checked privately and are not part of this Mac release. Public Windows beta.14 installers remain unsigned manual tester builds. Windows signing/automatic updates, standard-user and native ARM64 device acceptance remain pending. A native Linux desktop installer is not available yet.

Retain your existing workspace when replacing the app. If a Mac beta.10 installation already says updates are not configured because generated cache files invalidated its signature, use the current DMG once: quit JokerForge and replace the app in Applications without deleting app data. A release feed cannot repair that already disabled updater.

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
