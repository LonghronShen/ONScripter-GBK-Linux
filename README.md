Introduction
====================
ONScripter-GBK for Linux is a project for porting the ONScripter to most popular Linux distros.
Currently this project is developped on the Debian distros, especially for the Loongson-2F platform.

This repository is forked from *https://github.com/shouhuanxiaoji/ONScripter-GBK-Linux*

Quick start
====================
The following steps are based on the Debian 8 running on a Loongson-2F system.
Firstly we should install some dependencies.

* libsdl 1.2-dev
* libsdl-image1.2
* libsdl-image1.2-dev
* libsdl-mixer1.2
* libsdl-mixer1.2-dev
* libsdl-net1.2
* libsdl-net1.2-dev
* libsdl-ttf2.0-0
* libsdl-ttf2.0-dev
* libsmpeg-dev
* libsmpeg0
* libavifile-0.7-dev
* lua5.1-dev
* libfontconfig1-dev
* libbz2-dev

Then execute: 

    make -f Makefile.Linux

Then you can compile the whole project and generate a <code>onscript</code> executable file.

Usage
====================
Copy the compiled executable file to the game directory, then a TTF font file and rename it to <code>default.ttf</code>

Then execute: <code>./onscripter --window</code>

Enjoy!
