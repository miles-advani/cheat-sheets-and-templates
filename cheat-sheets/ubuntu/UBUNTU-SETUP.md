# Setup For Ubuntu

This is a collection of commands and tools that I use to setup my Ubuntu machine for development.

## First things first

### Set a faster initial key repeat

Ubuntu does not use the same command as MacOS for setting key repeat rates. You can adjust these settings through the GNOME Tweak Tool or using the following commands:

```sh
gsettings set org.gnome.desktop.peripherals.keyboard delay 200
gsettings set org.gnome.desktop.peripherals.keyboard repeat-interval 15
```

### Install command line tools

Ubuntu comes with most of the essential command line tools pre-installed. For development tools, you can install the build-essential package:

```sh
sudo apt update
sudo apt install build-essential
```

## Terminal

Ubuntu comes with GNOME Terminal by default. For a customizable terminal, you might consider Tilix:

```sh
sudo apt install tilix
```

## Cloudflare Warp

Cloudflare Warp is not directly available as an apt package, but you can install it using the following steps:

```sh
sudo apt install cloudflare-warp
```

Note: If the above command doesn't work, you might need to follow Cloudflare's official documentation for alternative installation methods.

## Visual Studio Code

```sh
sudo snap install --classic code
```

## Git

```sh
sudo apt install git
```

## Ripgrep

```sh
sudo apt install ripgrep
```

## Git GUI

While GitUp is not available for Linux, GitKraken is a popular alternative:

```sh
sudo snap install gitkraken --classic
```

## GitHub CLI

```sh
sudo apt install gh
```

### Setup

```sh
gh auth login
gh auth status
```

## Node.js

Using NVM to manage Node versions:

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
nvm install 18
nvm use 18
```

### json language server

```sh
npm install -g vscode-langservers-extracted
```

### tsserver

```sh
npm install -g typescript typescript-language-server
```

## Direnv

```sh
sudo apt install direnv
```

## Utility tools

### System Monitor

For system monitoring, you can use Stacer:

```sh
sudo apt install stacer
```

## exa / modern ls

```sh
sudo apt install exa
```

## NerdFonts

For cool looking fonts and symbols in the terminal:

```sh
sudo apt install fonts-hack-ttf
```

## MongoDB

```sh
sudo apt install -y mongodb
```

Start MongoDB:

```sh
sudo systemctl start mongodb
```

To start the mongo shell run:

```sh
mongo
```

Stop MongoDB:

```sh
sudo systemctl stop mongodb
```

## MongoDB Compass

To install MongoDB Compass on Ubuntu, you can use the following commands:

```sh
wget https://downloads.mongodb.com/compass/mongodb-compass_1.31.0_amd64.deb
sudo dpkg -i mongodb-compass_1.31.0_amd64.deb
```

Replace `1.31.0` with the latest version number if necessary.

## Postman

```sh
sudo snap install postman
```

## Random Tools

### Obsidian

```sh
sudo snap install obsidian
```

### Albert

Raycast is not available for Linux, but Albert is a good alternative:

```sh
sudo apt install albert
```

### GIMP

```sh
sudo apt install gimp
```
