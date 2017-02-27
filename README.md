# Install my VIM settings from Vundle (Vim Package Manager)

    $ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    $ git clone https://github.com/starrlingo/starrlingo.vim ~/.vim/bundle/starrlingo.vim
    $ ln -s ~/.vim/bundle/starrlingo.vim/vimrc ~/.vimrc
    $ sudo yum -y install ctags (or apt-get)
    $ vim
    :BundleInstall
