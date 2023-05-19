This is documentation is for Mac OS users only!

Homebrew Documentation

nstallation

Instructions for a supported install of Homebrew are on the homepage.

This script installs Homebrew to its default, supported, best prefix (/usr/local for macOS Intel, /opt/homebrew for Apple Silicon and /home/linuxbrew/.linuxbrew for Linux) so that you don’t need sudo after Homebrew’s initial installation when you brew install. This prefix is required for most bottles (binary packages) to be used. It is a careful script; it can be run even if you have stuff installed in the preferred prefix already. It tells you exactly what it will do before it does it too. You have to confirm everything it will do before it starts.
macOS Requirements

    A 64-bit Intel CPU or Apple Silicon CPU 1
    macOS Big Sur (11) (or higher) 2
    Command Line Tools (CLT) for Xcode (from xcode-select --install or https://developer.apple.com/download/all/) or Xcode 3
    The Bourne-again shell for installation (i.e. bash) 4

Again!! 
To work in the terminal you need to install `xcode` first!! 
```
# Use this code
xcode-select --install
```

then, to work with brew you need to install it 
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Then, you can install, update or upgrade software

```bash
# first 
brew update
# follow by 
brew upgrade
# if you want to install software just do this
brew install wget
```
Now type `wget` and see the message
or try this
```bash
wget https://github.com/ricardoi/cheatsheets/blob/master/commandsUNIX.pdf
```
