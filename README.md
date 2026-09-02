# Ab Tap

Homebrew formulae and casks maintained by [ab](https://github.com/ab).

## Install

```bash
brew install ab/tap/<formula>
brew install --cask ab/tap/<cask>
```

Or tap the repository first:

```bash
brew tap ab/tap
```

In a `Brewfile`:

```ruby
tap "ab/tap"
brew "<formula>"
cask "<cask>"
```

## Available Casks

### Alacritty

Alacritty is not notarized, so macOS may block it the first time you open it
after installation or an upgrade.

Approve it in **System Settings > Privacy & Security**, or remove quarantine
from this application only:

```bash
xattr -dr com.apple.quarantine /Applications/Alacritty.app
```
