# Shoal

Shoal is a Mac app for running coding agents side by side, each in its own git worktree.

This repo holds the released builds only. The source is private.

## Install

```sh
brew trust austinejose1516/tap        # once: Homebrew asks you to trust a tap before using it
brew install --cask austinejose1516/tap/shoal
```

This also puts the `shoal` command on your PATH. Or download the `.dmg` from
[Releases](https://github.com/austinejose1516/shoal-releases/releases) and drag Shoal to Applications.

Shoal is not notarized by Apple yet. The first time you open it, macOS may block it:
open **System Settings → Privacy & Security** and click **Open Anyway**.

Needs a Mac with Apple silicon and macOS 14 or later. Builds are betas for now.
