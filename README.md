# Awesome Recursion Schemes [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/passy/awesome-recursion-schemes.svg?branch=master)](https://travis-ci.org/passy/awesome-recursion-schemes)

> A curation of useful resources for learning about and using recursion schemes.

## Introductions

- [Practical Recursion Schemes](https://jtobin.io/practical-recursion-schemes) -
  An introduction to pattern functors, fix points, anamorphisms, catamorphisms,
  paramorphisms and hylomorphisms, requiring very little prior knowledge.
- [An Introduction to Recursion Schemes](http://blog.sumtypeofway.com/an-introduction-to-recursion-schemes/) -
  A three-part series in which you discover recursion schemes from scratch and
  implement a small subset of Edward Kmett's library.
- [Understanding Algebras](https://www.schoolofhaskell.com/user/bartosz/understanding-algebras) -
  Bartosz Milewski explains F-algebras and shows how to use them in the context of
  catamorphisms.
- [Don’t fear the cat-armophism (nor the hylomorphism)](http://fho.f12n.de/posts/2014-05-07-dont-fear-the-cat.html) -
  Short introduction to morphisms & recursion schemes
  
## Articles

- [Recursion Schemes: A Field Guide (Redux)](http://comonad.com/reader/2009/recursion-schemes/) -
  List of various recursion schemes with code samples.
- [Catamorphisms](https://wiki.haskell.org/Catamorphisms) - Definition on the Haskell Wiki.
- [Catamorphisms](https://www.schoolofhaskell.com/user/edwardk/recursion-schemes/catamorphisms) -
  Short definition with code on School of Haskell by Edward Kmett.
  
## Papers

- [Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire, 1991, Meijer et al.](http://maartenfokkinga.github.io/utwente/mmf91m.pdf) -
  The original paper most of this is based on.
- [A Duality of Sorts, 2013, Hinze et al.](http://www.cs.ox.ac.uk/ralf.hinze/publications/Sorting.pdf) -
  Shows that many basic sorting algorithms exist as a pair, and that these pairs
  arise naturally out of the duality between folds and unfolds.
- [Sorting with Bialgebras and Distributive Laws, 2012, Hinze et al.](http://www.cs.ox.ac.uk/people/daniel.james/sorting/sorting.pdf) -
  Shows how paramorphisms and apomorphisms can be used for more efficient
  implementations of sorting algorithms.
- [Scrap your boilerplate: a practical design pattern for generic programming, 2003, SPJ et al.](http://research.microsoft.com/en-us/um/people/simonpj/Papers/hmap/hmap.ps) -
  Design pattern for writing programs that traverse data structures built from rich mutually-recursive data types

## Presentations

- [Slidedecks by Tim Philip Williams](http://www.timphilipwilliams.com/slides.html) -
  "Recursion Schemes by Example" and "Exotic Tools for Exotic Trades" provide
  concise definitions as well as practical examples of many recursion schemes.
- [Unifying Structured Recursion Schemes](https://www.youtube.com/watch?v=9EGYSb9vov8) -
  12 min presentation by Ralf Hinze, Nicolas Wu, and Jeremy Gibbons.
- [Recursion Schemes](https://www.youtube.com/watch?v=Zw9KeP3OzpU) -
  Presented by Tim Williams at the London Haskell meetup.
- [F-algebras or: How I Learned to Stop Worrying and Love the Type System](https://www.youtube.com/watch?v=PK4SOaAGVfg) -
  Presented by Anthony Burzillo at the NYC Haskell User's Group.
- [A Gentle Introduction to Recursion Schemes](https://www.youtube.com/watch?v=i5A2Amfcir8) -
  Presented by Jean Remi Desjardins at Lambdaconf 2016.

## Implementations

- [recursion-schemes](https://github.com/ekmett/recursion-schemes/) for
  Haskell. - The canonical implementation by Edward Kmett.
- [Matryoshka](https://github.com/slamdata/matryoshka) -
  Generalized folds, unfolds, and traversals for fixed point data structures in
  Scala.
- [purescript-matryoshka](https://github.com/slamdata/purescript-matryoshka) -
  A work-in-process port of matryoshka for PureScript.

## License

This content is licensed
under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
