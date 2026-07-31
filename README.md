# JSMenzies Homebrew Tap

This is a Homebrew tap containing macOS apps and CLI tools by jsmenzies.

## Available Software

### PRHQ

PRHQ delivers real-time GitHub pull-request and CI notifications through a
native macOS menu-bar and notch experience.

```bash
brew install --cask jsmenzies/tap/prhq
```

### fresh

A CLI tool for interactively managing the status of multiple Git repositories.

```bash
brew install jsmenzies/tap/fresh
```

### autocommit

An AI-powered git commit message generator.

```bash
brew install jsmenzies/tap/autocommit
```

## Installation

### Install a specific tool

```bash
brew install jsmenzies/tap/<tool-name>
```

### Or tap once and install multiple

```bash
brew tap jsmenzies/tap
brew trust jsmenzies/tap
brew install prhq
brew install fresh
brew install autocommit
```

## Updating

```bash
brew update
brew upgrade --cask prhq
brew upgrade fresh
brew upgrade autocommit
```

## Uninstalling PRHQ

Sign out in PRHQ first so the app can clear its Keychain credentials, then quit
the app and run:

```bash
brew uninstall --cask prhq
```

To also remove PRHQ caches, preferences, saved state, and WebKit data:

```bash
brew uninstall --cask --zap prhq
```

Homebrew cannot remove PRHQ Keychain items. If PRHQ was removed before signing
out, reinstall it and sign out before uninstalling again.
