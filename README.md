
SRC's
=====
. http://www.unlogic.co.uk/posts/vim-python-ide.html
. https://github.com/gmarik/vundle

INSTALL
=======

1. git clone https://github.com/bl4ckb1rd/dotvim.git ~/.vim
2. cd ~/.vim/
3. git submodule init && git submodule update
4. ln -s ~/.vim/dotvimrc ~/.vimrc
5. mkdir -p ~/tmp/vim/{undo,backup,swap}
6. vim then :BundleInstall

IMPORTANT
=========

For plugin jedi-vim you need install jedi with `pip install jedi`
For plugin pyflakes you need install jedi with `pip install pyflakes`
