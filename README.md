### Building Transmission from Git (first time)

    $ git clone https://github.com/transmission/transmission Transmission
    $ cd Transmission
    $ git submodule update --init
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ sudo make install

### Building Transmission from Git (updating)

    $ cd Transmission/build
    $ make clean
    $ git pull --rebase --prune
    $ git submodule update
    $ cmake ..
    $ make
    $ sudo make install

sudo service transmission-daemon stop; make clean;cmake ..;make;sudo make install;sudo service transmission-daemon start; 


sudo apt install -y joe neofetch openssh-server cifs-utils nginx php-fpm curl libssl-dev libevent-dev libcurl4-openssl-dev cmake build-essential zlib1g-dev automake autotools-dev libtool-bin

