# Homebrew tap — Spendif.ai

Personal finance manager with local AI categorisation.
Source code: https://github.com/spendifai/spendif-ai

## Install

```bash
brew tap spendifai/spendifai
brew trust --cask spendifai/spendifai/spendifai
brew install --cask spendifai
```

Homebrew 6 refuses to load casks from third-party taps until you trust them,
hence the `brew trust` line — it is unrelated to code signing. The DMG is
signed with a Developer ID certificate and notarised by Apple.

## Update

```bash
brew update
brew upgrade --cask spendifai
```

## Uninstall

```bash
brew uninstall --cask spendifai        # keeps your data
brew uninstall --zap --cask spendifai  # also deletes ~/.spendifai
```

This repository is generated: the cask is rendered and pushed by
`packaging/homebrew/update-tap.sh` in the main repository.
