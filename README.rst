Mixbib
======

This repository contains the BibTeX file and HTML templates that are used to
create the Mix Network Bibliography, mixbib. Find the HTML version here:
https://bib.mixnetworks.org

Build it
--------

You first need `bibliogra.py` https://github.com/NullHypothesis/bibliograpy
to turn the BibTeX file into an HTML bibliography.

Then, run the following commands to write the bibliography to `OUTPUT_DIR`.::

    $ ./fetch_pdfs.py references.bib OUTPUT_DIR
    $ bibliogra.py -H header.tpl -F footer.tpl -f references.bib OUTPUT_DIR


Acknowledgements
----------------
Thanks to Philipp Winter, this repository is inspired by the censorbib repo:

https://github.com/NullHypothesis/censorbib


Contact
-------

IRC #katzenpost @ OFTC https://www.oftc.net/

Mix network mailing list https://lists.mixnetworks.org/listinfo/mixnetworks
