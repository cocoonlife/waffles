Fork of Waffles library to include autoconf and Debian packaging.

# Building
## Prerequisites
    sudo apt-get install git build-essential automake debhelper devscripts
    git clone git@github.com:cocoonlife/waffles.git  # will need SSH keys
    cd waffles/src

## Autotools
    cd waffles/src
    aclocal -I m4
    autoconf
    automake
    ./configure && make

You can now type `make install` to put the waffles code in system directories.

## CMake

TODO

## Packaging

    cd waffles/src
    debuild -us -uc

Just say "y" to the question about the orig tarball not existing. This
will result in Debian packages getting build in ..

# Testing

    cd waffles/src
    ./test/waffles_test
