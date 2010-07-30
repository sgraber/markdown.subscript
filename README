# A Subscript Extension for Markdown

This extension adds the ability to add subscripts to Markdown documents.


## Usage

To subscript something, place a tilde symbol, '~', before and after the
text that you would like in subscript:  C~6~H~12~O~6~
The numbers in this example will be subscripted.  See below for more:

Examples:

    >>> import markdown
    >>> md = markdown.Markdown(extensions=['subscript'])
    >>> md.convert('This is sugar: C~6~H~12~O~6~')
    u'<p>This is sugar: C<sub>6</sub>H<sub>12</sub>O<sub>6</sub></p>'

Paragraph breaks will nullify subscripts across paragraphs. Line breaks
within paragraphs will not.

Drop subscript.py into your /site-packages/markdown/extensions/ directory.


## Calling from Command Line

markdown.py FILENAME.md -x subscript --file=OUTPUTFILE.html

Where:

* FILENAME.md = valid Markdown file to convert

* '-x subscript' calls the extension

* OUTPUTFILE.html = the resulting HTML conversion of the Markdown file


## Script Information

Author: [Shane Graber][1]

Repository: [http://github.com/sgraber/markdown.subscript][2]

Date: 2010-07-29


[1]: sgraber-at-gmail-dot-com
[2]: http://github.com/sgraber/markdown.subscript