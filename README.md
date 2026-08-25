# Homebrew tap — Spendif.ai

Personal finance manager with local AI categorisation.
Source code: https://github.com/drake69/spendif-ai

## Install

```bash
brew tap drake69/spendifai
brew install --cask --no-quarantine spendifai
```

`--no-quarantine` is required while the DMG ships unsigned.

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
