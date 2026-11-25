# JokerForge releases

Public installers, release notes and video guides for JokerForge. This repository hosts downloads; application source development is maintained separately.

## Current tester release

[JokerForge 0.19.0-beta.22](https://github.com/cristhiandcl/JokerForge-releases/releases/tag/v0.19.0-beta.22) provides matching Mac Apple silicon and Windows x64/ARM64 builds. Claude login-expiry guidance now points to JokerForge Settings for the session's host, and local setup retains an explicit Sign in again action. Stored history, credential ownership and the existing CLI/session/crew/MCP fixes are preserved.

- [Mac Apple silicon installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.22/JokerForge-0.19.0-beta.22-arm64.dmg): macOS 26 or later; Developer ID signed, Apple notarized and stapled.
- [Windows x64 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.22/JokerForge-0.19.0-beta.22-x64-Setup.exe).
- [Windows ARM64 installer](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.22/JokerForge-0.19.0-beta.22-arm64-Setup.exe).
- [Windows read-only checks ZIP](https://github.com/cristhiandcl/JokerForge-releases/releases/download/v0.19.0-beta.22/JokerForge-Beta22-Windows-Checks.zip): extract all seven files and run Run-M4.4-Checks.cmd. Expected: 27 PASS, 0 FAIL. No real prompts or credential/workspace/PATH changes.

Mac users can use Check for Updates. Windows installers remain unsigned manual prerelease builds; signing and automatic updates are deferred. Quit the current app, install over it and reopen the existing workspace without uninstalling or resetting credentials. No Intel Mac or native Linux desktop installer is included. A previously disabled Mac updater may require a one-time DMG app replacement without deleting app data.

For an expired Claude login, use Settings > Harnesses for the same host used by the chat, then its subscription sign-in flow and Open local setup for the managed local host. Sign in or Sign in again opens the temporary terminal/console and browser. Return to the same chat afterward. A subscription login does not require a vault/password reset.

About JokerForge > Terminal command retains explicit optional user PATH setup. Existing commands and profile/PATH content are preserved. Use jokerforge version, jokerforge session list or jokerforge quickstart after enabling it and reopening the terminal. JSON/JSONL, offline nested help and opt-in static completion remain supported.

Full regression, engine E2E, signed Mac native/package/trust and both Windows package/renderer checks passed. Physical beta.22 owner acceptance follows installation; standard-user and physical Windows ARM64 acceptance remain unverified. See the release notes and manifest for scope and exact source/download identities.

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
