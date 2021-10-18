# GV9531-linux
GV9531 linux kernel and rootfs compile environment,the directory tree bleow:
linux 4.9.56     ----->linux kernel  
rootfs           ----->rootfs  
host             ----->crosscompile toolchain 

# compile step
step1: ./build d 
generate linux kernel conifguration file;
step2: ./build r
compile linux kernel and rootfs for boot gv9531 chip;
