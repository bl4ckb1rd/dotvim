
SRC's
=====
. http://www.unlogic.co.uk/posts/vim-python-ide.html
. https://github.com/gmarik/Vundle.vim


INSTALL
=======

1. git clone https://github.com/bl4ckb1rd/dotvim.git ~/.vim
2. git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
3. ln -s ~/.vim/dotvimrc ~/.vimrc
4. mkdir -p ~/tmp/vim/{undo,backup,swap}
5. vim +PluginInstall +qall


IMPORTANT
=========

For plugin pyflakes you need install jedi with `pip install pyflakes`
