# Chesski downloads

Chesski turns your own chess.com games into spaced-repetition puzzles. It runs
entirely on your machine: your games are fetched from chess.com's public API
(no login), analysed with a bundled copy of Stockfish, and stored locally.

**Download the latest version from the [Releases page](https://github.com/lhlamar/chesski-releases/releases/latest).**

| Platform | File |
|---|---|
| Mac with Apple Silicon (M1 or newer) | `Chesski-<version>-mac-arm64.dmg` |
| Mac with Intel | `Chesski-<version>-mac-x64.dmg` |
| Windows | `Chesski-<version>-win-x64.exe` |
| Linux | `Chesski-<version>-linux-x64.AppImage` |

## First launch on macOS

The app is not yet notarised by Apple, so the first launch is blocked with
"Apple could not verify Chesski is free of malware". To open it once:

1. Open **System Settings → Privacy & Security**.
2. Scroll down to the message about Chesski and click **Open Anyway**.
3. Confirm. After that it opens normally.

(Or right-click the app in Applications and choose Open.)

## Getting started

1. Enter your chess.com username.
2. Click **Import from chess.com**, then select games and **Analyse selected**.
3. Open **Train**.

Chesski checks this repository for new versions on launch and lets you know
when one is available.
