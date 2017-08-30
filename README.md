# dotfiles


## fonts
In editors, current favorite is [Fira Code](https://github.com/tonsky/FiraCode) which supports some awesome font ligatures.

## Terminal 
[This](https://gist.github.com/kevin-smets/8568070) is pretty close to how I've set up my current bash set up, except I use Fira Code here as well. I also tend to crank up the brightness of the colors (especially green, #228b22, and yellow, #ffc72c) Additionally, I needed to manually set the "bright" colors in iTerm2, or else they just show the super saturated colors.

## Shell
I use ZSH backed by oh-my-zsh. Important things to know is that I've enabled the vi-mode plugin. This works well when you map caps lock to escape (this should be done through MacOS system preferences)

## vim
1. `brew install vim` to get 8.0 (macOS default is 7.3).
2. Download [spf13](https://github.com/spf13/spf13-vim)'s implementation of Vim's dotfiles.
3. Add the local one from this repo (just changes the airline theme)
