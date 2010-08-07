# Vimmpc

Vimmpc provides functionality for manipulating [mpd](http://www.musicpd.org/)
from within the (vim)(http://www.vim.org/) editor.

## Dependencies

The following dependencies are required to use vimmpc:

* Vim 7.0+ (http://www.vim.org/)
* Python 2.4+ (http://www.python.org/)
* mpdclient2.py (http://svn.navi.cx/misc/trunk/python/bemused/mpdclient2.py)

## Installation

    $ tar xzf vimmpc-(revision).tar.gz
    $ cd ~/.vim/plugin
    $ ln -s /path/to/vimmpc/vimmpc.vim
    $ ln -s /path/to/vimmpc/vimmpc.py

And finally:

    $ vim -c 'MPC'

To complete the installation and launch Vim with MPC loaded.

NOTE: Vim can be loaded as normal and vimmpc activated by use of :MPC

## Screenshots

Here is a screenshot of vimmpc in action:

![interface](http://github.com/gaving/vimmpc/raw/master/site/1.png)

## Development

The development version can be viewed on [github](http://github.com/gaving/vimmpc/)

Please note that development is currently stalled just now due to an expired
interest on my part. Anyone wishing to maintain it please feel free.
