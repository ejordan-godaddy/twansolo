# MacOS Developer Setup

## System Settings
---

These are critical to life bliss

- set turn display off and amphetemine
- turn off battery/power saving
- turn on night shift

## Install brew
---

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew analytics off
```

## Install a terminal

iterm2 is popular but garbage here some better alternatives

```zsh
brew install kitty
brew install alacritty **
```
** is what I use currently

## Install a browser

Keeping in linux theme, remove Safari from the dock and never use it 

```
brew install brave-browser**
brew install librewolf
```

** is what I currently use

### Browser Extensions

List of personal use extentions 

- Example

## Chat Apps
```bash
brew install signal # secure chat app 
brew install discord # for personal if you need it 
brew install slack # company issued **
```

** is what I currently use

## Command Line Tools
```zsh
xcode-select --install
```

## Content Creation
```zsh
brew install obs
brew install gimp
brew install blender
```
Research a good tool to make .gif files for git repositories

## Improving the Launcher
Spotlight is garbage.  Alfred is less garbage but not Batman.  Rayman is actually pretty good
```
brew install raycast
```

## Window Management

Window management on MacOS is abysmal and we need to improve it.  A good combination is Yabai for WM and SKHD for key command control over the OS.

```bash
brew install yabai **
brew install skhd **
```

** is what I currently use

## CLI Utilities

These are a few things I can't live without

```bash
brew install tree
brew install fd
brew install fjira
```
