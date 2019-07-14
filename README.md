# QuicksortComplexity

[![Travis][travis-shield]][travis-link]
[![DOI][doi-shield]][doi-link]

[travis-shield]: https://travis-ci.com/coq-contribs/quicksort-complexity.svg?branch=master
[travis-link]: https://travis-ci.com/coq-contribs/quicksort-complexity/builds


[doi-shield]: https://zenodo.org/badge/DOI/10.1007/978-3-642-02444-3_16.svg
[doi-link]: https://doi.org/10.1007/978-3-642-02444-3_16

The development contains:
- a set of monads and monad transformers for measuring a (possibly nondeterministic) algorithm's use of designated operations;
- monadically expressed deterministic and nondeterministic implementations of Quicksort;
- proofs of these implementations' worst- and average case complexity.


More details about the project can be found in the paper
[A Machine-Checked Proof of the Average-Case Complexity of Quicksort in Coq](http://www.cs.ru.nl/~james/2008-TYPES/final.pdf).

## Meta

- Author(s):
  - Eelis van der Weegen (initial)
- License: [Public Domain](LICENSE)
- Compatible Coq versions: Coq 8.8 or later (use releases for other Coq versions)
- Additional Coq dependencies: none

## Building and installation instructions

The easiest way to install the latest released version of QuicksortComplexity
is via [OPAM](https://opam.ocaml.org/doc/Install.html):

```shell
opam repo add coq-released https://coq.inria.fr/opam/released
opam install coq-quicksort-complexity
```

To instead build and install manually, do:

``` shell
git clone https://github.com/coq-contribs/quicksort-complexity
cd quicksort-complexity
make   # or make -j <number-of-cores-on-your-machine>
make install
```

After installation, the included modules are available under
the `QuicksortComplexity` namespace.



