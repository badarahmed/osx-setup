# osx-setup

## Install Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install Homebrew Packages
```
brew install zsh-syntax-highlighting
brew install jq
brew install tmux
```

### Install Cask Packages
```
brew install --cask iterm2
brew install --cask caffeine
brew install --cask macpass
brew install --cask rectangle
brew install --cask visual-studio-code
```

## Install iTerm2 Theme
```
curl -O https://raw.githubusercontent.com/chriskempson/tomorrow-theme/master/iTerm2/Tomorrow%20Night%20Eighties.itermcolors
open Tomorrow%20Night%20Eighties.itermcolors

# iTerm > Preferences > Profiles > Default > Colors > Load Presets
```

## Install ohmyzsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

It will save previous `.zshrc` config to `.zshrc.pre-oh-my-zsh`. Add the pre-config to the new `.zshrc`

## Setup Git
```
git config --global user.name "Your Name"
git config --global user.email you@example.com
```

## Setup scm_breeze
```
git clone git://github.com/ndbroadbent/scm_breeze.git ~/.scm_breeze
~/.scm_breeze/install.sh
```

# Resources
- https://github.com/mathiasbynens/dotfiles
- https://github.com/robbyrussell/oh-my-zsh
- https://github.com/sindresorhus/pure
- https://github.com/chriskempson/tomorrow-theme
- https://github.com/tony/tmux-config
- http://meltuhamy.com/tech/dev/setting-up-my-dev-environment-on-a-new-mac/
