Texify
======
Texify is a simple wrapper script for pdflatex.  If using a bibliography in your
document, it will run the extra commands required.

Usage
-----
To use Texify, simply run `texify filename`, where `filename` is a valid LaTeX
file.  If `\bibliography` is used int he LaTeX source, it will invoke the
commands necessary to produce that bibiliography.  Your output will be produced
in a new directory called `out`.

Texify will attempt to open the output in a PDF Viewer.  If you're running KDE,
and Okular is installed, it will open it in Okular.  Otherwise, it will try to
detect Evince.

License
-------
Texify is released under the beer license, but it'd be great if you could do a
mental s/beer/coffee/g.
