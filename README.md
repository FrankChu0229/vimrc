 Please backup your configuration before run bellow command 
 --------

1, Get the configuration:

    git clone https://github.com/rmrf/vimbackup.git  ~/.vim
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

2, Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

3, run vim, then install related bundles

    :BundleInstall

done!
