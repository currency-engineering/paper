Syntax notes about document
===========================

Reference
---------

latex.pdf

Graphics
--------

We use PNG rather than PDF. The reason is that to add mathematics formatting to the images, we need
to add a HTML layer over an SVG. This means that we can't just create a PDF directly from the SVG,
but need to create a screenshot of the wrapping div that includes both HTML and SVG.

    \usepackage{graphicx}


