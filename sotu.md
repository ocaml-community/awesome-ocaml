# State of the OCaml Ecosystem - August 2015

This document aims to be a community-driven review of the current state of the OCaml ecosystem and its suitability for various programming domains and tasks. The idea comes from Gabriel Gonzalez's the post about the [state of the Haskell ecosystem](https://github.com/Gabriel439/post-rfc/blob/master/sotu.md).

The content is grouped in various sections, each one covering a particular topic, inspired by the structure found in [Awesome OCaml](https://github.com/rizo/awesome-ocaml).

The topics are roughly sorted from greatest strengths to greatest weaknesses. Each programming area will also be summarized, compared to other languages, by a single rating of either:

- **Best in class**: the best experience in any language
- **Mature**: suitable for most programmers
- **Immature**: only acceptable for early-adopters
- **Bad**: pretty unusable

# Application Domains
<br/>

## Compilers and Programming Language Tools

- **Rating**: Best in class

- **Compilers written in OCaml**:

  - [cDuce](http://www.cduce.org/) - cDuce is a modern XML-oriented functional language with innovative features.
  - [Compcert C Compiler](http://compcert.inria.fr/) - It is a C Compiler supporting most of the ISO C90 and C99 / ANSI C  features.
  - [Eff Programming Language](http://www.eff-lang.org/) - Eff is a functional language with handlers of not only exceptions, but also of other computational effects such as state or I/O.
  - [Hack Programming Language](http://hacklang.org/)
  - [Haxe Programming Language](http://haxe.org/)
  - [Neko Programming Language](http://nekovm.org) - Originally the compiler was written in OCaml.
  - [Mezzo Programming Language](http://protz.github.io/mezzo/) - Mezzo is a programming language in the ML tradition, which places strong emphasis on the control of aliasing and access to mutable memory.
  - [OCaml-Java](http://www.ocamljava.org) - OCaml to Java bytecode compiler.
  - [Rhine](https://github.com/artagnon/rhine) – A Lisp on LLVM written in OCaml.
  - [Rust Programming Language](http://rust-lang.org) - Originally written in OCaml before bootstrapping.
  - [Quick C-- Target Language](http://www.cminusminus.org/) - It is now a dead project. [Github Repo](https://github.com/nrnrnr/qc--). [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).
  - [Others](http://caml.inria.fr/cgi-bin/hump.en.cgi?sort=0&browse=88) - Some other compilers implemented in OCaml, quite a few dead now.

- **Parser and Lexer Generators**:
  - [Menhir](http://gallium.inria.fr/~fpottier/menhir) – Menhir is a refined (LA)LR(1) parser generator for OCaml.
  - [dypgen](http://dypgen.free.fr/) – Self-extensible GLR parser generator
  - [ocamllex](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) – lex (and yacc) implementation for OCaml.
  - [Opal](https://github.com/pyrocat101/opal) – Self-contained monadic parser combinators for OCaml.
  - [DeCaP](http://lama.univ-savoie.fr/decap/) – Parser generator (aiming at efficiency)

- **Articles**:
  - [Kaleidoscope: Implementing a Language with LLVM in Objective Caml](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)
  - [Getting started with OCaml bindings for LLVM](http://nopaniers.calepin.co/getting-started-with-ocaml-bindings-for-llvm.html)

## Formal Verification

- **Rating**: Best in class

- **Notable projects**:

  - [Coq](http://coq.inria.fr/) – Coq is a formal proof management system. It provides a formal language to write mathematical definitions, executable algorithms and theorems together with an environment for semi-interactive development of machine-checked proofs.
  - [Why3](http://why3.lri.fr/) – Why3 is a platform for deductive program verification. It provides a rich language for specification and programming, called WhyML, and relies on external theorem provers, both automated and interactive, to discharge verification conditions.
  - [Frama-C](http://frama-c.com/what_is.html): static analysis toolbox for the C language
  - [TLA+](https://tla.msr-inria.inria.fr/tlaps/content/Download/Source.html): modeling and verification of concurrent and distributed systems
  - [Astrée](http://www.astree.ens.fr/): abstract-analysis based program analyzer
  - [Alt-Ergo](http://alt-ergo.lri.fr/) – Alt-Ergo is an open-source SMT solver dedicated to the proof of mathematical formulas generated in the context of program verification.
  - [Zenon](http://zenon-prover.org/): tableau-based prover used in `TLA+` and other projects.

- **Educational resources**: ...

## Scientific Computing

- **Rating**: Immature
- **Notable libraries**:
    - [Lacaml](http://mmottl.github.io/lacaml): OCaml-bindings to BLAS and LAPACK.
    - [Gsl](http://mmottl.github.io/gsl-ocaml): Bindings to the GNU Scientific Library.
    - [Sundials/ML](http://inria-parkas.github.io/sundialsml/) is an interface to the Sundials 
      suite of numerical solvers.
    - [odepack](http://forge.ocamlcore.org/projects/odepack/): Binding to ODEPACK.
    - [optimization1d](http://forge.ocamlcore.org/projects/optimization1d/): 
      Find extrema of 1D functions.
    - [Lbfgs](https://github.com/Chris00/L-BFGS-ocaml): Minimization of multidimensional 
      functions on bounded or unbounded domains.  Binding to
      [L-BFGS-B](http://users.iems.northwestern.edu/~nocedal/lbfgsb.html).
    - [FFTW3](https://github.com/Chris00/fftw-ocaml): Binding to the famous Fast Fourier
      Transform library [FFTW](http://www.fftw.org/).
    - [mesh](https://github.com/Chris00/mesh): Triangular mesh generation and manipulation.
    - [root1d](http://forge.ocamlcore.org/projects/root1d/): Find roots of 1D functions.
    - [integration1d](http://forge.ocamlcore.org/projects/integration1d/): Integration of 
      functions of one variable (inspired from QUADPACK).
    - [nlopt](https://bitbucket.org/mkur/nlopt-ocaml/): bindings to the
      [NLOpt](http://ab-initio.mit.edu/wiki/index.php/NLopt) optimization library. 

- **Educational resources**: ...

## Web Development

- **Rating**: Immature
- **Notable libraries**:
   - [COW](github.com/mirage/ocaml-cow): Set of tools and syntax extensions for generating
     and manipulating HTML, CSS, and XML with OCaml.
   - [Ocsigen](http://ocsigen.org/): High-level framework for developing client-server applications
     in OCaml
   - [BuckleScript](https://github.com/BuckleScript/bucklescript): JS compiler
   - [JS of OCaml (JSOO)](https://github.com/ocsigen/js_of_ocaml): Compiler from OCaml bytecode
     to JavaScript, intended to be used for large, high-performance projects.
   - [Reason](https://github.com/facebook/reason): JavaScript-ish syntax for OCaml.
- **Educational resources**: ...

## Mobile Applications

- **Rating**: Immature
- **Notable libraries**: ...
- **Educational resources**: ...

## System Programming

- **Rating**: Mature
- **Notable libraries**:

    - XenServer's [XAPI](https://github.com/xapi-project/xen-api) toolstack
    - [MirageOS](https://mirage.io/)  – a library operating system that constructs unikernels

- **Educational resources**: ...






# Programming ecosystem
<br/>

## Extensions or Replacements to stdlib

- **Notable libraries**:
  * [batteries-included](http://batteries.forge.ocamlcore.org/): a community-driven stdlib replacement
    with many data structures
  * [Core](https://github.com/janestreet/core_kernel): JaneStreet's replacement for the stdlib
  * [containers](https://github.com/c-cube/ocaml-containers): modular collection of data structures

## Algorithms and Data Structures

- **Rating**: Mature
- **Notable libraries**:
  * [htmt](https://github.com/rgrinberg/ocaml-hamt): Hash Array Mapped Tries
  * [ocamlgraph](http://ocamlgraph.lri.fr/): powerful graph library
- **Educational resources**: ...

## Code Analysis and Linters

- **Rating**: Immature
- **Notable libraries**:
  - [OCamlLint](https://github.com/cryptosense/ocamllint): Linter for finding common security and performance
     problems in OCaml programs.
- **Educational resources**: ...

## Parallelism and concurrency

- **Rating**: Immature
- **Notable libraries**:
    - [Lwt](http://ocsigen.org/lwt/) — A stand-alone monadic cooperative threading library.
    - [Async](http://janestreet.github.io/) — A monadic cooperative threading library integrated with the Core library.
- **Educational resources**: ...

## Databases

- **Rating**: Immature
- **Notable libraries**:
    - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/): Bindings to the PostgreSQL database
    - [SQLite3-OCaml](https://github.com/mmottl/sqlite3-ocaml): Bindings to the SQLite3 database
    - [Irmin](https://github.com/mirage/irmin): A distributed database based on Git, written in OCaml
- **Educational resources**: ...

## Developer Tools

- **Rating**: Immature
- **Notable libraries**: ...
- **Educational resources**: ...

## Graphics

- **Rating**: Immature
- **Notable libraries**: ...
- **Educational resources**: ...

## System interaction

- **Rating**: Mature
- **Notable libraries**:
    - [fileutils](https://forge.ocamlcore.org/projects/ocaml-fileutils/) – File manipulation utilties, such as (recursive) directory removal, and path manipulation.
    - [ExtUnix](https://github.com/ygrek/extunix) – interface to common
      and platform-specific Unix system functions
D-Bus (system libraries)
    - [Libvirt](https://libvirt.org/ocaml/) – a portable toolkit to interact with the virtualisation capabilities of Linux, Solaris and other operating systems.

## Foreign Function Interfaces

## User interfaces

- **Rating**: Immature
- **Notable libraries**:
    - [Cmdliner](http://erratique.ch/software/cmdliner/doc/Cmdliner.html) – Cmdliner is a powerful library for defining command line interfaces in a declarative fashion, include the support for subcommands.


## Networking

- **Rating**: ...
- **Notable libraries**: ...
- **Educational resources**: ...

## Package Management

- **Rating**: Mature
- **Notable libraries**:
  * [opam](http://opam.ocaml.org/): very active package manager for OCaml
- **Educational resources**: ...

## Communication protocols

- **Rating**: ...
- **Notable libraries**: ...
    - [Obus](https://github.com/diml/obus) – pure-OCaml (and fast!) implementation of the DBus protocol
- **Educational resources**: ...

## Data Formats

- **Rating**: ...
- **Notable libraries**:
  * [sexplib](https://github.com/janestreet/sexplib): S-expressions
  * [yojson](http://mjambon.com/yojson.html): JSON
- **Educational resources**: ...

## Serialization

- **Rating**: Mature
- **Notable libraries**: ...
- **Educational resources**: ...

## Testing

- **Rating**: Mature
- **Notable libraries**:
  * [OUnit](http://ounit.forge.ocamlcore.org/): unit testing
  * [Alcotest](https://github.com/mirage/alcotest): unit testing
- **Educational resources**: ...




