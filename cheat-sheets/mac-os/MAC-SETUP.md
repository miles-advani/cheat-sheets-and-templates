# Setup For Mac

This is a collection of commands and tools that I use to setup my macbook for development.

## First things first

### Set a faster initial key repeat

Before doing anything please do yourself a favour and speed up the initial key repeat rate:

```sh
defaults write -g InitialKeyRepeat -int 10 # normal minimum is 15 (225 ms)
defaults write -g KeyRepeat -int 1 # normal minimum is 2 (30 ms)
```

> [!IMPORTANT]
> A complete restart of the macbook is required after this to apply the changes!

### Install command line tools

```sh
xcode-select --install
```

## Homebrew

Install our favourite package manager <3

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Warp Terminal

```sh
brew install --cask warp
```

## vsCode

```sh
brew install --cask visual-studio-code
```

## Git

```sh
brew install git
```

## Ripgrep

```sh
brew install ripgrep
```

### Gitup

```sh
brew install --cask gitup
```

## Github cli

```sh
brew install gh
```

### Setup

```sh
gh auth login
gh auth status
```

## Node

```sh
brew install nvm
nvm -v
```

```sh
nvm install 18.17
node -v
```

### json language server

```sh
npm i -g vscode-langservers-extracted
```

### tsserver

```sh
npm install -g typescript typescript-language-server
```

## Direnv

```sh
brew install direnv
```

## Utility tools

### Fanny

```sh
brew install --cask fanny
```

## exa / modern ls

```sh
brew install exa
```

## NerdFonts

cool looking fonts and symbols in terminal

```sh
brew tap homebrew/cask-fonts
brew install font-hack-nerd-font
```

## MongoDB

```sh
brew tap mongodb/brew
```

```sh
brew update
```

```sh
brew install mongodb-community@7.0
```

```sh
brew install --cask mongodb-compass
```

Start MongoDB

```sh
brew services start mongodb-community@7.0
```

To start the mongo shell run:

```sh
mongosh
```

Stop MongoDB

```sh
brew services stop mongodb-community@7.0
```

## Postman

```sh
brew install --cask postman
```

## Obsiadian

```sh
brew install --cask obsidian
```

## Raycast

```sh
brew install --cask raycast
```

## Gimp

```sh
brew install gimp
```


