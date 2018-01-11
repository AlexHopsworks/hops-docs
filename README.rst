Template
========

$project is a next-generation distribution of Apache Hadoop.

Build the documentation
------------------------

   # Install sphinx

   pip install sphinx sphinx-autobuild recommonmark sphinx_rtd_theme jupyter_sphinx_theme

   cd docs

   make html

   # Latex dependencies

   If latexpdf does not work you are probably missing latexmk and some macros. You can probably install less, but this is what was tested to work:

   sudo apt-get install python-sphinx
   sudo apt-get install texlive texlive-latex-extra texlive-lang-cjk latexmk

   # Serving
   sudo apt install nodejs
   sudo apt install npm
   npm install http-server -g

   cd docs/_build/html
   http-server -p <port>
   
   # Remote write
   https://github.com/randy3k/RemoteSubl

Contribute
----------

- Issue Tracker: github.com/logicalclocks/$project/issues
- Source Code: github.com/logicalclocks/

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: hopshadoop@google-groups.com

License
-------

The project is licensed under the Apache v2 license.
