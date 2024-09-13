# WR841N-V8-23.05
Custom minimal image of the latest OpenWRT 23.05


git clone the 23.05 version of OpenWRT by doing a quick 

git clone https://github.com/openwrt/openwrt -b 23.05

drop the .config file in openwrt 23.05 after updating the feeds 

then do "make defconfig" and you can procees with either "make menuconfig"
either if you wish to change somethign or you can just type "make" to proceed with the compilation procedure 

the final file will be outputed in bin/target/ath79/
