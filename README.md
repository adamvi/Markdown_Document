Markdown_Document
=================

This Github repository provides a template for a nice looking HTML document by transforming a simple markdown text file into a static website using Jekyll. Because Github supports Jekyll, this document can be hosted for free on [Github pages](http://pages.github.com/).  Simply fork this repository and substitute your markdown (or similar) file for 'index.md'.  The example site based on the set up and fake document provided can be found [here](https://github.com/adamvi/Markdown_Document).

I use the kramdown flavor of markdown to allow for math formulas (via MathJax - LaTeX style).

The nicest example tables are provided using raw HTML, which sucks and kinda defeats the purpose of using markdown to begin with.  I also provide some more simple examples of tables produced in 'pure' markdown, and in LaTeX.  The LaTeX version requires the use of the more restrictive 'array' environment rather than 'tabular'.  None of these options are seem great to me, so if you have a better (i.e. 'pure' markdown) solution please let me know by forking this repository and a placing a pull request, or by adding an [issue](https://github.com/adamvi/Markdown_Tests2/issues).

Examples of how to include figures are also provided.  These examples that range from simple static images stored in a local directory or linked to a URL to interactive [D3 charts] produced using the [rCharts](http://ramnathv.github.io/rCharts/) package for the [R statistical programming language](http://www.r-project.org/).

Credit/Acknowledgement for the .css files go to [Scott Fortmann-Roe](http://scott.fortmann-roe.com/docs/BiasVariance.html), who credits [substance.io](http://substance.io/).
I have recycled/refreshed/reused them here, and extended them to a new level of Jekyll-ized, Github hosted awesome.

Enjoy!
