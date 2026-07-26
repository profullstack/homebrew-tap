# Profullstack Homebrew Tap

```sh
brew tap profullstack/tap
brew install --cask nightcell7
```

Casks here are generated from published GitHub releases by
[`nightcell7`](https://github.com/profullstack/nightcell7)'s
`tools/release/package-managers.mjs`, which reads each release's own
`SHA256SUMS.txt`. Do not hand-edit them — a manual change would be overwritten
on the next release, and could point at a checksum the release does not have.
