
SRC's
=====
.- http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/


INSTALL
=======

1. git clone https://github.com/bl4ckb1rd/dotvim.git .vim
2. cd ~/.vim/
3. git submodule update --init
4. ln -s ~/.vim/dotvimrc ~/.vimrc
5. ln -s ~/.vim/vim-pathogen/autoload/ ~/.vim/autoload
6. mkdir -p ~/tmp/vim/{undo,backup,swap}

UPDATE SUBMODULES
=================

1. cd ~/.vim/
2. git submodule foreach git pull origin master
