
SRC's
=====
.- http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/


INSTALL
=======

1. git clone ... .vim
2. cd ~/.vim/
3. git submodule update --init
4. ln -s ~/.vim/dotvimrc ~/.vimrc
5. ln -s ~/.vim/vim-pathogen/autoload/ ~/.vim/autoload


UPDATE SUBMODULES
=================

1. cd ~/.vim/
2. git submodule foreach git pull origin master
