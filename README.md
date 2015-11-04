latex-fontawesome
=================

Original project is [furl's latex-fontawesome](https://github.com/furl/latex-fontawesome). I edited this project to use latest [FontAwesome](http://fortawesome.github.io/Font-Awesome/) icons in XeLaTeX.

The current version of FontAwesome icons used is 4.4.0. See [this](http://www.ctan.org/tex-archive/fonts/fontawesome) for an older version (using FontAwesome version 3.1.1) with better documentation, examples, and for more information.

How to Use
----------

### Requirements
* You must have the FontAwesome font installed on your machine (download the `.otf` file [here](https://github.com/FortAwesome/Font-Awesome/blob/master/fonts/FontAwesome.otf?raw=true)).
* You must be using XeLaTeX and have the `fontspec` package installed.

### Usage
1. Download the `fontawesome.sty` file and put it in the same directory as the LaTeX file using the icons.
2. Include the package as normal (in the preamble of the `.tex` file, add the line `\usepackage{fontawesome}`).
3. Use an icon by typing `\faIconName`. For example, to use the `fa-quote-left` icon, convert it to camelcase and prepend the slash: `\faQuoteLeft`.

Make Latest fontawesome.sty
---------------------------

### Requirements
You need [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) to run ``makesty.py``.
```bash
$ sudo pip install beautifulsoup4
```

### Usage
```bash
$ python makesty.py
```
This should result in the creation of latest ``fontawesome.sty``


Notice
------
* You cannot use the icons which include a digit(0~9) in the name. (Ex. fa-500px)

Contact
-------

You are free to modify it.

If you have any questions, feel free to join me at [`#posquit0` on Freenode](irc://irc.freenode.net/posquit0) and ask away. Click [here](https://kiwiirc.com/client/irc.freenode.net/posquit0) to connect.

Good luck!
