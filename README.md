Texify
======
Texify automatically runs the extra commands to produce a bibiliography with 
BiBTeX.

Usage
-----
To use Texify, simply run `texify <filename>.tex`.  If `\bibliography` is used 
int he LaTeX source, it will invoke the commands necessary to produce that 
bibiliography.  Your output will be produced in a new directory called `out`.

Texify automatically opens the generated PDF file.  I'm using Evince right now, 
but you can change this to Okular or anything else.
