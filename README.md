# JokerForge releases

Public installers, release notes and video guides for JokerForge. This repository hosts downloads; application source development is maintained separately.

## Current tester release

[JokerForge 0.19.0-beta.18](https://github.com/cristhiandcl/JokerForge-releases/releases/tag/v0.19.0-beta.18) provides matching macOS Apple silicon and Windows x64/ARM64 builds. It repairs paired advisor-tool history during Claude resume, preserves saved chats, and includes the worker recovery, MCP lifecycle and Windows CLI input fixes.

- [macOS Apple silicon installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.18/JokerForge-0.19.0-beta.18-arm64.dmg): macOS 26 or later; Developer ID signed, Apple notarized and stapled.
- [Windows x64 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.18/JokerForge-0.19.0-beta.18-x64-Setup.exe).
- [Windows ARM64 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.18/JokerForge-0.19.0-beta.18-arm64-Setup.exe).

Windows installers are unsigned manual prerelease builds. Signing and automatic updates remain deferred. The owner reports all 16 installed Windows x64 checks pass under the available Administrator account. Standard-user and native Windows ARM64 device acceptance remain unverified. Retain the existing workspace and credential store when replacing the app. No native Linux desktop or Intel Mac installer is included.

Working Mac updaters can offer this release through Check for Updates. If an older Mac build already says updates are not configured because its installed signature was invalidated, use the DMG once: quit JokerForge and replace the app in Applications without deleting app data. An update feed cannot repair that already disabled updater remotely.

After updating an affected Claude chat, reopen that existing chat and send one harmless new continuation. The original Mac chat's live-provider confirmation is still pending; the reproduced failure and preserved-history E2E pass. See the release notes for verification and limits.

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
