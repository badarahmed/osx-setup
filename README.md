# osx-setup

## Install Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
brew update
```

### Install Homebrew Packages
```
brew install zsh
brew install zsh-syntax-highlighting
brew install caskroom/cask/brew-cask
```

### Install Cask Packages
```
brew cask install iterm2
brew cask install google-chrome
brew cask install caffeine
brew cask install flux
brew cask install macpass
brew cask install spectacle
```

## Install nvm
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | sh
```

## Install Node.js v4 LTS
```
nvm install v4.2.2
```

## Install pure zsh prompt
```
npm install --global pure-prompt
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
