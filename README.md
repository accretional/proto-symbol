# proto-symbol
ASCII, Unicode Characters, Unicode Scripts, Unicode Encoding per ISO/IEC 14977

Note: starting with ASCII, then probably a stub implementation of UTF-8, since that will be sufficient for compiler/dealing with protobuf's symbols (as far as we use them)

* Latest Unicode https://www.unicode.org/versions/Unicode17.0.0/
* Unicode Technical Reports https://www.unicode.org/reports/
* ASCII https://www.unicode.org/charts/PDF/U0000.pdf (NOTE: pdf is under copyright)
* LDML (Locale Data Markup Language) https://www.unicode.org/reports/tr35/tr35.html#Contents
* ICU (International Components for Unicode, C/C++ library, unicode data) https://icu.unicode.org/
* CLDR (Common Locale Data Repository) https://cldr.unicode.org/

LDML->CLDR->ICU->Code I think

LDML itself has a syntax https://www.unicode.org/reports/tr35/tr35.html#Unicode_Sets

Feeds into [proto-lex](https://github.com/accretional/proto-lex/). Subsystem of [proto-sym](https://github.com/accretional/proto-sym/)

## Unicode Copyright Stuff

Per Unicode's https://www.unicode.org/copyright.html basically this is what's open sourced by Unicode under the [Unicode License](https://www.unicode.org/license.txt):

"Unicode Data Files", everything below except things like PDF code charts and Technical Reports.

* https://www.unicode.org/Public/
* https://www.unicode.org/reports/
* https://www.unicode.org/ivd/data/
* https://github.com/unicode-org/ 

"Unicode Software",  source and compiled code under:

* https://www.unicode.org/Public/PROGRAMS/
* https://www.unicode.org/Public/cldr/
* https://github.com/unicode-org/
