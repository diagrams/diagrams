[![Build Status](https://secure.travis-ci.org/diagrams/diagrams.png)](http://travis-ci.org/diagrams/diagrams)

[diagrams] is a full-featured framework and domain-specific langauge
(embedded in [Haskell]) for creating declarative vector graphics and
animations.

[diagrams]: http://projects.haskell.org/diagrams/
[haskell]: http://www.haskell.org/haskellwiki/Haskell

This package is just *a convenient wrapper* around the
[diagrams-core], [diagrams-lib], and [diagrams-contrib] packages, so
they can be installed with a single `cabal install diagrams` command.

[diagrams-core]: http://github.com/diagrams/diagrams-core
[diagrams-lib]: http://github.com/diagrams/diagrams-lib
[diagrams-contrib]: http://github.com/diagrams/diagrams-contrib

The package also comes with flags to enable two different backends.
The [native SVG backend](http://github.com/diagrams/diagrams-svg) is
enabled by the `-fsvg` flag and is enabled by default.  If you don't
want it, you must explicitly disable it with `-f-svg`.

The [cairo/gtk backend](http://github.com/diagrams/diagrams-cairo) is
disabled by default but can be selected with the `-fcairo` flag.

# Installation

```
cabal update && cabal install diagrams
```

or, to get the cairo backend in addition to the SVG backend

```
cabal update && cabal install gtk2hs-buildtools && cabal install -fcairo diagrams
```

# Reporting bugs

Issue trackers for all diagrams-related repositories are hosted under
the [diagrams organization on github](http://github.com/diagrams).  If
you know the specific package containing the bug, report it in the
issue tracker specific to that package (for example,
[diagrams-lib](http://github.com/diagrams/diagrams-lib/issues)).
Otherwise, just report the issue in the issue tracker for the
[general diagrams repository](http://github.com/diagrams/diagrams/issues).

# Further reading

For more information, including a gallery of examples, tutorial, and
user manual, see the
[diagrams website](http://projects.haskell.org/diagrams).  For help,
join the `#diagrams` IRC channel on Freenode or the
[mailing list](http://groups.google.com/group/diagrams-discuss).
