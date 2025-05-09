# About

A Homebrew package manager tap for various Casks.

The Casks have the following properties:

## would be rejected from main homebrew-cask repository

e.g.

- unnotarized
- unsigned

Signing requires someone to be in the Apple Developer Program, which at present is 99 USD per member per year, this financial and labour overhead, explains why apps are not always signed, especially with smaller developers, or those not focusing on Apple development (providing for other OSs).

## other

Other apps may be added for expediency, but it may be best to endeavour to add it to the official repository if possible.

## responsibility of use

The main [homebrew-cask](https://github.com/Homebrew/homebrew-cask) will not allow unsigned Casks on Apple Silicon M series according to their [acceptable casks policy](https://docs.brew.sh/Acceptable-Casks).

This tap, is meant to store software, where there is a degree of trust, but it has not been signed.  That being said YOU take full responsibility, for using any software in this tap.

# Tap

Think of a "tap" like a package repository.

## Add


```bash
brew tap paradigmzero/unnotarized-cask-tap
```

## List and confirm

```bash
brew tap
```

# Remove

```bash
brew untap paradigmzero/unnotarized-cask-tap
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

# Contributing

Contributions are welcome. A comment above the Cask .rb file explaining why it is not being added to the main homebrew-cask repository is required.