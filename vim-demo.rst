Web Development with Vim
========================

Johannes Raggam
thetetet@gmail.conf
https://github.com/thet/dotfiles-vim 


- Show survey:

    https://docs.google.com/forms/d/e/1FAIpQLSdnrZgyyNd9oNtax-AJKKFpG-bQ8SgpG2Sk9xlOoTcP1vYOEA/viewform?c=0&w=1

    https://docs.google.com/forms/d/1OwT8wstFQ1Hqmp3wC0wTXbIKar-H8VIvYDbRX9IWMR8/edit?c=0&w=1#responses


Naked Vim is hardly usable
--------------------------

- Load vim with different configuration ``vim -u dot-vimrc``
- Show inserting, moving with cursors, etc.
- Use ``set nocompatible`` and do ``:so %``. Now it's much better.
- Show "deleting in register" problem and "delete in blackhole register" solution.


Show fully configured vim
-------------------------

- My vim config: https://github.com/thet/dotfiles-vim 
- Good examples: https://github.com/garbas/vim-config-garbas

- Show ``.vimrc``
- Show ``config.vim``
- Show ``keymap.vim``


Show plugins and functionality
------------------------------

- Show ``plugins.vim`` and there individual plugins.

- Open plugin manager ``gx``: https://github.com/junegunn/vim-plug


File Navigation
~~~~~~~~~~~~~~~

- Ctrl-P:
    - ``,/``, search for ``autoformatdefaults``.
    - ``,,`` currently open files.
- File Beagle: ``-``, a netrw alternative.
- Buffer Gator: ``,m``
- Open Buffer in NERDTree: ``,b``
- MiniMap: ``mm``.


Linting and Formating
~~~~~~~~~~~~~~~~~~~~~

- Ctrl-P, open ``autoformatsamplejs``
- Show errors and explanation.
- ``,f``
- See result.

- ``-`` choose the python sample, format it with ``,f``, ``,i``, ``,s``

- Use external formating tools:
    - Choose ``test.json`` from root and do: ``:%!python -m json.tool``
    - Choose ``test.rst`` from root and do: ``:%!column -t``


Git
~~~

- Show gut gutter on changed files.
- Jump from Hunk to Hunk ``]c``.
- Undo a specific Hunk ``,hu``

- Show ``:Gitv`` commit browser.
- Show ``GDiff`` diff viewer.

- Show Tagbar ``tt`` on Python file.


More
----

- Show ``:Goyo`` with Limelight
- ``colorscheme github``, ``colorscheme molokai``


Show jedi-vim
-------------

- pythonpaths part to build file with project paths:
  https://github.com/bluedynamics/buildout-base/blob/master/etc/dev.cfg

- python-config.vim which parses this file.

- ask me if you're interested in this and need some help.


Tnx A Lot!
----------------





