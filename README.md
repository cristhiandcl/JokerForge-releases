# JokerForge releases

Public installers, release notes and video guides for JokerForge. This repository hosts downloads; application source development is maintained separately.

## Current tester release

[JokerForge 0.19.0-beta.21](https://github.com/cristhiandcl/JokerForge-releases/releases/tag/v0.19.0-beta.21) provides matching Mac Apple silicon and Windows x64/ARM64 builds. About JokerForge now offers bundled terminal command setup with explicit optional user PATH configuration. Plain session list shows readable titles, status, harnesses and full IDs; JSON/JSONL stays unchanged. Offline CLI help, static shell completion, quickstart and prior session/crew/MCP/Claude history fixes remain.

- [Mac Apple silicon installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.21/JokerForge-0.19.0-beta.21-arm64.dmg): macOS 26 or later; Developer ID signed, Apple notarized and stapled.
- [Windows x64 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.21/JokerForge-0.19.0-beta.21-x64-Setup.exe).
- [Windows ARM64 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.21/JokerForge-0.19.0-beta.21-arm64-Setup.exe).

Windows installers are unsigned manual prerelease builds. Signing and automatic updates remain deferred. Install over the existing app and reopen the same workspace without uninstalling or resetting credentials. No Intel Mac or native Linux desktop installer is included.

To use jokerforge by name, open About JokerForge > Terminal command, select Make jokerforge available in new terminals and click Install terminal command. The option starts unchecked and preserves existing commands and PATH/profile content. Reopen your terminal; on Windows, close all Windows Terminal/PowerShell windows first or sign out/in if its environment is cached. Run jokerforge version, jokerforge session list or jokerforge quickstart. Completion remains opt-in.

Working Mac updaters can offer this release through Check for Updates. If an older build already reports a disabled updater because its installed signature was invalidated, replace the app once from the DMG without deleting app data. A release feed cannot repair an already disabled updater remotely.

The owner reports all 25 installed Windows x64 CLI checks pass on the available Administrator-account machine. Separate owner PATH/history observations and installed Mac beta.21 acceptance remain pending. Standard-user and physical Windows ARM64 device acceptance are unverified. The CLI can use an existing server without a GUI window; independent headless service/SDK distribution remains separate. See the release notes for validation and limits.

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
