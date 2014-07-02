yasnippets-yard
===============

A collection of snippets for YARD documentation tags for Ruby.

---

Synopsis
--------

This set of snippets implements nearly all non-deprecated tags for YARD
documentation.  Out of the box, it works with both ruby-mode and
enh-ruby-mode.  Note that all tags will only expand when the first
non-whitespace character is a `#`.  That is, the line must be commented
out for the snippet to expand.

Installation
------------

### From github

Clone the repository into a directory of your choosing:

    git clone https://github.com/lgustafson/yasnippets-yard ~/.emacs.d/mysnippets

In .emacs, add the snippet directory to your yasnippets:

    (add-to-list 'yas-snippet-dirs "~/.emacs.d/mysnippets")

Author
------
Leif Gustafson <leif@leifgustafson.com>

License
-------

[MIT License][mit]

Copyright 2014 Leif Gustafson
