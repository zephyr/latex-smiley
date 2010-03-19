

# latex-smiley


## Purpose

The “smilie” package provides a very easy way to typeset [emoticons](http://en.wikipedia.org/wiki/Emoticon) in LaTeX:

    \smiley{rose}

will output @}-;-'--- (even colored, rotated, …).


## How to Compile

Just type

    xelatex smiley.dtx

This will give you the documentation as well as the style file.

Even though the documentation depends on XeTeX, the package itself works under every LaTeX engine and can be created with

    tex smiley.dtx


## Status

This package has not yet reachead a stable status, so the user intferface may change!

### ToDo’s

* Resolve kerning problem.
* Add *much* more smileys.
* Optional key=value input at command level: \smiley[usecolor]{happy}

### Smileys

Most of the shorthands were taken from [The Canonical Smiley (and 1-Line Symbol) List by James Marshall](http://marshall.freeshell.org/smileys.html), which is much bigger as the [list of emoticons at Wikipedia](http://en.wikipedia.org/wiki/List_of_emoticons).


## Licence

Copyright 2010 by Dennis Heidsiek

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License, either version 1.3 of this license or (at your option) any later version. All versions of this license (including the latest one) can be accessed online [from the homepage of the LaTeX-project](http://www.latex-project.org/lppl/), but you can also find a local copy of version 1.3 in the LICENCE file.

This work has the LPPL maintenance status “*maintained*” and the Current Maintainer of this work is [Dennis Heidsiek](http://www.google.com/profiles/Dennis.Heidsiek).

This work consists of the file

* smiley.dtx

and the derived files

* smiley.sty
* smiley.pdf