# Datpaq Homebrew Tap

Official Homebrew tap for the **Datpaq CLI** and related command-line tools.

This repository is automatically maintained by **GoReleaser** and contains the Homebrew formula used to install the Datpaq CLI on macOS and Linux.

## Installation

First, add the Datpaq tap:

```bash
brew tap datpaq/homebrew-tap
```

Then install the Datpaq CLI:

```bash
brew install datpaq
```

Verify the installation:

```bash
datpaq --version
```

## Upgrading

To upgrade to the latest release:

```bash
brew update
brew upgrade datpaq
```

## Uninstall

To remove the Datpaq CLI:

```bash
brew uninstall datpaq
```

To remove the Datpaq tap:

```bash
brew untap datpaq/homebrew-tap
```

## Releases

Homebrew formulas in this repository are generated automatically whenever a new version of the Datpaq CLI is released through GitHub Actions and GoReleaser.

Manual changes to generated formula files may be overwritten by future releases.

## Source

The Datpaq CLI source code is maintained in the main repository:

https://github.com/datpaq/cli

## Documentation

Developer documentation and installation guides are available in the main Datpaq CLI repository.

## License

Refer to the license included in the Datpaq CLI repository.
