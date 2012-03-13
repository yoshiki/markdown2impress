markdown2impress
==========

* * * * *


What is markdown2impress?
----------

**markdown2impress** is script to convert *markdown* into presentation using *impress.js*.

* * * * *


How to use?
----------

1. Write markdown.
2. Run **markdown2impress.pl**, then generate 'js/impress.js', 'css/impress.css' and 'index.html'.

        % markdown2impress markdown.md

* * * * *

Rules
----------

markdown2impress has two rules.

* * * * *

Rule 1
----------

Slide breaking is '\* \* \* \* \*'(&lt;hr&gt;).

* * * * *

Rule 2
----------

Use comment to set 'data-*'.

    <!-- data-x="2400" -->
    <!-- data-y="3000" -->
    <!-- data-z="-100" -->
    <!-- data-scale="10" -->
    <!-- data-rotate="90" -->

See [impress.js](http://bartaz.github.com/impress.js/) manual for details.

* * * * *

Command options
----------

- **--width**

    Width of slide.

- **--height**

    Height of slide.

- **--column**

    Column of slide.

- **--outputdir**

    Output directory.
