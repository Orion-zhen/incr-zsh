# incr-zsh

## Declaration

This repo is forked from the [orignal website](http://mimosa-pudica.net/zsh-incremental.html)

## Modification

Avoide directly put completion onto command line when there is only one choice by commenting code that handles only one completion

## Installation

Make sure you have [oh-my-zsh]() installed

1. `curl -fsSL https://raw.githubusercontent.com/Orion-zhen/incr-zsh/main/incr.zsh -o ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/incr/incr.zsh`
2. in `$HOME/.zshrc`, add this line: `source $ZSH_CUSTOM/plugins/incr/incr.zsh`
3. `source $HOME/.zshrc`
