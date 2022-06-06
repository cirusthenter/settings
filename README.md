# General Setting fow New Mac

- Ver. 1.0 Sep 7, 2020
- Ver. 1.1 Aug 10, 2021

## Install

### VSCode

https://code.visualstudio.com

### iTerm2

https://iterm2.com

### XCode

https://apps.apple.com/jp/app/xcode/id497799835?l=en&mt=12

### Google Chrome

https://www.google.com/chrome/

### Logi Options

https://www.logicool.co.jp/ja-jp/product/options

### Google Japanese Input

https://www.google.co.jp/ime/

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

- Open the OpenInTerminal app. Go to System Preferences -> Extensions -> Finder Extensions, check the permission button as below.

![](https://user-images.githubusercontent.com/11001224/78590336-448f4180-7874-11ea-827c-ad3a7bffca5e.png)

## Other Settings

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

### Google Japanese Input

![image](https://user-images.githubusercontent.com/47409332/128803761-1e265607-d9b5-47e9-9c8f-3964dca34176.png)

![image](https://user-images.githubusercontent.com/47409332/128803889-0df52ced-bed0-4ec8-912d-4fba48eecff9.png)
