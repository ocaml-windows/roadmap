# TODO

### Compiler

* Relocatability of the compiler (WIP)
* Cross-compilation
* Debugging
* Auditing the Unix library

### Platform tools

* Fix build/test issues in the platform tools
* Add Windows CI for all platform tools
* Dune 4 development is Windows compatible
* opam
    * Rework depexts
    * MSVC story for opam 2.2+
* opam-repository
    * all packages have their availability properly set

### Ecosystem

* ocurrent and opam-health-check support Windows
* Deploy a opam-health-check instance for Windows
* Identify and fix errors in the libraries
* Develop bindings for Windows

### Benchmarking

All this while, the focus was on getting opam working on Windows. Not a lot of effort has gone into benchmarking. There are possibly many low hanging fruits.