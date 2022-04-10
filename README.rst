TextEdit
========
A small module for to display the letters at the sequence.

New Releases
-------------
There are just two new fonction : defileInput ans defileInputSound. 

Installation
------------
For windows, you must install the folder TextEdit in C:\Users\your_account\AppData\Local\python\python-version\Lib\  
For Linux, you must install the folder TextEdit in /usr/local/lib/python/dist-packages/  
So, you import TextEdit for Linux with 
.. code-block:: bash
        pip3 TextEdit  
And, for Windows you import with 
.. code-block:: bash
        py -m pip install TextEdit

Importation and use
===================
Once you've installed, you can really quickly verified that it works with just this:
.. code-block:: python
        >>> import TextEdit
        >>> TextEdit.defile ("Hello world")

The TextEdit module contain for the moment 4 fonction : defile ; defileInput ; defileSound ; defileInputSound.
It does nor requires argument.
You can put as many arguments as you want.

Copyright
-----------
This software is Copyright © 2022 Corentin Perdry <corentin.perdry@gmail.com>

See the bundled LICENSE file for more information.
