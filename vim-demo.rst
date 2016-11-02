Web Development with Vim
========================

- Johannes Raggam
- thetetet@gmail.com
- https://github.com/thet
- https://twitter.com/thetetet
- Vim Config: https://github.com/thet/dotfiles-vim


Survey via Twitter "What is your favorite code IDE/editor? Let me know"
-----------------------------------------------------------------------

.. note::
        - Questions: https://goo.gl/JU8qhk
        - Results: https://goo.gl/1pkBYq


Naked Vim is hardly usable
--------------------------

.. note::
    - Load vim with different configuration ``vim -u dot-vimrc``
    - Show inserting, moving with cursors, etc.
    - Use ``set nocompatible`` and do ``:so %``. Now it's much better.
    - Show "deleting in register" problem and "delete in blackhole register" solution.


Show fully configured vim
-------------------------

.. note::
    - My vim config: https://github.com/thet/dotfiles-vim
    - Good examples: https://github.com/garbas/vim-config-garbas

    - Show ``.vimrc``
    - Show ``config.vim``
    - Show ``keymap.vim``


Show plugins and functionality
------------------------------

.. note::

    - Show ``plugins.vim`` and there individual plugins.

    - Open plugin manager ``gx``: https://github.com/junegunn/vim-plug


File Navigation
~~~~~~~~~~~~~~~

.. note::

    - Ctrl-P:
        - ``,/``, search for ``autoformatdefaults``.
        - ``,,`` currently open files.
    - File Beagle: ``-``, a netrw alternative.
    - Buffer Gator: ``,m``
    - Open Buffer in NERDTree: ``,b``
    - MiniMap: ``mm``.


Linting and Formating
~~~~~~~~~~~~~~~~~~~~~

.. note::

    - Ctrl-P, open ``autoformatsamplejs``
    - Show errors and explanation.
    - ``,f``
    - See result.

    - ``-`` choose the python sample, format it with ``,f``, ``,i``, ``,s``

.. note::

    - External formating tools

        - Choose ``test.json`` from root and do: ``:%!python -m json.tool``
        - Choose ``test.rst`` from root and do: ``:%!column -t``


Git
~~~

.. note::
    - Show gut gutter on changed files.
    - Jump from Hunk to Hunk ``]c``.
    - Undo a specific Hunk ``,hu``

    - Show ``:Gitv`` commit browser.
    - Show ``GDiff`` diff viewer.

    - Show Tagbar ``tt`` on Python file.


More
----

.. note::
    - Show ``:Goyo`` with Limelight
    - ``colorscheme github``, ``colorscheme molokai``


Show jedi-vim
-------------

.. note::
    - pythonpaths part to build file with project paths:
      https://github.com/bluedynamics/buildout-base/blob/master/etc/dev.cfg

    - python-config.vim which parses this file.

    - ask me if you're interested in this and need some help.


Tnx A Lot!
----------





