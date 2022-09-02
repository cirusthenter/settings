# General Setting fow New Mac

- Ver. 1.0 Sep 7, 2020
- Ver. 1.1 Aug 10, 2021
- Ver. 1.2 Jul 25, 2022

## Install

### VSCode

https://code.visualstudio.com

### iTerm2

https://iterm2.com

### Google Chrome

https://www.google.com/chrome/

### Logi Options+

https://www.logitech.com/en-us/software/logi-options-plus.html

### Google Japanese Input

https://www.google.co.jp/ime/

### Slack

https://slack.com/intl/en-us/downloads/mac

## iTerm2

### Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### Oh-my-zsh

```
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

### powerlevel 10k

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc
source ~/.zshrc
p10k configure
```

### Visual Studio Code

```
mv ~/Downloads/Visual\ Studio\ Code.app /Applications
```

### iTerm2 Preferences

#### Profiles -> Colors...

- Color Presets: Solarized Dark
- Foreground: #ffffff
- Background: #252525
- Bold: #ffffff
- Selection: #c1ddff

#### Profiles -> Session

- ☑Status bar enabled

![](https://i.ibb.co/NykKs02/status-Bar.png)

#### Profiles -> Text

- Font: size 15

#### Appearance -> Dimming

- Dim inactive split panes: off

### OpenInTerminal

```
brew install openinterminal --cask
```

#### Setting

- Open the OpenInTerminal app. Go to System Preferences -> Extensions -> Full Disk Access, check the permission button as below.

<img width="780" alt="image" src="https://user-images.githubusercontent.com/47409332/180756830-617c7758-3dbe-4497-b500-e46508e8ff0c.png">

### Vim

#### Iceberg Color Scheme

```
mkdir -p ~/.vim/colors
cd ~/.vim/colors && curl -O https://raw.githubusercontent.com/cocopon/iceberg.vim/master/colors/iceberg.vim
```

#### `~/.vimrc`

```
set tabstop=4
set shiftwidth=4
set expandtab
:syntax on
colorscheme iceberg
set cursorline
```

### GitHub

```
git config --global user.name cirusthenter
git config --global user.email cirusthenter@gmail.com
git config --global core.editor vim
git config --global merge.tool vimdiff
```

## Other Settings

### Google Japanese Input

<img width="637" alt="image" src="https://user-images.githubusercontent.com/47409332/180756676-d1b3fa7d-9dd1-47e2-a4ba-7207b5f28157.png">

### Visual Studio Code

#### Launching fron the Command Line

- Move `Visual Studio Code.app` to `/Applications`.
- Launch VS Code.
- Open the Command Palette (Cmd+Shift+P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.

#### Settings Sync

- Open the Command Palette (Cmd+Shift+P) and type 'Settings Sync: Turn on...' to find the `Settings Sync: Turn on...` command.
- Select `Sign in & Turn on` with GitHub Account.

#### Extensions

- Python
- C/C++
- Remote - SSH

#### Font

Set `Editor: Font Family` to `MesloLGS NF`

### Finder

#### New Finder Windows Show

Finder -> Preferences -> New Finder windows show: iCloud Drive

### Internet Accounts

Activate all internet accounts manually.
