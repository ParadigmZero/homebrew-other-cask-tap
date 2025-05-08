# About - Homebrew tap with unsigned casks

Homebrew will not allow unsigned Casks on Apple Silicon M series...

<https://docs.brew.sh/Acceptable-Casks>

This tap, is meant to store software, where there is a degree of trust, but it has not been signed. Signing requires someone to be in the Apple Developer Program, which at present is 99 USD per member per year, this financial and labour overhead, explains why apps are not always signed, especially with multiple-OS open-source organizations such as KDE .etc. That being said YOU take full responsibility, for using any software in this tap.

# Tap

Think of a "tap" like a package repository.

## Add


```bash
brew tap ParadigmZero/unsigned-cask-homebrew-tap
```

## List and confirm

```bash
brew tap
```

# Remove

```bash
brew untap ParadigmZero/local-homebrew-tap
```
## Update

```bash
brew update
```

(will update ALL taps)

# Casks

## Install a cask
Casks are like the programs within the specific tap.

```bash
brew install --cask examplecask
```

## Update

```bash
brew upgrade
```

## Uninstall

```bash
brew remove examplecask
```