# tduyng’s Homebrew Tap

Homebrew tap for shipping my CLI tools.

## Install

```bash
brew tap tduyng/tap
```

## Install Packages

```bash
# formula
brew install tduyng/tap/<name>

# cask
brew install --cask tduyng/tap/<name>
```

## Packages

### Formulae

- `codeme` — Private CLI to track coding activity, used for `codeme.nvim`

## Update / Uninstall

```bash
brew update
brew upgrade

brew uninstall <formula>
brew uninstall --cask <cask>

# casks only: remove user data
brew uninstall --cask --zap tduyng/tap/<name>
```

## Notes

- Run `brew info tduyng/tap/<name>` for per-tool caveats (permissions, setup steps, etc.).
