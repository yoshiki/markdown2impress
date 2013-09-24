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
<!-- data-x="1000" -->
<!-- data-y="3000" -->
<!-- data-z="500" -->
<!-- data-scale="3" -->
<!-- data-rotate="90" -->

'data-*' attribute for impress.js represent HTML comment.
This comment must be write in secion.

    <!-- data-x="2400" -->
    <!-- data-y="3000" -->
    <!-- data-z="-100" -->
    <!-- data-scale="10" -->
    <!-- data-rotate="90" -->

markdown2impress assume and calculate default x,y, if you do not specify this.

See [impress.js](http://bartaz.github.com/impress.js/) manual for details.

Command line options
----------

- **--width=1200**

    Width of slide.

- **--height=800**

    Height of slide.

- **--column=5**

    Column of slide.

- **--outputdir=.**

    Output directory.

Export to PDF
----------

Add `?print` to the end of your presentation url like [`index.html?print`](./index.html?print) and export it to PDF using browser printing feature.

You will be able to share your slides in speakerdeck & slideshare.
    
