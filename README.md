# Terminal Setup

## Install Dracula

`git clone https://github.com/dracula/terminal-app.git`

## Install Oh My ZSH

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

## Install "FiraCode Nerd Font"

[Download](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/FiraCode.zip)

## Install Powerlevel10k

`git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`

Change the theme in `~/.zshrc`:

`ZSH_THEME="powerlevel10k/powerlevel10k"`
