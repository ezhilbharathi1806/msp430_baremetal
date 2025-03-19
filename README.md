# msp430_baremetal
msp430-gcc-opensource toolchain installation steps in Ubuntu linux

1.) Download link: https://www.ti.com/tool/MSP430-GCC-OPENSOURCE
2.) click "Mitto Systems GCC 64-bit Linux - toolchain only  — 62584 K" to download.
3.) file named "msp430-gcc-9.3.1.11_linux64.tar.bz2"gets downloaded
4.) unpack using linux command "$ tar -xvf msp430-gcc-9.3.1.11_linux64.tar.bz2"
5.) after unpacking navigate to bin file using command "$ cd Downloads/msp430-gcc-9.3.1.11_linux64/bin/" 
6.)add bin path to linux environment variables using command "$ export PATH="$PATH:$(pwd)" and "$ echo $PATH" to display all env variable paths.
