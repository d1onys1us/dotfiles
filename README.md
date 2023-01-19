# Setup mac

## General settings

- general -> dark mode
- trackpad -> tap to click, increase tracking speed, turn off force click
- edit the menu bar
  - show battery percentage in the menu bar
  - hide spotlight search
- turn off hot corners
- system preferences -> view -> in alphabetical order
- edit widgets, remove all except screen usage and calendar
- bluetooth > show in menu bar

## Finder preferences

- general -> change default finder window
- sidebar
  - turn off recents
  - turn off recent tags
  - turn off icloud drive
  - turn on home folder
- advanced
  - show all filename extensions
- view
  - show path bar
- change all to show items as list

## Dock and menu bar preferences

- remove unnecessary apps including downloads, but leave system preferences
- enable automatically hide and show dock
- disable "show recent applications in Dock"
- battery -> show percentage
- now playing -> don't show in menu bar

## Keyboard shortcuts

- remove "omw" from text
- shortcuts > launchpad & dock > toggle "dock hiding on/off" in shortcuts -> launchpad & dock

## Apps
### Core
- Chat: Discord
- Browser: Brave
- Editors: vscode and vscodium (for hotkey switching between these), one is for notes one is for code
- Input format: osprette mx keyboard + vim keybindings (qwerty pleb but looking at hands down layout)
- Terminal: wezterm + zellij
- navigation: raycast
- music: spotify

### Other
- Docker desktop (official)

## Configure Brave

- Set the search engine to Google
- Customize new tab page
- Turn off "offer to save passwords" and "auto sign in"
- Import bookmarks

## Setup VS code

- user settings: turn off enable persistent sessions integrated terminal
- user settings: set fish path in integrated.profiles.osx and select as default profile
- user settings: hide minimap
- copy keybindings.json and settings.json
- remove keybinding for "close open window"

### Install extensions

- Peacock
- GitLens -> and configure
- Dendron
- Live Share
- Fish
  - set fish path in settings to /opt/homebrew/bin/fish
- Copilot (stable)
- Prettier
- ESLint
- New (wenfangdu.faster-new)
- Material icon theme
- Thunder Client

## Setup terminal / shell

1. Install xcode command line tools by entering `git` in the terminal, and following the prompts
2. Install caskaydiacove code font
3. [Install Homebrew](https://brew.sh/)
4. Install fish and add homebrew to path
   1. `/opt/homebrew/bin/brew install fish`
   2. `fish_add_path /opt/homebrew/bin/`
5. `brew install starship`
6. `brew install zellij`
7. `fish_add_path /Applications/Visual Studio Code.app/Contents/Resources/app/bin` (add vscode to path)
    see [[reference.shell]] for more
8. [install fisher](https://github.com/jorgebucaran/fisher)
9. [install nvm](https://github.com/jorgebucaran/nvm.fish) (TODO: use pnpm instead)
10. `npm install -g pnpm` install pnpm

## Copy over config files

1. ~/.config/zellij/config.yaml
2. ~/.config/fish/config.fish
3. vscode keybindings
4. vscode user settings

## TODO chezmoi
