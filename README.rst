Bookbook converts a set of notebooks in a directory to HTML or PDF,
preserving cross references within and between notebooks.

This code is in early development, so use it at your own risk.

It expects a directory of notebooks whose names indicate their order, e.g.
``01-introduction.ipynb``. To run it::

    python3 -m bookbook.html           # HTML output under html/
    python3 -m bookbook.latex [--pdf]  # Latex/PDF output as combined.(tex|pdf)

Add ``--help`` to either command for more options.

installation
------------

To install locally as an editable install run::

    pip install flit
    flit install --symlink

