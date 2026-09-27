# bugsbunny-25/homebrew-tap

Homebrew formulae for macOS (Apple silicon) and Linux (x86_64, arm64).

```bash
brew install bugsbunny-25/tap/mkv-track-editor
```

## Formulae

| Formula | Description |
|---|---|
| `mkv-track-editor` | Desktop app to reorder, rename and flag MKV tracks with profiles and Radarr/Sonarr-compatible file names. Installs MKVToolNix and MediaInfo as dependencies. |

On macOS, `mkv-track-editor` also installs `MKV Track Editor.app`; run
`brew info mkv-track-editor` to see how to add it to `/Applications`.

## How this tap is updated

Formulae and the archives on this repository's
[Releases](https://github.com/bugsbunny-25/homebrew-tap/releases) are
published by the application's CI when a `release/X.Y.Z` branch is pushed.
Don't edit `Formula/*.rb` by hand; changes are overwritten on the next
release.
