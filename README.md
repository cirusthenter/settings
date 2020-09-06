# General Setting fow New Mac
Ver. 1.0 Sep 7, 2020

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
p10k configure
```
### iTerm2 Preferences
#### Profiles -> Colros...
- Color Presets: Solarized Dark
- background: #252525
#### Profiles -> Session
- ☑Status bar enabled
![](https://i.ibb.co/NykKs02/status-Bar.png)