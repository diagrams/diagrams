[![Build Status](https://secure.travis-ci.org/diagrams/diagrams.png)](http://travis-ci.org/diagrams/diagrams)

Diagrams is a full-featured framework and embedded domain-specific
langauge for creating declarative vector graphics and animations.

This package is just *a convenient wrapper* around the
[diagrams-core](http://github.com/diagrams/diagrams-core),
[diagrams-lib](http://github.com/diagrams/diagrams-lib), and
[diagrams-contrib](http://github.com/diagrams/diagrams-contrib)
packages, so they can be installed with a single `cabal install
diagrams` command.  

The package also comes with flags to enable two different backends.
The [cairo/gtk backend](http://github.com/diagrams/diagrams-cairo) can be
selected with the `-fcairo` flag.  This flag is enabled by default, so
if you do *not* want the cairo/gtk backend, you must explicitly
disable it with `-f-cairo`.

There is also an experimental
[native SVG backend](http://github.com/diagrams/diagrams-svg), which
can be enabled with `-fsvg`.

For more information, including a gallery of examples, tutorial, and
user manual, see the
[diagrams website](http://projects.haskell.org/diagrams).  For help,
join the `#diagrams` IRC channel on Freenode or the
[mailing list](http://groups.google.com/group/diagrams-discuss).
