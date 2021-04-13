# Ruby

Powerhell bindings creating link to Visual Studio used: PS> ./ruby.h

***Build tools***
 sudo apt install build-essentials 
 sudo apt install gnulib

***Configuration***
sudo m4 ./aclocal.m4
sudo libtoolize
sudo autoconf
sudo ./configure
sudo make
sudo make check
***if the screen freezes on fcntl use ctrl+c to ignore the*** check
sudo make -pw install
