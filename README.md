[![CI for specs](https://github.com/WebAssembly/spec/actions/workflows/ci-spec.yml/badge.svg)](https://github.com/WebAssembly/spec/actions/workflows/ci-spec.yml)
[![CI for interpreter & tests](https://github.com/WebAssembly/spec/actions/workflows/ci-interpreter.yml/badge.svg)](https://github.com/WebAssembly/spec/actions/workflows/ci-interpreter.yml)

# [DRAFT] Thread Spawning Proposal

This repository proposes a new WebAssembly instruction for spawning threads. It is a fork of the
[spec] repository for easier merging later. It is based on the [threads] proposal as a baseline,
though those spec changes are not yet included here. Read the [overview] for details.

[spec]: https://github.com/WebAssembly/spec
[threads]: https://github.com/WebAssembly/threads
[overview]: proposals/thread-spawn/Overview.md

Original `README` from upstream repository follows...

# spec

This repository holds the sources for the WebAssembly draft specification
(to seed a future
[WebAssembly Working Group](https://lists.w3.org/Archives/Public/public-new-work/2017Jun/0005.html)),
a reference implementation, and the official testsuite.

A formatted version of the spec is available here:
[webassembly.github.io/spec](https://webassembly.github.io/spec/),

Participation is welcome. Discussions about new features, significant semantic
changes, or any specification change likely to generate substantial discussion
should take place in
[the WebAssembly design repository](https://github.com/WebAssembly/design)
first, so that this spec repository can remain focused. And please follow the
[guidelines for contributing](Contributing.md).

# citing

For citing WebAssembly in LaTeX, use [this bibtex file](wasm-specs.bib).
