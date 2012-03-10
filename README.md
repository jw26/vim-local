my vim local stuff
==================

because i keep loosing it

    cd ~
    git clone git://github.com/jw26/vim-local.git
    ln -s vim-local/.vimrc .vimrc
    cd vim-local
    git submodule init
    git submodule update
    cd bundle/command-t
    rvm use system
    bundle install
    rake make

then https://gist.github.com/1634235 and install it
