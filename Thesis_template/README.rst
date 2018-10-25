This is a template for a Ph.D. dissertation written in LaTeX that fulfills all of the requirements as stated by the graduate department of the Baskin School of Engineering as of June 2015. While a 12pt sans serif font can be used to fulfill the requirements, only a 12pt serif font is supported by this template.

Building
========

The main LaTeX document is dissertation.tex so compiling everything entails compiling only dissertation.tex.

LaTeX packages
--------------

The following LaTeX packages are required to compile ``dissertation.tex``.

* pbox
* appendix
* ucthesis

Linux
-----

To build use either ``make`` or ``latexmk``. The following two commands will both generate ``dissertation.pdf`` assuming all necessary packages are installed::

$ make
$ latexmk -pdf dissertation.tex

Windows
-------

Install `MikTek <http://www.miktex.org/download>`_ for the ``latex`` program and related tools.

Once Miktex is installed, Texworks can be used as an IDE.

Files
=====

The main file is dissertation.tex, which loads in the rest of the .tex files from other .tex files in the main directory. These .tex files are included by LaTeX into the dissertation.tex file and processed directly. To add more chapters, create a new .tex file and include it similar to the existing chapters.

Images should be stored in the ``Images/`` folder, possibly under directories for every chapter if there are a large number of images.
