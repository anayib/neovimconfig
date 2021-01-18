
## Getting started
FOllow this instructions
https://www.linode.com/docs/guides/how-to-install-neovim-and-plugins-with-vim-plug/


## Not required
the following lines are NOT require at the end of init.vim
call plug#begin()
Plug 'roxma/nvim-completion-manager'
Plug 'SirVer/ultisnips'
Plug 'honza/vim-snippets'
call plug#end()


## Install the plugins
Then run

nvim
:PlugInstall
:UpdateRemotePlugins
:q!
:q!

## Install nerdfont to get files icons from terminal
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts && curl -fLo "Droid Sans Mono for Powerline Nerd Font Complete.otf" https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/DroidSansMono/complete/Droid%20Sans%20Mono%20Nerd%20Font%20Complete.otf

source: https://github.com/ryanoasis/nerd-fonts#linux
