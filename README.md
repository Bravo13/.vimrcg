Before using this .vimrcg follow next simple steps

  1. create .vimrc that will include vimrcg and setup plugin dir for perl-support
  
    source $HOME/.vimrcg/.vimrc_g

    let g:Perl_PluginDir = $HOME.'/.vim/bundle/vim-plugins/'

  2. install Vundle to .vim 
  
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle 

  3. install ctags 
  
    http://prdownloads.sourceforge.net/ctags/ctags-5.8.tar.gz

Now you can run vim and start BundleInstall to get cool themes and plugins :)
