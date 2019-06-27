# ATSAM3x8E_Linux
Arduino Due Firmware Development Env/BSP for Linux Enviroment

##### References:
http://www.atwillys.de/content/cc/using-custom-ide-and-system-library-on-arduino-due-sam3x8e/?lang=en

##### Original author: @stfwi (https://github.com/stfwi)

##### Troubleshooting:  
If the PHP script just simply prints the script on stdout instead of executing then please edit `/etc/php/5.6/cli/php.ini` and change `short_open_tag = Off` to `short_open_tag = On`

##### To Recompile libraries (libsam_sam3x8e_gcc_rel.a, libsam_sam3x8e_gcc_dbg.a etc)  
Change Directory to: `due/sam/libsam/build_gcc` and issue `make` command.
