# Haskell treap implementation
A simple [treap](https://en.wikipedia.org/wiki/Treap) written in Haskell, for the [non-procedural programming course](https://is.cuni.cz/studium/predmety/index.php?do=predmet&kod=NPRG005&skr=2017&fak=11320) at Charles University.

## Benchmarks
The implementation has benchmarks written using [criterion](http://www.serpentine.com/criterion/). Install criterion using
```
cabal install -j --disable-tests criterion
```
The benchmarks may then be generated by running `make`. This generates `build/report.html` which is a human-readable report.
