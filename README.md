# Lumae tap

A Homebrew tap for [Lumae](https://github.com/matlegault/lumae-releases), a macOS
screen recorder and editor for software demos.

```sh
brew install --cask matlegault/lumae/lumae
```

Lumae updates itself through Sparkle, so the cask is marked `auto_updates true`:
`brew upgrade` leaves an installed copy alone and the app offers new versions on
its own. Pass `--greedy` if you would rather Homebrew drive the update.

`Casks/lumae.rb` is generated from the Lumae source repo on every release. Edits
here are overwritten.
