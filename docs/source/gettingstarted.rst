.. _gettingstarted:
Getting Started
===============

Sphinx is a documentation generator or a tool that translates a set of plain text source files into various output formats, automatically producing cross-references, indices, etc. That is, if you have a directory containing a bunch of reStructuredText or Markdown documents, Sphinx can generate a series of HTML files, a PDF file (via LaTeX), man pages and much more.

Sphinx focuses on documentation, in particular handwritten documentation, however, Sphinx can also be used to generate blogs, homepages and even books. Much of Sphinx’s power comes from the richness of its default plain-text markup format, reStructuredText, along with its significant extensibility capabilities.

The goal of this document is to give you a quick taste of what Sphinx is and how you might use it. When you’re done here, you can check out the installation guide followed by the intro to the default markup format used by Sphinx, reStucturedText.

For a great “introduction” to writing docs in general – the whys and hows, see also Write the docs, written by Eric Holscher.


Setting up the documentation sources
-------------------------------------

The root directory of a Sphinx collection of plain-text document sources is called the source directory. This directory also contains the Sphinx configuration file conf.py, where you can configure all aspects of how Sphinx reads your sources and builds your documentation.

Defining document structure
---------------------------

Let’s assume you’ve run sphinx-quickstart. It created a source directory with conf.py and a root document, index.rst. 