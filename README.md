# realtek8821ce
ubuntu5.0.0-36 realtek8821ce 无线驱动

1. Unpack zip archive.
2. Change the Makefile. Line "export TopDIR ?= ..." to export "TopDIR ?= PATH TO EXTRACTED DIRECTORY".
3. make
4. sudo make install
5. sudo modprobe -a 8821ce

帮助我的Url:
https://bbs.deepin.org/forum.php?mod=viewthread&tid=152205
https://www.cnblogs.com/imagineAct/p/11286072.html
