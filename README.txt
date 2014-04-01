====================================================================
xappendix - An extensible appendix package
Maintained by Hugo van den Berg
E-mail: latex-dev@tbdwebdesign.nl
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt
--------------------------------------------------------------------

For a long time the appendix package was the de facto standard
to configure appendices, including insertion of a part heading
before the first appendix, and inclusion in the table of contents.

However, though interaction with the hyperref package is supported,
to add multiple sets of appendices one needs to take special care
to prevent duplicate page anchors.

This package aims to overcome these issues by adding built in
support for multiple appendix sets. Furthermore, configuration
has been rewritten to use pgfkeys as a frontend to redefining
internal strings, as well as the use of LaTeX3.

Installation
------------

The package is supplied in `dtx` format and as a pre-extracted
zip file, `xappendix.tds.zip`. The latter is most convenient for
most users: simply unzip this in your local texmf directory. If
you want to unpack the `.dtx` yourself, running `tex
xappendix.dtx` will extract the package whereas `latex
xappendix.dtx` will extract it and also typeset the documentation.

The package requires LaTeX3 support as provided in the
`l3kernel` and `l3packages` bundles. Both of these are available
on [CTAN](http://www.ctan.org/) as ready-to-install zip files.
Suitable versions are available in MiKTeX 2.9 and TeX Live 2012
(updating the relevant packages online may be necessary).
LaTeX3, and so `xappendix`, requires the e-TeX extensions: these
are available on all modern TeX systems.

Furthermore, the documentation uses the following packages, which
need to be installed previously, although they will be by default
on most systems.

- libertine
- xcolor
- booktabs
====================================================================

%% \CharacterTable
%%  {Upper-case    \A\B\C\D\E\F\G\H\I\J\K\L\M\N\O\P\Q\R\S\T\U\V\W\X\Y\Z
%%   Lower-case    \a\b\c\d\e\f\g\h\i\j\k\l\m\n\o\p\q\r\s\t\u\v\w\x\y\z
%%   Digits        \0\1\2\3\4\5\6\7\8\9
%%   Exclamation   \!     Double quote  \"     Hash (number) \#
%%   Dollar        \$     Percent       \%     Ampersand     \&
%%   Acute accent  \'     Left paren    \(     Right paren   \)
%%   Asterisk      \*     Plus          \+     Comma         \,
%%   Minus         \-     Point         \.     Solidus       \/
%%   Colon         \:     Semicolon     \;     Less than     \<
%%   Equals        \=     Greater than  \>     Question mark \?
%%   Commercial at \@     Left bracket  \[     Backslash     \\
%%   Right bracket \]     Circumflex    \^     Underscore    \_
%%   Grave accent  \`     Left brace    \{     Vertical bar  \|
%%   Right brace   \}     Tilde         \~}
