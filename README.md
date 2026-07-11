# homebrew-xlent

Homebrew tap for [**xlent**](https://github.com/Jon-Schneider/xlent) — an
Excel-style spreadsheet for the terminal.

## Install

```sh
brew tap jon-schneider/xlent
brew install --cask xlent
```

The cask installs a signed, notarized macOS binary, so it runs without a
Gatekeeper prompt. Upgrade with `brew upgrade --cask xlent`.

## About

This repository only hosts the Homebrew cask. The cask in
[`Casks/xlent.rb`](Casks/xlent.rb) is generated and updated automatically by
[GoReleaser](https://goreleaser.com) on each xlent release — do not edit it by
hand.

The application itself lives in the main repository:
**https://github.com/Jon-Schneider/xlent**

For releases, prebuilt archives for Linux and Windows, and issues, see that
repository.
