# Sam Brannon's Dotfiles

These aren't even really dotfiles yet. Just an overview of what I've done during a couple recent fresh OSX installations.

## Apps to Download
The following is a list of common apps to install on a fresh OSX install

**App Store Apps**
  - Irvue
  - Amphetamine
  - Annotate
  - Sunrise Calendar
  - Magnet
  - Deliveries
  - 1Password
  - Alfred
  - Slack
  - Gradient
  - Frank DeLoupe
  - Daisy Disk
  - Icon Slate
  - Site Sucker
  - Wunderlist
  - Pixelmator
  - Transmit

**homebrew-cask apps**
  - scroll-reverser
  - private-internet-access
  - mamp
  - virtualhostx
  - iterm2 (new beta)
  - google-chrome
  - atom
  - istat-menus
  - dropbox (maybe do selective sync initially to get 1pass and Atom app preferences synced first?)
  - spotify

**Non-homebrew-cask && non-app-store apps**
  - Airmail Beta ([download](https://rink.hockeyapp.net/apps/84be85c3331ee1d222fd7f0b59e41b04))
    - Import account settings from Dropbox

## Setting up iTerm

  1. Set up oh-my-zsh
    - `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
    - Follow [installation instructions](https://github.com/oskarkrawczyk/honukai-iterm-zsh#installation) for *Honukai*
    - Install `zsh-autosuggestions` using [these instructions](https://github.com/zsh-users/zsh-autosuggestions#oh-my-zsh)
    - update plugins list to `git zsh-autosuggestions`
  2. Toggle hotkey in “keys > hotkey”
  3. Install homebrew
    `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  4. `brew install rbenv`
  5. `brew install node`
  6. `brew install wget`
  7. toggle hidden files in finder
      `defaults write com.apple.finder AppleShowAllFiles NO`
      `killall Finder`
  8. Set up global Git config `git config --global --edit`
  9. Add ssh key to Github

## Setting up Atom
  1. Open for first time
  2. Install package `sync-settings`
  3. Add gistID and token from 1Pass
  4. Run `sync-settings:restore` command
  5. Restart Atom to get access to plugin settings
