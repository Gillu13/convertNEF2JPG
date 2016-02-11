convertNEF2JPG
==============

Taking pictures in "raw" mode is often the best option for those who do not want
to loose information. However, this format is not supported by most picture 
viewers.

I wrote this basic shell script in order to massively convert to JPG the NEF 
photos I upload from my Nikon camera to my computer so I can take a glance at 
them before I edit them on softwares like `Darktable
<http://www.darktable.org/>`_.

Please, feel free to use and improve it.

Dependencies
------------

This code heavily depends on the `ImageMagick
<http://www.imagemagick.org/script/index.php>`_ suite.


Installation and Usage
----------------------

Except the dependencies, there is nothing to install.

It might be however more convenient to make the script available so you can use 
it directly by calling the script name from wherever. To make it possible, 
first make the script executable::

$ chmod u+x convertNEF2JPG

Then save the file to your `$HOME/bin` directory (if it does not exist, create 
it). If you are running a recent Linux distribution (e.g. Ubuntu 12.04 or 
later), you are done! Otherwise you may need to add `$HOME/bin` to your PATH by 
running::

$ export set PATH=$PATH:~/bin

To use the script open a terminal, place yourself to the directory where you 
uploaded your NEF photos and run::

$ convertNEF2JPG

and follow the instructions.
