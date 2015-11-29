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
```

## Install Homebrew Cask
```
brew install caskroom/cask/brew-cask
```

### Install Cask Packages
```
brew cask install iterm2
brew cask install google-chrome
brew cask install caffeine
brew cask install flux
brew cask install macpass
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
