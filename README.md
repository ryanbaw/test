# test
work test

install dependencies package
sudo apt-get install libcurses5-dev
sudo apt-get install build-essential
sudo apt-get install gawk bison flex libjpeg62-dev

modify /etc/rc.local
before exit 0, add following code:
ifconfig eth0 down
ifconfig eth0 hw ether 00:15:c5:bb:e4:d2
ifconfig eth0 up

modify ~/.bashrc , add following code:
source /home/nike/amba_src/toolchain/envsetup_bashrc.sh
