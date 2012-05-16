reStructuredText Practice
=========================
Examples are from http://sphinx.pocoo.org/rest.html.
.. Add footnote => [#f1]_http://sphinx.pocoo.org/rest.html

* This is a bulleted list.

1. This is a numbered list.

#. This is also a numbered list, but using "#".

Nested list
    * this is a list

      * with a nested list

    * and here the parent list continues

Preserving line breaks:
    | These lines are
    | broken exactly like in
    | the source file.

Source Code
    This is a normal text paragraph. The next paragraph is a code sample::

        Put your code here and     

        it can be spanned multiple lines.

    This is a normal text paragraph again.

Tables
    +----------+----------+
    | Header 1 | Header 2 |
    +----------+----------+
    |  github  | facebook |
    +----------+----------+

Simple tables
    === ===
    A   B
    === ===
    C   D
    === ===

..  .. [#f1] reStructuredText Primer
