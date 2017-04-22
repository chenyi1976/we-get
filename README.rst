we-get: command-line tool for searching torrents.
#################################################

.. image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square   :target:

.. class:: no-web

    .. image:: https://raw.githubusercontent.com/wiki/levisabah/we-get/screenshots/we_get.gif
        :alt: we-get gif
        :width: 100%
        :align: center

.. class:: head

.. contents::

.. section-numbering::

Installation
============

* Option 1

.. code-block:: bash

    $ sudo python setup.py install


* Option 2

.. code-block:: bash

    $ sudo pip install git+https://github.com/levisabah/we-get


Dependencies
============

`Python <https://www.python.org/>`_ 3.5 or above


Platforms
==========

* Linux
* Mac
* Windows

Mainly tested on linux.

Basic Usage
===========

.. code-block:: bash

    $ we-get --search "Linux.iso" --target  the_pirate_bay,1337x --filter "2016"

General options
---------------

============ =============
-h --help    Help message.
-v --version Show version.
============ =============

Options
-------

===================== =====================================================
-s --search=<text>    Search for a torrent.                                
-l --list             List top torrents from modules.                      
-t --target=<target>  Select module to use or 'all'.                       
-L --links            Output results as links.                             
-J --json             Output results in JSON format.                       
-G --get-list         List targets (supported web-sites).                  
-f --filter=<str>     Match text or regular expression in the torrent name.
-n --results=<n>      Number of results to retrieve.                       
-S --sort-type=<type> Sort torrents by name/seeds (default: seeds).        
===================== =====================================================

Video options
-------------

================ ==================================================================
-q --quality=<q> Try to match quality for the torrent (720p,1080p, ...).           
-g --genre=<g>   Try to select video genre for the torrent (action, comedy, etc..).
================ ==================================================================



See also ``we-get --help``.

Supported websites
------------------

* 1337x
* thepiratebay
* eztv
* yts

and the list will grow.

Contributing
------------

Any collaboration is welcome!

* Write blog post about we-get
* Tweet (@0xlevis)
* Code

and that's it.

Licence
-------

We-get is written by Levi sabah.

`MIT <https://github.com/levisabah/we-get/blob/master/LICENSE>`_
