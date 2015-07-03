ipython_notebook_goodies
========================

Random goodies for use in iPython Notebooks. 
Tested with the latest iPython Notebook 3.2.0

1. Table of Contents
--------------------

Make a table of contents for your notebook. Uses headings (e.g. H1, H2, etc.) to build TOC, 
and provides anchors (added where needed).

**Usage:** 

1. Add a *markdown* cell at the top of your notebook with the following:
```
<h1 id="tocheading">Table of Contents</h1>
<div id="toc"></div>
```
2. Add a *code* cell anywhere in the notebook with the following:
```
%%javascript
$.getScript('https://kmahelona.github.io/ipython_notebook_goodies/ipython_notebook_toc.js')
```
