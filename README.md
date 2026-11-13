# Homebrew tap for tui

```sh
brew install srt54558/tui/tui
```

`tui` opens terminal apps by their domain. This tap holds only the formula; it downloads the release files from `https://tui-get.k-plus.one`. Builds installed through Homebrew are updated with `brew upgrade`, never by tui itself.

macOS only (Apple silicon and Intel). The formula is generated for each release by the tui release tooling and pins each download by SHA-256. On Linux, use `curl -fsSL https://tui-get.k-plus.one/install.sh | sh`.
