# Octo Browser Homebrew tap

Homebrew cask for [Octo Browser](https://octobrowser.net/), for Apple Silicon and Intel Macs.

```sh
brew tap AuthFailed/octobrowser
brew trust --tap AuthFailed/octobrowser
brew install --cask octo-browser
```

The cask always downloads the latest installer from `binaries.octobrowser.org`. Octo Browser updates itself, so `brew upgrade` skips it unless you pass `--greedy`.

Remove the app together with its profiles and settings:

```sh
brew uninstall --zap --cask octo-browser
```
