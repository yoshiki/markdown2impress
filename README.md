markdown2impress
==========

What is markdown2impress?
----------

**markdown2impress** is script to convert *markdown* into presentation using *impress.js*.

How to use?
----------

1. Write markdown.
2. Run **markdown2impress.pl**, then generate 'js/impress.js', 'css/impress.css' and 'index.html'.

        % markdown2impress README.md

Slide Dividing rule
----------

Each slide is divided into sections.

'data-*' attribute rule
----------

'data-*' attribute for impress.js represent HTML comment.

    <!-- data-x="2400" -->
    <!-- data-y="3000" -->
    <!-- data-z="-100" -->
    <!-- data-scale="10" -->
    <!-- data-rotate="90" -->

markdown2impress assume and calculate default x,y, if you do not specify this.

See [impress.js](http://bartaz.github.com/impress.js/) manual for details.

Command line options
----------

- **--width**

    Width of slide.

- **--height**

    Height of slide.

- **--column**

    Column of slide.

- **--outputdir**

    Output directory.
