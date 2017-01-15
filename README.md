
Overview
--------
This repository contains the BibTeX file and HTML templates that are used to
create the Mix Network Bibliography, mixbib. Find the HTML version here: http://mixbib.censor.watch

Build it
--------

You first need [`bibliogra.py`](https://github.com/NullHypothesis/bibliograpy)
to turn the BibTeX file into an HTML bibliography.

Then, run the following commands to write the bibliography to `OUTPUT_DIR`.

    $ ./fetch_pdfs.py references.bib OUTPUT_DIR
    $ bibliogra.py -H header.tpl -F footer.tpl -f references.bib OUTPUT_DIR


Acknowledgements
----------------
Thanks to Phillip Winter, this repository is inspired by the censorbib repo:

https://github.com/NullHypothesis/censorbib


Feedback
--------
Contact: IRC #applied-mixnetworks @ [hackint.org](https://www.hackint.org) - [webchat](https://webirc.hackint.org/#applied-mixnetworks)
