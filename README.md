Awesome OCaml [![Build Status](https://travis-ci.org/ocaml-community/awesome-ocaml.svg?branch=master)](https://travis-ci.org/ocaml-community/awesome-ocaml)
=============

<img src="colour-logo.png" width="70%" />

> _**Everything you'll ever need on the road to mastering OCaml.**_

A curated list of references to awesome OCaml tools, frameworks, libraries and articles. Additionally there is a collection of freely available [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books), [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) and [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations).

If you're looking for comprehensive community-driven content about OCaml visit 📚[OCamlverse](https://ocamlverse.github.io/)!

For a quick introduction to the modern OCaml development workflow consult the [**OCaml for the impatient**](https://adambard.com/blog/getting-started-with-ocaml/) guide.

Your favorite package is not listed? Fork and [create a Pull Request](https://github.com/rizo/awesome-ocaml/edit/master/README.md) to add it!

## Contents

- [Community](#community)
- [Algorithms and Data Structures](#algorithms-and-data-structures)
- [Application Libraries](#application-libraries)
- [Benchmarking](#benchmarking)
- [Blogs](#blogs)
- [Books](#books)
- [Code Analysis and Linters](#code-analysis-and-linters)
- [Compilers and Compiler Tools](#compilers-and-compiler-tools)
- [Concurrency](#concurrency)
- [Databases](#databases)
- [Datetime](#datetime)
- [Developer Tools](#developer-tools)
- [Exercises](#exercises)
- [Formal Software Verification](#formal-software-verification)
- [General](#general)
- [Graphics](#graphics)
- [Internationalization](#internationalization)
- [User Interface](#user-interface)
- [Language-related](#language-related)
- [Logging](#logging)
- [Machine Learning](#machine-learning)
- [Messaging](#messaging)
- [Metaprogramming](#metaprogramming)
- [Metrics](#metrics)
- [Mobile Applications](#mobile-applications)
- [Networking](#networking)
- [Online Courses](#online-courses)
- [Package Management](#package-management)
- [Parallelism](#parallelism)
- [Questions](#questions)
- [Regular Expressions](#regular-expressions)
- [Science and Technical Computing](#science-and-technical-computing)
- [Security and Cryptography](#security-and-cryptography)
- [Semantic Technology](#semantic-technology)
- [Serialization](#serialization)
- [System Programming](#system-programming)
- [Testing](#testing)
- [Utilities](#utilities)
- [Web Development](#web-development)

* * *


## Community

- [Official OCaml Website](https://ocaml.org/)
- [OCaml Discourse Web Forum](https://discuss.ocaml.org/)
- [OCaml Discord Chat](https://discord.gg/ZBgYuvR)
- [Official OCaml Mailing List](http://caml.inria.fr/resources/forums.en.html)
- [OCaml Planet](https://ocaml.org/community/planet/)
- [OCaml SubReddit](https://www.reddit.com/r/ocaml/)


## Algorithms and Data Structures

- [Comparing a Machine Learning Algorithm Implemented in F# and OCaml](https://philtomson.github.io/blog/2014-05-29-comparing-a-machine-learning-algorithm-implemented-in-f-sharp-and-ocaml/)
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) – A generic graph library for OCaml.
- [ods](https://github.com/owainlewis/ods) – A large collection of data structures and algorithms for OCaml.
- [combine](https://github.com/backtracking/combine) – OCaml library for combinatorics <https://www.lri.fr/~filliatr/combine/>.
- [Decompress](https://github.com/mirage/decompress) - A pure OCaml implementation of Zlib.
- [Ke](https://github.com/mirage/ke) - Fast implementation of queue (FIFO) in OCaml.
- [Duff](https://github.com/mirage/duff) - Implementation of Rabin's fingerprint and delta compression by P. MacDonald in OCaml (same as [libXdiff](http://www.xmailserver.org/xdiff-lib.html)
- [ORaft](https://github.com/komamitsu/oraft) - Library of [Raft consensus algorithm](https://raft.github.io/raft.pdf) implemented in OCaml


## Application Libraries

- [Batteries Included](https://github.com/ocaml-batteries-team/batteries-included) – A community-maintained foundation library for your OCaml projects.
- [Cmdliner](https://github.com/dbuenzli/cmdliner) – Declarative definition of command line interfaces for OCaml.
- [Core](https://github.com/janestreet/core) – Jane Street Capital's full-fledged standard library overlay. A portable subset of Core is also available: [Core_kernel](https://github.com/janestreet/core_kernel).
- [Base](https://github.com/janestreet/base) - Jane Street Capital's dependency-free, quick-compiling, fully-portable across any environment that can run OCaml code standard library.
- [React](http://erratique.ch/software/react) – React is an OCaml module for functional reactive programming (FRP). It provides support to program with time varying values: declarative events and signals.
- [Minicli](https://github.com/UnixJunkie/minicli) – Minimalist library for command line parsing.
- [easy-format](https://github.com/mjambon/easy-format) – Pretty-printing library for OCaml.
- [ocaml-rpc](https://github.com/mirage/ocaml-rpc) – Light library to deal with RPCs in OCaml.
- [ocaml-containers](https://github.com/c-cube/ocaml-containers) – A lightweight, modular standard library extension, string library and interfaces to various libraries (bigarrays, unix, etc...). BSD license.


## Benchmarking

- [core_bench](https://github.com/janestreet/core_bench) – Micro-benchmarking library for OCaml by Jane Street.
  - [Getting Started with Core_bench](https://github.com/janestreet/core_bench/wiki/Getting-Started-with-Core_bench)
- [benchmark](https://github.com/Chris00/ocaml-benchmark) – Benchmarking functions for measuring the run-time of functions using latency or throughput.


## Blogs

- [Gagallium](http://gallium.inria.fr/blog/)
- [Type OCaml – Many things about OCaml](http://typeocaml.com/)
- [OCaml Platform](https://opam.ocaml.org/blog/)
- [Drup's Thingies](https://drup.github.io/)

## Books

- [More OCaml: Algorithms, Methods, and Diversions](https://www.amazon.com/More-OCaml-Algorithms-Methods-Diversions/dp/0957671113/) – In More OCaml John Whitington takes a meandering tour of functional programming with OCaml, introducing various language features and describing some classic algorithms. The book ends with a large worked example dealing with the production of PDF files. There are questions for each chapter together with worked answers and hints.
- [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html) by Allen Downey and Nicholas Monje – How to Think Like a Computer Scientist is an introductory programming textbook based on the OCaml language. It is a modified version of Think Python by Allen Downey. It is intended for newcomers to programming and also those who know some programming but want to learn programming in the function-oriented paradigm, or those who simply want to learn OCaml.
- [OCaml from the Very Beginning](http://ocaml-book.com/) by J. Whitington - OCaml from the Very Beginning will appeal both to new programmers, and experienced programmers eager to explore functional languages such as OCaml.
- [Pearls of Functional Algorithm Design](https://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383) by Richard Bird - It summaries 30 hard algorithm problems in function programming world. Although it is for Haskell, the algorithm problems are very interesting and trying to solve them in OCaml also helps the thinking of functional programming. Partial solutions in OCaml are [here](https://github.com/MassD/pearls).
- [Real World OCaml](https://realworldocaml.org/) by Y. Minsky, A. Madhavapeddy and J. Hickey - Functional programming for the masses.
- [Unix System Programming in OCaml](https://ocaml.github.io/ocamlunix/) by X. Leroy and D. Rémy – Introduction to Unix system programming, with an emphasis on communications between processes.
- [Using, Understanding, and Unraveling OCaml](https://caml.inria.fr/pub/docs/u3-ocaml) – This book describes both the OCaml language and the theoretical grounds behind its powerful type system.
- [Purely Functional Data Structures](https://www.amazon.co.uk/Purely-Functional-Structures-Chris-Okasaki/dp/0521631246/ref=sr_1_1?ie=UTF8&qid=1406279836&sr=8-1&keywords=functional+data+structures) - This is the first or only book focus on various data structures in FP world. A must-read one.
- [OCaml for Scientists](http://www.ffconsultancy.com/products/ocaml_for_scientists/) - by Jon Harrop.
- [Functional Programming in OCaml: A Principled Approach](http://www.cs.cornell.edu/courses/cs3110/2018fa/textbook/) - Textbook for CS 3110 Data Structures and Functional Programming, Cornell University.



## Code Analysis and Linters

- [Mascot](http://mascot.x9c.fr/) - Mascot is a style-checker for OCaml sources
- [pfff](https://github.com/returntocorp/pfff) – pfff is a set of tools and APIs to perform some static analysis, dynamic analysis, code visualizations, code navigations, or style-preserving source-to-source transformations such as refactorings on source code.
- [Infer](https://github.com/facebook/infer) - Infer is a static analyzer for Java, C and Objective-C
- [Frama-C](http://frama-c.com) - Frama-C is a static analysis and formal proof framework for C and C++
- [flow](https://github.com/facebook/flow) - flow is a static type checker for JavaScript
- [SLAyer](https://github.com/Microsoft/SLAyer) - SLAyer is an automatic formal verification tool that uses separation logic to verify memory safety of C programs.
- [MemCAD](https://github.com/Antique-team/memcad) - MemCAD is an abstract interpreter for shape analysis. MemCAD can verify C programs manipulating complex data structures.

## Program analysis
- [BAP](https://github.com/BinaryAnalysisPlatform/bap) - BAP is a reverse engineering and program analysis platform that targets binary programs.
- [BinCat](https://github.com/airbus-seclab/bincat) - BinCat is a binary code static analysis toolkit.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) - cwe_checker finds vulnerable patterns in binary executables.

## Compilers and Compiler Tools

- **Languages and Compilers**:
  - [cDuce](http://www.cduce.org/) - cDuce is a modern XML-oriented functional language with innovative features.
  - [Compcert C Compiler](http://compcert.inria.fr/) - It is a C Compiler supporting most of the ISO C90 and C99 / ANSI C  features.
  - [Eff Programming Language](http://www.eff-lang.org/) - Eff is a functional language with handlers of not only exceptions, but also of other computational effects such as state or I/O.
  - [Hack Programming Language](https://hacklang.org/)
  - [Haxe Programming Language](https://haxe.org/)
  - [Neko Programming Language](https://nekovm.org/) - Originally the compiler was written in OCaml.
  - [Mezzo Programming Language](https://protz.github.io/mezzo/) - Mezzo is a programming language in the ML tradition, which places strong emphasis on the control of aliasing and access to mutable memory.
  - [OCaml-Java](http://www.ocamljava.org/) - OCaml to Java bytecode compiler.
  - [Opa Programming Language](http://opalang.org/)
  - [Rhine](https://github.com/artagnon/rhine-ml) – A Lisp on LLVM written in OCaml.
  - [Rust Programming Language](https://www.rust-lang.org/) - Originally written in OCaml before bootstrapping.
  - [Quick C-- Target Language](http://www.cminusminus.org/) - It is now a dead project. [Github Repo](https://github.com/nrnrnr/qc--). [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).
  - [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) - An interpreter for finding subtle bugs in programs written in standard C

  - [Reason](http://facebook.github.io/reason/) - Friendly syntax & toolchain for OCaml by Facebook.
  - [RaML](http://raml.co/index.html) - Resource Aware ML (RaML) is a tool that automatically and statically computes resource-use bounds for OCaml programs.

- **Parser and Lexer Generators**:
  - [Opal](https://github.com/pyrocat101/opal) – Self-contained monadic parser combinators for OCaml.
  - [Sedlex](https://github.com/ocaml-community/sedlex) is a modern, encoding-agnostic (read: Unicode-supporting) lexer generator (the ppx-based successor to [ulex](http://www.cduce.org/download.html#side).)
  - [Menhir](http://gallium.inria.fr/~fpottier/menhir/) – Menhir is a LR(1) parser generator for OCaml.
    - See [ocaml-parsing](https://github.com/smolkaj/ocaml-parsing) for a clearer example of using Menhir and Sedlex to produce a useful parser,
    - ... and [Obelisk](https://github.com/Lelio-Brun/Obelisk), a neat project to produce readable LaTeX, HTML, or plain-text EBNF-style documentation for your grammar.
  - [ocamllex/ocamlyacc](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) – lex and yacc implementation for OCaml.
  - [Angstrom](https://github.com/inhabitedtype/angstrom) - Parser combinators built for speed and memory efficiency
- **Articles**:
  - [Kaleidoscope: Implementing a Language with LLVM in Objective Caml¶](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)


## Concurrency

Two concurrency libraries exist in OCaml: _Lwt_ and _Async_. They provide very similar functionality but make radically different decisions with regards to error handling and internal implementation details (see the links below for more details). [Real World OCaml](https://realworldocaml.org/) uses Async but a version of the [code examples translated to Lwt](https://github.com/dkim/rwo-lwt) is also available.

- **Libraries**:
  - [Lwt](http://ocsigen.org/lwt/) — A cooperative threads library for OCaml.
  - [Async](https://opensource.janestreet.com/async/) — A monadic concurrence library to go with the Core library.
- **Articles**:
  - [The blog post that introduced Async](https://blog.janestreet.com/announcing-async/)
  - [A user gives up on Async](http://rgrinberg.com/posts/abandoning-async/)
  - [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).

There is also an ongoing experimental project to make OCaml multiprocessor and multicore aware at [OCaml multicore](https://github.com/ocamllabs/ocaml-multicore) fork.

## Databases

- **Bindings**
  - [Dbm](https://forge.ocamlcore.org/projects/camldbm/) — A binding to the NDBM/GDBM Unix "databases".
  - [Mongo.ml](https://massd.github.io/mongo/) – An OCaml driver for Mongodb
  - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) — A type-safe interface to PostgreSQL in pure OCaml.
    - [ppx_pgsql](https://github.com/tizoc/ppx_pgsql) – A syntax extension for embedded SQL queries using PG'OCaml.
  - [PostgreSQL-OCaml](https://mmottl.github.io/postgresql-ocaml/) — An interface to PostgreSQL through the C API (`libpq`).
  - [SQLite3](https://github.com/mmottl/sqlite3-ocaml) — OCaml bindings to the SQLite3 database.
  - [Sqlite3EZ](https://mlin.github.io/ocaml-sqlite3EZ/) — Thin wrapper for SQLite3 with a simplified interface.
  - [ocaml-redis](https://github.com/0xffea/ocaml-redis) – Redis bindings for OCaml.
  - [mysql](http://ygrek.org.ua/p/ocaml-mysql/) – Bindings to libmysqlclient for interacting with MySQL databases.
  - [pgx](https://github.com/arenadotio/pgx) – A pure OCaml PostgreSQL client library
.
  - [mysql_protocol](https://github.com/slegrand45/mysql_protocol) – Implementation of MySQL Protocol with the Bitstring library.
- **New Implementations**
  - [Irmin](https://github.com/mirage/irmin) — A distributed database that follows the same design principles as Git.
  - [Obigstore](http://obigstore.forge.ocamlcore.org/) — A database with BigTable-like data model atop LevelDB.
  - [RunOrg](https://github.com/RunOrg/RunOrg) - It is a WIP database server written in OCaml.
- **Overlays**
  - [Sequoia](https://github.com/andrenth/sequoia) - Sequoia is a type-safe query builder for MySQL/MariaDB and PostgreSQL
  - [Macaque](https://github.com/ocsigen/macaque) — Macaque is a library for safe and flexible database queries using comprehensions on top of PG'OCaml.
  - [ORM](https://github.com/mirage/orm) — ORM for SQLite.
  - [Caqti](https://github.com/paurkedal/ocaml-caqti) - Cooperative-threaded access to relational data
- **Articles**:
  - [Implementing the Binary Memcached Protocol with Ocaml and Bitstring](https://andreas.github.io/2014/08/22/implementing-the-binary-memcached-protocol-with-ocaml-and-bitstring/)
  - [Interfacing OCaml and PostgreSQL with Caqti](https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11)


## Datetime

- [ISO8601](https://github.com/sagotch/ISO8601.ml)
- [calendar](http://calendar.forge.ocamlcore.org/)
- [odate](https://github.com/hhugo/odate)
- [ptime](http://erratique.ch/software/ptime)


## Developer Tools

- [Try OCaml](https://try.ocamlpro.com/) – Try OCaml in your web browser.
- [codingground](https://www.tutorialspoint.com/compile_ocaml_online.php) – Compile and execute OCaml code online.
- [Jupyter](https://github.com/akabe/ocaml-jupyter) – An OCaml kernel for the Jupyter notebook.
- [utop](https://github.com/ocaml-community/utop) – Universal toplevel for OCaml with support of multiline edition, history, real-time and context sensitive completion, colors, and more.
- [ocamlformat](https://github.com/ocaml-ppx/ocamlformat) - A command-line tool to format OCaml code.
- [ocamlbrowser](http://caml.inria.fr/pub/docs/manual-ocaml/browser.html) – A source and compiled interface browser, written using LablTk. Included in the standard distribution for ocaml <= 4.01 and with labltk for ocaml >= 4.02.
- [ghim](https://github.com/samoht/ghim) – A command-line tool to manage Github Issues.
- [OCaml Yeoman Generator](https://github.com/mabrasil/generator-ocaml) – Yeoman generator to scaffold OCaml modules.

- **Foreign Function Interface**:
  - [ctypes](https://github.com/ocamllabs/ocaml-ctypes) – Library for binding to C libraries using pure OCaml.
  - [ocaml-main-program-in-c](https://github.com/johnwhitington/ocaml-main-program-in-c) – Example build system for making mixed C/Ocaml binaries where the main program is in C.
  - [Modular foreign function bindings](http://openmirage.org/blog/modular-foreign-function-bindings)
  - [Py.ml](https://github.com/thierry-martinez/pyml) - OCaml bindings for Python.
- **Editor Integration**:
  - [merlin](https://github.com/ocaml/merlin) – Context sensitive completion for Ocaml in Vim and Emacs.
  - [tuareg](https://github.com/ocaml/tuareg) - OCaml mode for Emacs that can run the toplevel and the debugger within Emacs.
  - [merlin-eldoc](https://github.com/Khady/merlin-eldoc) – Emacs package to provide merlin's features through eldoc.
  - [vscode-ocaml](https://github.com/hackwaly/vscode-ocaml) – extension that provides OCaml language support for [VSCode](https://github.com/microsoft/vscode)
  - [OCaml Debugger](https://github.com/hackwaly/ocamlearlybird) – extension that provides OCaml Debugger for [VSCode](https://github.com/microsoft/vscode)
  - [Sublime better ocaml](https://github.com/whitequark/sublime-better-ocaml) – Better OCaml mode for Sublime Text.
    - [Sublime text package](https://github.com/def-lkb/sublime-text-merlin)
  - [ocp-index](http://www.typerex.org/ocp-index.html) – Easy access to the interface information of installed OCaml libraries. Provides standalone tools like `ocp-browser` and `ocp-grep`.
    - [ocp-browser](http://www.typerex.org/ocp-index.html#ocp-browser) – Small ncurses-based API and documentation browser.
    - [ocp-index-top](https://github.com/reynir/ocp-index-top) – Toplevel directive for looking up documentation using ocp-index.
    - [Sublime text package](https://sublime.wbond.net/packages/OCaml%20Autocompletion)
  - [ocp-indent](http://www.typerex.org/ocp-indent.html) – Indentation tool for OCaml, to be used from editors like Emacs and Vim.
    - [Vim plugin](https://github.com/def-lkb/ocp-indent-vim).
- **Code coverage**:
  - [Bisect_ppx](https://github.com/aantron/bisect_ppx)


## Exercises

- [99 problems](https://ocaml.org/learn/tutorials/99problems.html). 99% solutions are [here](https://github.com/MassD/99).
- [Rosetta Code](http://rosettacode.org/wiki/Category:OCaml)
- [OCaml at Exercism](http://exercism.io/languages/ocaml) – Exercism is your place to engage in thoughtful conversations about code. Explore simplicity, idiomatic language features, and expressive readable code. [Solutions](https://github.com/exercism/xocaml).


## Formal Software Verification

- [Coq](https://coq.inria.fr/) – Coq is a formal proof management system. It provides a formal language to write mathematical definitions, executable algorithms and theorems together with an environment for semi-interactive development of machine-checked proofs.
- [Why3](http://why3.lri.fr/) – Why3 is a platform for deductive program verification. It provides a rich language for specification and programming, called WhyML, and relies on external theorem provers, both automated and interactive, to discharge verification conditions.
- [Alt-Ergo](http://alt-ergo.lri.fr/) – Alt-Ergo is an open-source SMT solver dedicated to the proof of mathematical formulas generated in the context of program verification.


## General

- [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
- [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
- [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
- [Why We Use OCaml](https://espertech.wordpress.com/2014/07/15/why-we-use-ocaml)
- [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
- [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
- [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)
- [Why OCaml, why now?](http://spyder.wordpress.com/2014/03/16/why-ocaml-why-now/)
- [A blog about game development in OCaml](http://cranialburnout.blogspot.ca/)
- [(Functional) Alternatives to inheritance](http://ocamltutorials.blogspot.se/2013/06/alternatives-to-subtyping.html)
- [camlPDF](https://github.com/johnwhitington/camlpdf) – OCaml library for reading, writing and modifying PDF files.
- [slacko](https://github.com/Leonidas-from-XIV/slacko) – A neat interface for Slack in OCaml.
- [Learn X in Y minutes](https://learnxinyminutes.com/docs/ocaml/) - Where X=OCaml.


## Graphics

- **2D**
  - [archimedes](http://archimedes.forge.ocamlcore.org/) — 2D plotting library.
  - [cairo2](https://github.com/Chris00/ocaml-cairo) — Binding to Cairo, a 2D Vector Graphics Library. Integrates well with lablgtk.
  - [Vg](https://github.com/dbuenzli/vg) – Declarative 2D vector graphics for OCaml.
- **3D**
  - [glMLite](http://www.linux-nantes.org/~fmonnier/OCaml/GL/) — OpenGL bindings for OCaml. Provides an (experimental) functional API.
  - [lablgl](https://forge.ocamlcore.org/projects/lablgl/) — Interface to OpenGL. Integrates well with lablgtk.
  - [tgls](http://erratique.ch/software/tgls) — Thin bindings OpenGL 3.{2,3},4.{0,1,2,3,4} and OpenGL ES {2,3}.


## Internationalization

- [Camomile](https://github.com/yoriyuki/Camomile/) — A Unicode library for OCaml.
- [ocaml-m17n](https://github.com/whitequark/ocaml-m17n) — Multilingualization for OCaml source code. Allows using Unicode identifiers in OCaml source code.
- [Uucd](https://github.com/dbuenzli/uucd) — Unicode character database decoder for OCaml.
- [Uucp](https://github.com/dbuenzli/uucp) — Unicode character properties for OCaml.
- [Uunf](https://github.com/dbuenzli/uunf) — Unicode text normalization for OCaml.
- [Uuseg](https://github.com/dbuenzli/uuseg) — Unicode text segmentation for OCaml.
- [Uutf](https://github.com/dbuenzli/uutf) — Non-blocking streaming Unicode codec for OCaml.


## User Interface

- [lablgtk](http://lablgtk.forge.ocamlcore.org/) — GTK2 bindings for OCaml with various higher-level facilities to define GUIs.
- [lablqml](https://github.com/Kakadu/lablqml) – QML Qt5 bindings for OCaml.
- [labltk](https://forge.ocamlcore.org/projects/labltk/) — Interface to the Tcl/Tk GUI framework. In the standard distribution for ocaml <= 4.01.
- [TSDL](http://erratique.ch/software/tsdl) – Tsdl is an OCaml module providing thin bindings to the cross-platform SDL library.
- [Lambda-Term](https://github.com/ocaml-community/lambda-term) – Lambda-Term is a cross-platform library for manipulating the terminal. It provides an abstraction for keys, mouse events, colors, as well as a set of widgets to write curses-like applications.
- [Notty](https://github.com/pqwy/notty) - Notty is a declarative terminal library for OCaml, structured around a notion of composable images.
- [ocaml-linenoise](https://github.com/ocaml-community/ocaml-linenoise) - Self-contained OCaml bindings to linenoise, easy high level readline functionality in OCaml.


## Language-related

- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) – OCaml pattern-matching extended with regexps
- [Inlined records in constructors](https://www.lexifi.com/ocaml/inlined-records-constructors/)
- [Algebraic Data Types](https://espertech.wordpress.com/2014/07/30/algebraic-data-types/)
- [XEN – OCaml Best Practices for Developers](http://wiki.xen.org/wiki/OCaml_Best_Practices_for_Developers)
- [OCaml Style Guide (by Jane Street)](https://opensource.janestreet.com/standards/) - See also: [[1]](https://www.seas.upenn.edu/~cis500/cis500-f06/resources/programming_style.html), [[2]](http://www.cs.cornell.edu/Courses/cs312/2001sp/style.html), [[3]](https://www.seas.upenn.edu/~cis120/current/programming_style.shtml).
- [A safe but strange way of modifying OCaml compiler](https://bitbucket.org/camlspotter/compiler-libs-hack)
- [Fiddling with the OCaml Type System](https://technotroph.wordpress.com/2013/10/25/fiddling-with-the-ocaml-type-system/)


## Logging

- [dolog](https://github.com/UnixJunkie/dolog) – A dumb OCaml logger.
- [Volt](https://github.com/codinuum/volt) – A variant of Bolt OCaml logging tool.
- [Logs](http://erratique.ch/software/logs) - Logs provides a logging infrastructure for OCaml.

## Machine Learning

- **Libraries**
	- [Owl](https://ocaml.xyz/) - Scientific library with neural networks, algoritmic differentiation and ONNX support.
	- [Object detection convolutional neural network with OCaml (based on Owl)](https://github.com/owlbarn/owl_mask_rcnn).
	- [PyTorch bindings](https://github.com/LaurentMazare/ocaml-torch) - OCaml bindings for PyTorch.
- **Articles**
	- [Deep Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/deep-learning-experiments-in-ocaml/).
	- [Transfer Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/of-pythons-and-camels/).
	- [Reinforcement Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/playing-atari-games-with-ocaml-and-deep-rl/).

## Messaging

- [ocaml-zmq](https://github.com/issuu/ocaml-zmq) – ZeroMQ bindings for OCaml with Async and Lwt wrappers.
- [onanomsg](https://github.com/rgrinberg/onanomsg) – nanomsg bindings for OCaml.
- [Kafka](https://github.com/didier-wenzek/ocaml-kafka) – OCaml bindings for Apache Kafka.
- [AMQP](https://github.com/andersfugmann/amqp-client) – AMQP client library for Async and Lwt.
- [MPI](https://github.com/xavierleroy/ocamlmpi) – Message Passing Interface bindings for OCaml.
- [MQTT](https://github.com/j0sh/ocaml-mqtt) – OCaml implementation of the MQTT pubsub protocol.
- [capnp-ocaml](https://github.com/capnproto/capnp-ocaml) – OCaml code generator plugin for the Cap'n Proto serialization framework.

## Metaprogramming

- **Articles**:
  - [A Guide to Extension Points in OCaml](http://whitequark.org/blog/2014/04/16/a-guide-to-extension-points-in-ocaml/)
  - [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
  - [Syntax extensions without Camlp4: let's do it!](https://www.lexifi.com/ocaml/syntax-extensions-without-camlp4-lets-do-it/)
  - [Reading Camlp4 – Ambassador to the Computers](https://ambassadortothecomputers.blogspot.com/p/reading-camlp4.html)
- **Syntax Extensions**:
  - [ppx_import](https://github.com/ocaml-ppx/ppx_import) – Import is a syntax extension that allows to pull in types or signatures from other compiled interface files.
  - [ppx_string_interpolate](https://github.com/sheijk/ppx_string_interpolate) – A simple ppx filter to support string interpolation like `[%str "value of foo is $(foo)"]`.
  - [ppx_monad](https://github.com/rizo/ppx_monad) – Monad syntax extension for OCaml.
  - [ppx_deriving_yojson](https://github.com/whitequark/ppx_deriving_yojson) – A Yojson codec generator for OCaml.
- **Tools and Language Extensions**:
  - [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) – an OCaml dialect for multi-stage programming.
  - [Fan](http://zhanghongbo.me/fan/) – Fan is a compile-time metaprogramming system for OCaml, originally inspired from Camlp4. It's a combination of OCaml and Lispy Macros. It shares the same concrete syntax with OCaml.
  - [camlp5](https://camlp5.github.io/) - Camlp5 is a preprocessor-pretty-printer of OCaml.
  - [camlp4](http://caml.inria.fr/pub/docs/manual-camlp4/manual002.html) - Camlp4 is part of the standard OCaml distribution and is different from Camlp5.

## Metrics

- [prometheus](https://github.com/mirage/prometheus) – OCaml client library for Prometheus monitoring.

## Mobile Applications

- **Articles**:
  - [OCaml on iOS 7 Released](http://psellos.com/2014/08/2014.08.ocamlxarm-402.html)
  - [OCaml + Cordova = more secured, typed and hybrid mobile applications](https://blog.danny-willems.be/en/ocaml-cordova-secured-typed-hybrid-mobile-applications/)
- **Bindings**:
  - [Cordova plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list) – List of bindings to Cordova plugins. Get access to native device components like accelerometer, SMS, geolocation, etc in OCaml.


## Networking

- **HTTP Tools**:
  - [ocaml-cohttp](https://github.com/mirage/ocaml-cohttp) – Very lightweight HTTP server using Lwt or Async.
  - [ocurl](https://github.com/ygrek/ocurl) – OCaml bindings to libcurl.
  - [httpaf](https://github.com/inhabitedtype/httpaf) – A high performance, memory efficient, and scalable web server written in OCaml.
- [ocaml-dns](https://github.com/mirage/ocaml-dns) – A pure OCaml implementation of the DNS protocol.
- [fluent-logger](https://github.com/fluent/fluent-logger-ocaml) – Fluentd logger for OCaml.
- [charrua-unix](https://github.com/haesbaert/charrua-unix) - charrua-unix is a Unix DHCP daemon based on [charrua-core](https://github.com/haesbaert/charrua-core).


## Online Courses

- [Introduction to Functional Programming in OCaml](https://www.fun-mooc.fr/courses/parisdiderot/56002S02/session02/about).
- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php).
- [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).
- [University of Illinois](https://courses.engr.illinois.edu/cs421/fa2014/) - Course that uses OCaml to teach functional programming and programming language design


## Package Management
- **Distribution**:
  - [OPAM](http://opam.ocamlpro.com/) – A flexible Git-friendly package manager with multiple compiler support.
  - [ocamlfind](http://projects.camlcity.org/projects/findlib.html) — Local OCaml library manager. Used by most of the OCaml ecosystem.
  - [OCaml for Windows](https://fdopen.github.io/opam-repository-mingw) - opam repository and experimental build for Windows.
  - [makorel](https://github.com/sagotch/makorel) – Release OPAM packages easily.
  - [esy](https://github.com/esy/esy) - package.json workflow for native development with Reason/OCaml.

- **Build Tools**:
  - [Oasis](http://oasis.forge.ocamlcore.org/) - A tool to integrate a configure, build and install system in your OCaml project. It helps to create standard entry points in your build system and allows external tools to analyse your project easily.
    - [oasis2opam](https://github.com/ocaml/oasis2opam) — Tool to convert OASIS metadata to OPAM package descriptions.
  - [obuild](https://github.com/ocaml-obuild/obuild) – Simple package build system for ocaml.
  - [dune](https://github.com/ocaml/dune) – A composable and opinionated build system for OCaml (former jbuilder)
  - [jenga](https://github.com/janestreet/jenga) – Monadic build system from Jane Street.
  - [ocamlbuild](http://ocaml.org/learn/tutorials/ocamlbuild/) — Build system provided with the compiler.
  - [ocaml-makefile](https://github.com/mmottl/ocaml-makefile) — Easy to use Makefile for small to medium-sized OCaml-projects.
  - [topkg](https://github.com/dbuenzli/topkg) — OPAM-aware packaging system using ocamlbuild.
  - [Namespaces](https://github.com/aantron/namespaces) - ocamlbuild plugin that converts your directory tree into nested modules.
  - [Bazel](https://github.com/jin/rules_ocaml) - OCaml rules for [Bazel](https://bazel.build/), Google's multi-language and platform build tool.

## Parallelism

(_Note: Sorted from the easier to use to the more flexible._)

- **Libraries**:
  - [Parmap](http://rdicosmo.github.io/parmap/) — Provides easy-to-use parallel map and fold functions.
  - [ForkWork](https://github.com/mlin/forkwork) — A simple library for forking child processes to perform work on multiple cores.
  - [Functory](http://functory.lri.fr/About.html) — A distributed computing library which facilitates distributed execution of parallelizable computations in a seamless fashion.
  - [Rpc.Parallel](https://github.com/janestreet/rpc_parallel) — A library for spawning processes on a cluster of machines, and passing typed messages between them.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html) — An enhanced system platform library. Contains the `netmulticore` library to compute tasks on as many cores of the machine as needed.
  - [Nproc](https://github.com/MyLifeLabs/nproc) – Process pool implementation for OCaml.
  - [Parany](https://github.com/UnixJunkie/parany) – Parallelize computation over independent items, even if there is an infinite number of them.
  - [Sklml](http://sklml.inria.fr) – Functional parallel skeleton compiler and programming system for OCaml programs.
  - [SPOC](https://github.com/mathiasbourgoin/SPOC) - Libraries and syntax extensions to offload intensive computations to parallel accelerators (multicore CPUs, GPUs and other accelerators compatible with GPGPU frameworks).

- **Articles**:
  - [What is the state of OCaml's parallelization abilities?](https://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)


## Questions

- [OCaml polymorphism example other than template function?](https://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [OCaml - polymorphic print and type losing](https://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)


# Science and Technical Computing

- [biocaml](https://github.com/biocaml/biocaml) – OCaml Bioinformatics Library <http://biocaml.org>.
- [guizmin](https://github.com/pveber/guizmin) – OCaml library for building bioinformatics pipelines.
- [lacaml](https://mmottl.github.io/lacaml/) - OCaml bindings for BLAS/LAPACK (high-performance linear algebra Fortran libraries).
- [obandit](http://freux.fr/oss/obandit.html) - OCaml library for multi-armed bandits.
- [onumerical](https://github.com/cheshire/onumerical) – Numerical library for OCaml.
- [oml](https://github.com/hammerlab/oml) - OCaml library for general numerical work.
- [ocephes](https://github.com/rleonid/ocephes) - Bindings to frequently used `C` special funcitons library.
- [slap](https://github.com/akabe/slap) - A linear algebra library in OCaml with type-based static size checking for matrix operations.
- [tensorflow-ocaml](https://github.com/LaurentMazare/tensorflow-ocaml) – OCaml bindings for TensorFlow.
- [owl](https://github.com/owlbarn/owl) - OCaml numerical library: dense and sparse matrix, linear algebra, regressions, maths and stats functions.


## Regular Expressions

- [Re](https://github.com/ocaml/ocaml-re) – a pure OCaml regular expressions library with combinators, supporting several formats (glob, posix, str...)
- [ocaml-pcre](https://github.com/mmottl/pcre-ocaml) – bindings to the PCRE library (perl-compatible regular expressions)
- [Humane-re](https://github.com/rgrinberg/humane-re) – Humane-re attempts to provide an easy interface for 90% of your regex needs Courtesy of ocaml-re
- [Tyre](https://github.com/Drup/tyre) - Tyre is a set of combinators to build type-safe regular expressions, allowing automatic extraction and modification of matched groups.


## Security and Cryptography

- [ocaml-tls](https://github.com/mirleft/ocaml-tls) – TLS in pure OCaml.
- [Digestif](https://github.com/mirage/digestif) - Hash algorithms (like SHA* or BLAKE2*) in OCaml and C.
- [cryptokit](https://github.com/xavierleroy/cryptokit) – The Cryptokit library for OCaml provides a variety of cryptographic primitives that can be used to implement cryptographic protocols in security-sensitive applications.
- [nocoiner](https://github.com/marcoonroad/nocoiner) - A Commitment Schemes library for Multi-party Computations such as online Auctions and Gambling.
- [nocrypto](https://github.com/mirleft/ocaml-nocrypto) – A small cryptographic library behind the ocaml-tls project. It is built to be straightforward to use, adhere to functional programming principles and able to run in a Xen-based unikernel.

> Note: The differences between `nocrypto` and `cryptokit` cryptographic libraries are described in the following blog post: [OCaml-TLS: building the nocrypto library core](https://mirage.io/blog/introducing-nocrypto).


## Semantic Technology

- [OCaml-RDF](https://framagit.org/zoggy/ocaml-rdf) – OCaml library to manipulate RDF graphs and execute Sparql queries.


## Serialization

- [bencode](https://github.com/rgrinberg/bencode) — Bencode (.torrent file format) reader/writer.
- [biniou](https://github.com/mjambon/biniou) – Extensible binary data format, like JSON but faster.
- [jsonm](http://erratique.ch/software/jsonm) — Non-blocking streaming JSON codec for OCaml.
- [xmlm](http://erratique.ch/software/xmlm) — A streaming codec to decode and encode the XML data format.
- [yojson](https://github.com/ocaml-community/yojson) — An optimized parsing and printing library for the JSON format.
- [sexplib](https://github.com/janestreet/sexplib) – A S-expression parser and printer


## System Programming

- [Mirage OS](https://github.com/mirage/mirage) – Mirage is a programming framework for constructing secure, high-performance network applications across a variety of cloud computing and mobile platforms.
- [ocaml-fat](https://github.com/mirage/ocaml-fat) – Read and write FAT format filesystems from OCaml.
- [ocaml-git](https://github.com/mirage/ocaml-git) – Pure OCaml low-level git bindings.
- [ocaml-vchan](https://github.com/mirage/ocaml-vchan) – Pure OCaml implementation of the "vchan" shared-memory communication protocol.

- **Embedded systems**
  - [OMicroB](https://github.com/stevenvar/omicrob) - A virtual machine designed to run OCaml bytecode on AVR (Arduino for instance) micro-controlers.
  - [OCaPIC](http://www.algo-prog.info/ocapic/web/index.php?id=OCAPIC:OCAPIC) - An OCaml virtual machine for PIC18 micro-controlers.
  - [ocaml-esp32](https://github.com/sadiqj/ocaml-esp32) - A compiler for ESP32 SoC.


## Testing

- [Alcotest](https://github.com/mirage/alcotest) – A lightweight and colourful test framework.
- [OUnit](http://ounit.forge.ocamlcore.org/) – OUnit is a unit test framework for OCaml. It allows one to easily create unit-tests for OCaml code. It is based on HUnit, a unit testing framework for Haskell.
- [QCheck](https://github.com/c-cube/qcheck) — QCheck is a property testing library inspired from Haskell's QuickCheck
- [iTeML](https://github.com/vincent-hugot/iTeML) (formerly known as [qtest](http://batteries.vhugot.com/qtest/))  — supports inline pragma's to generate tests.
- [Kaputt](http://kaputt.x9c.fr/) —  comprehensive testing framework.
- [Pa_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) —  General inline testing macro's.
- [TestSimple](https://github.com/hcarty/ocaml-testsimple) - A lightweight unit testing framework compatible with the [Test Anything Protocol](https://testanything.org/).


## Utilities

- [ocaml-cuid](https://github.com/marcoonroad/ocaml-cuid) - Collision-resistant IDs for server scalability & database performance.


## Web Development

- **Frameworks**:
  - [Opium](https://github.com/rgrinberg/opium) – Sinatra like web toolkit for OCaml.
  - [Ocsigen Eliom](http://ocsigen.org/eliom/) – Eliom is a full-featured multi-tier framework, for developing multi-platform Web and mobile apps as 100% OCaml distributed applications. It can also be used for more traditional Web or mobile apps: Web sites, single page applications, REST API, etc.
  - [webmachine](https://github.com/inhabitedtype/ocaml-webmachine) – A REST toolkit for OCaml. OCaml webmachine is a layer on top of cohttp that implements a state-machine-based HTTP request processor. It's particularly well-suited for writing RESTful APIs. As the name suggests, this is an OCaml port of the webmachine project.
  - [incr_dom](https://github.com/janestreet/incr_dom) - A library for building dynamic webapps, using Js_of_ocaml
  - [ocaml-vdom](https://github.com/LexiFi/ocaml-vdom) - Elm architecture and (V)DOM for OCaml

- **Tools**:
  - [COW](https://github.com/mirage/ocaml-cow) – Caml on the Web (COW) is a set of parsers and syntax extensions to let you manipulate HTML, CSS, XML, JSON and Markdown directly from OCaml code.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)
    has many relevant web libraries —
    [Nethtml](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Nethtml.html)
    html parser,
    [Netasn1](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netasn1.html)
    for ASN.1 parsing,
    [Netencoding](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netencoding.html)
    for Base64, Quoted Printable, URL encoding and HTML escaping,
    [Netmime](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netmime.html)
    for MIME processing, etc. See the [list of
    modules](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/index.html)
    in Ocamlnet's manual.
  - [tyxml](http://ocsigen.org/tyxml) — Library to build valid (according to the W3C spec) Html and Svg trees.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml) – Js_of_ocaml is a compiler of OCaml bytecode to Javascript. It makes it possible to run Ocaml programs in a Web browser.
    - [commonjs_of_ocaml](https://github.com/AngryLawyer/commonjs_of_ocaml) - Easily import and export CommonJS modules from a js_of_ocaml project.
  - [BuckleScript](https://github.com/bloomberg/bucklescript) - BuckleScript is backend for OCaml to generate debuggable Javascript. It enables OCaml to integrate Javascript platform in a seamless way.
  - [ocaml-uri](https://github.com/mirage/ocaml-uri) – RFC3986 URI parsing library.
  - [Goji](https://github.com/klakplok/goji) – An OCaml bindings generator for JavaScript libraries.
  - [Syndic](https://github.com/Cumulus/Syndic) – RSS and Atom feed parsing
  - [ocaml-mustache](https://github.com/rgrinberg/ocaml-mustache) – mustache.js logic-less templates in OCaml.
  - [atdjs](https://github.com/barko/atdjs) – atd code generator for OCaml/js_of_ocaml.
  - [jingoo](https://github.com/tategakibunko/jingoo) – OCaml template engine almost compatible with jinja2.
  - [dispatch](https://github.com/inhabitedtype/ocaml-dispatch) – Path-based dispatching for client- and server-side applications.
  - [Lambda Soup](https://github.com/aantron/lambda-soup) - Functional HTML scraping and manipulation with CSS selectors, à la Python's Beautiful Soup.
  - [Markup.ml](https://github.com/aantron/markup.ml) - Error-recovering streaming HTML5 and XML parsers, serializers.
  - [gen_js_api](https://github.com/LexiFi/gen_js_api) - gen_js_api aims at simplifying the creation of OCaml bindings for Javascript libraries.
  - [routes](https://github.com/anuragsoni/routes) - Typed routes for OCaml/ReasonML web applications.

- **Open Source Projects**:
  - [Cumulus](https://github.com/Cumulus/Cumulus) – Hacker news like website with the OCaml framework Ocsigen

* * *

_Inspired by awesome projects line. Discover [more awesomeness](https://github.com/bayandin/awesome-awesomeness) :sparkles:._
