1.0.8 / 2011-06-29
==================

  * Fixed comments parsing.
    You can’t have comments at the end of a line # like this
    # But you can still have comments at the beginning of a line

1.0.7 / 2011-06-28
==================

  * Added `getRaw()` method to PyStringNode
  * Updated vendors

1.0.6 / 2011-06-17
==================

  * Updated vendors

1.0.5 / 2011-06-10
==================

  * Fixed bug, introduced with 1.0.4 - hash in PyStrings

1.0.4 / 2011-06-10
==================

  * Fixed inability to comment pystrings

1.0.3 / 2011-04-21
==================

  * Fixed introduced with 1.0.2 pystring parsing bug

1.0.2 / 2011-04-18
==================

  * Fixed bugs in text with comments parsing

1.0.1 / 2011-04-01
==================

  * Updated vendors

1.0.0 / 2011-03-08
==================

  * Updated vendors

1.0.0RC2 / 2011-02-25
=====================

  * Windows support
  * Missing phpunit config

1.0.0RC1 / 2011-02-15
=====================

  * Huge optimizations to Lexer & Parser
  * Additional loaders (Yaml, Array, Directory)
  * Filters (Tag, Name, Line)
  * Code refactoring
  * Nodes optimizations
  * Additional tests for exceptions and translations
  * Keywords dumper

0.2.0 / 2011-01-05
==================

  * New Parser & Lexer (based on AST)
  * New verbose parsing exception handling
  * New translation mechanics
  * 47 brand new translations (see i18n)
  * Full test suite for everything from AST nodes to translations
