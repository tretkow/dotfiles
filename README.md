
## clone
    git clone https://github.com/tretkow/dotfiles .dotfiles
    ln -s .dotfiles/tmux.conf ~/.tmux.conf
    echo "alias tmux='tmux -2'" >> ~/.bashrc
    echo "alias cgrep='grep -rIi --color=auto --include \*.c --include \*.cpp --include \*.h --include \*.hpp'" >> ~/.bashrc

