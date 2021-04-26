# hebrew text tools

This repo contains a script that has code useful for automating pulling Jewish texts from Sefaria.

It has a number of functions to "tweak" texts, such as adding missing kamatz-katans, marking shva na with a rafe, etc.
These are useful to change around diacritics in an existing texts if desired.

It also has a Sefaria-pulling function, which accepts a query string and returns text.
Depending on parameters in the query string this can include running it through the converting functions.
It also can add syntax useful for TeX.
There is a further function that can run a TeX file through the puller, so a TeX file can have queries which are then expanded into text references.

The shem converter function is based on the shem converted from Siddur Olas Tamid by wolf-math, available here: https://github.com/wolf-math/olastamid

These functions have been tested but not exhaustively.
Please use caution, and keep backups of text run through the converters.
Please report any errors found.
